<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>{{ msg }}</h1>
    <h1>{{ msg }}</h1>
    <h1>{{ msg }}</h1>
    <h1>{{ msg }}</h1>
    <h1>{{ msg }}</h1>
    <h1 class="my">哈哈哈哈</h1>
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<script>
import { Button } from "vant";
export default {
  name: "HelloWorld",
  components: {
    [Button.name]: Button
  },
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello
    border 1px solid red
    .my 
        background-color black  
</style>

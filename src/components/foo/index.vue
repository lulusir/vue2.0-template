<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="test"></div>
    <router-link to="/page2">滚动加载</router-link>
    <router-link to="/page3">全屏swiper</router-link>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: '一键开启使用vue2.0'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
h1 {
  color: #42b983;
}

.test{
	width: 100px;
	height: 100px;
	background-image: url("./img/logo.png");
  background-size: 100% 100%;
  display: inline-block;
}
</style>

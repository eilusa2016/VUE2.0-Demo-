<!-- 展示模板 -->
<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <!--hello></hello-->
  </div>

</template>

<script>
 // 导入组件
import Hello from './components/HelloWorld'
export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
<!-- 样式代码 -->
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

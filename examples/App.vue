<!--
 * @Author: your name
 * @Date: 2020-05-21 09:41:40
 * @LastEditTime: 2020-05-21 09:50:45
 * @LastEditors: your name
 * @Description: In User Settings Edit
 * @FilePath: \jeft-vue-plugin\jeft-vue-longtap\examples\App.vue
--> 
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="长按触发事件"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

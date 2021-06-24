<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo_ROCM_RGB_WEB.jpg" style="width: 20%; height: 30%;">
    <HelloWorld msg="ROC Mondriaan Point Collector"/>
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


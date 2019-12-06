<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <p class="bg-green-300 text-blue-700">Classes added to this element are only used for testing and setting up this starter. Resulted in rewriting the "serve" parameter and using concurrently.</p>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

import '../public/build/main.css' // use compiled file here. when running npm run build all the unused css will be purged to keep filesize low.

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

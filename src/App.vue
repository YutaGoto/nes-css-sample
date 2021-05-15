<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import "nes.css/css/nes.min.css"
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
html, body, pre, code, kbd, samp {
  font-family: "Press Start 2P";
}

#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  max-width: 980px;
  margin: 0 auto;
}
</style>

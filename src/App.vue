<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo_element.png">
    <HelloElement msg="Welcome to ElementUI with Vue.js App"/>
  </div>
</template>

<script>
import HelloElement from './components/HelloElement.vue'

export default {
  name: 'app',
  components: {
    HelloElement
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

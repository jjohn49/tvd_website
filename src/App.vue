<template>
  <Home msg="Welcome to Your Vue.js App"/>

  <services/>
</template>

<script>
import Home from './components/Home.vue'
import Services from './components/MenuBar.vue'

export default {
  name: 'App',
  components: {
    Home,
    Services
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
  color: white;
}
body{
  background: black;
}
</style>

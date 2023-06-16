<template>
  <div id="app">
    <ConversorDeMoeda/>

  </div>
</template>

<script>
import ConversorDeMoeda from "./components/ConversorDeMoeda.vue"

export default {
  name: 'App',
  components: {
    ConversorDeMoeda
  
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

<template>
  <div id="app">
    <itune/>
  </div>
</template>

<script>
import itune from './components/itune.vue'

export default {
  name: 'App',
  components: {
    itune
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

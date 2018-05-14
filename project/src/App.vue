<template>
  <div id="app">
    <top />
  </div>
</template>

<script>
import top from './components/top'

export default {
  name: 'App',
  components: {
    top
  }
}
</script>

<style>
#app {
  font-family: 'Roboto', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

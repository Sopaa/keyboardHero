<template>
  <div id="app">
    <top/>
    <bot/>
  </div>
</template>

<script>
import top from './components/top'
import bot from './components/bot'

export default {
  name: 'App',
  components: {
    top,
    bot
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

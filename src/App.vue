<template>
  <div id="app">
    <screen1></screen1>
  </div>
</template>

<script>
import Screen1 from './components/Screen1.vue'

export default {
  name: 'app',
  components: {
    Screen1
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
}
</style>

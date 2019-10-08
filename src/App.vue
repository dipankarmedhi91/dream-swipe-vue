<template>
  <div id="app">
    <DreamSwipe msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import DreamSwipe from './components/DreamSwipe.vue'

export default {
  name: 'app',
  components: {
    DreamSwipe
  }
}
</script>

<style>
body{
  background-image: linear-gradient(to top, #cfd9df 0%, #e2ebf0 100%);
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div class="dreamswipe-main">
    <h1>{{ msg }}</h1>
    
    <Header/>
    <Navigation/>
    
  </div>
</template>

<script>
import Header from './Header/Header.vue';
import Navigation from './Navigation/Navigation.vue';

export default {
  components:{
    Navigation,
    Header
  },
  props: {
    msg: String
  }
}
</script>

<style lang='scss' scoped>
h3 {
  margin: 40px 0 0;
}
.dreamswipe-main{
  position: relative;
  height: 100vh;
  top:0;
  .dark{
    background-color: black;
    color: white;
  }
}
</style>

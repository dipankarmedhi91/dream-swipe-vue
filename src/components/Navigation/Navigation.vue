<template>
  <div class='main-sidebar'>
        <div class='main-sidebar-title'>OPTIONS</div>
  </div>
</template>

<script>
export default {
  props: {
    msg: String
  }
}
</script>

<style lang='scss' scoped>
h3 {
  margin: 40px 0 0;
}
.main-sidebar{
  position: fixed;
  height: calc(100vh - 90px);
  width: 230px;
  top:0;
  left:0;
  margin-top: 80px;
  margin-left: 20px;
  border-radius: 5px;
  background-image: linear-gradient(to top, #30cfd0 0%, #330867 100%);
  .main-sidebar-title{
    background-color: black;
    color: white;
  }
}
</style>
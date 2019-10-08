<template>
  <div class='main-header'>
      <div style='display:flex;'>
        <div class='main-title'>DreamSwipe</div>
      </div>
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
.main-header{
  position: fixed;
  display: flex;
  width: 100vw;
  top: 0;
  left: 0;
  height: 60px;
  text-align: center;
  justify-content: center;
  background-image: linear-gradient(to right, #4facfe 0%, #00f2fe 100%);
  .main-title{
      position: relative;
      display: flex;
      align-items: center;
  }
}
</style>
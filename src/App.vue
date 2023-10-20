<script setup>
import HeaderView from "./view/HeaderView.vue";
</script>

<template>
  <video autoplay muted src="../public/TEST RENDER 01 8SEC.mp4"></video>
  <div class="header">
    <HeaderView/>
  </div>
</template>
<style scoped>
@font-face{
    font-family:"North-well";
    src: url("./assets/fonts/Northwell/Northwell.ttf");
}
video{
  object-fit:fill;
  width:100%;
  position:fixed;
  top:0;
  z-index:-1;
}
.header{
  padding: 5px 20px;
  background-color: hsla(0, 100%, 100%,0.3);
  border-radius: 0 0 20px 20px;
}
</style>
  


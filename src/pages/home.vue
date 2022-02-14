<template>
  <div class="home">
    <img src="../assets/weileidesign.gif" alt="">
    <div class="box"><img src="../assets/weilei.jpg" alt="">
      <p>Weilei Design源自魏雷先生</p></div>
<!--    <div class="box"><img src="../assets/bianshidu.png" alt="">-->
<!--      <p>极具辨识度的设计风格</p></div>-->
<!--    <div class="box"><img src="../assets/chaoliu.jpg" alt="">-->
<!--      <p>引领时代设计潮流</p></div>-->


  </div>
</template>

<script>
export default {
  name: "home"
}
</script>

<style scoped>
 .box {
  border: 1px solid black;
}
 .home{
   display: flex;
   flex-direction: column;
   align-items: center;
 }
 .box img{
   width: 200px;
 }
</style>
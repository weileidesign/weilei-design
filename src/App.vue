<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup

</script>

<template>
  <div class="root">
  <section><h3>Weilei Design 魏雷设计 官网</h3>
    <ul class="menu">
      <li>
        <router-link to="/">主页</router-link>
      </li>
      <li>
        <router-link to="/about">关于</router-link>
      </li>
    </ul></section>

    <router-view></router-view>
  </div>

</template>

<style>
#app {
  font-family: 宋体, serif;
}

.root {
  display: flex;
  margin: 40px;
  flex-direction: column;
}

.menu {
  height: 43px;
  overflow: hidden;
  border-bottom-left-radius: 6px;
  border-bottom-right-radius: 6px;
  border-top: 3px solid #b30000;
  background: url(./assets/header.png);
  background-repeat: repeat
  /*background-image: linear-gradient(#FF0000, #00FF00);*/
}

.menu li {
  width: 10%;
  float: left;
  border-left: 1px solid #bd0101;
  list-style-type: none;
}

.menu li a {
  display: block;
  font-size: 16px ! important;
  font-weight: 600;
  line-height: 40px;
  text-align: center;
  cursor: pointer;
  color: #fff
}

.menu li a:hover {
  background: #9a001d
}
</style>

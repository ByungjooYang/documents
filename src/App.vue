<template>
  <div>
    <HeaderTemplate/>
    <LeftMenu/>
    <router-view/>
    <FooterTemplate/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body{
  margin: 0;
}
</style>
<script setup>
import HeaderTemplate from "@/layouts/HeaderTemplate.vue";
import FooterTemplate from "@/layouts/FooterTemplate.vue";
import LeftMenu from "@/layouts/LeftMenu.vue";
</script>
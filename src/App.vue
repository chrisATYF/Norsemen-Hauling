<script setup>
import { RouterView } from 'vue-router'
import Nav from './components/Nav.vue';
</script>

<template>
  <Nav></Nav>
  <RouterView />
  <div class="btmContent">
    <p>&copy 2023 - Norsemen Hauling</p>
  </div>
</template>

<style>
:root {
  --darkBg: rgb(21, 21, 21);
  --space: 200px;
  --radius: 25px;
  --shadow: 5px 5px 10px 5px rgba(0, 0, 0, 0.500);
  --shadow-mobile: 2.5px 2.5px 5px 2.5px rgba(0, 0, 0, 0.500);
}


.btmContent {
  bottom: 0;
  width: 100%;
  padding: 5px;
  margin: 0;
  text-align: center;
}
</style>
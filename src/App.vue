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

<style scoped>
.btmContent {
  bottom: 0;
  width: 100%;
  padding: 5px;
  margin: 0;
  text-align: center;
}
</style>
<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Navbar from './components/Navbar.vue'
</script>

<template>
  <div id="app">
    <Navbar />
    <h1 class="device"> device not supported</h1>
  </div>
</template>

<style scoped>
.device {
  text-align: center;
  margin-top: 50px;
}
@media screen and (min-width: 300px) {
    .device{
      display: none;
    }
}
</style>

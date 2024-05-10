<template>
  <div class="header">
    <NavBar />
  </div>
</template>
<script lang="ts" setup>
import NavBar from "../Molecules/NavBar.vue";
</script>
<style scoped>
.header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 2000;
}
</style>

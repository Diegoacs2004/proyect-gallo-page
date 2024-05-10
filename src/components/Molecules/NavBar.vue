<template>
  <div class="navbar">
    <LogoImage class="logo" />
    <v-spacer></v-spacer>
    <PageLinks class="links-header" />
  </div>
</template>
<script lang="ts" setup>
import LogoImage from "../atoms/LogoImage.vue";
import PageLinks from "../atoms/PageLinks.vue";
</script>
<style scoped>
.navbar {
  width: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  background-color: #2f2f2f;
}

.logo {
  margin-top: 16px;
  margin-left: 16px;
}

.links-header {
  margin-top: 16px;
  color: white;
  margin-right: 16px;
}
</style>

<template>
  <div class="footer">
    <FooterLinks />
  </div>
</template>
<script lang="ts" setup>
import FooterLinks from "../Molecules/FooterLinks.vue";
</script>
<style scoped>
.footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  z-index: 2000;
}
</style>

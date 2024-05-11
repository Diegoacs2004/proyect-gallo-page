<template>
  <div class="footer">
    <ContactLink class="links-footer" />
  </div>
</template>
<script lang="ts" setup>
import ContactLink from "../atoms/ContactLinks.vue";
</script>
<style scoped>
.footer {
  background-color: #2f2f2f;
  padding: 24px;
  display: flex;
  justify-content: center;
  text-align: center;
}

.links-footer {
  color: white;
}
</style>

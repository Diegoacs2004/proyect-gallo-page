<template>
  <v-app>
    <HeaderSection />
    <router-view></router-view>
    <FooterSection />
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
  </v-app>
</template>
<script lang="ts" setup>
import HeaderSection from "./components/Organism/HeaderSection.vue";
import FooterSection from "./components/Organism/FooterSection.vue";
</script>

<style lang="scss">

</style>

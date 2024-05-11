<template>
  <div class="container-main">
    <v-carousel
      height="400"
      show-arrows="hover"
      cycle
      hide-delimiter-background
    >
      <v-carousel-item v-for="(slide, i) in slides" :key="i">
        <v-sheet :color="colors[i]" height="100%">
          <div class="d-flex fill-height justify-center align-center">
            <div class="text-h2">{{ slide }} Slide</div>
          </div>
        </v-sheet>
      </v-carousel-item>
    </v-carousel>
    <FooterSection />
  </div>
</template>

<script lang="ts" setup>
let colors = [
  "indigo",
  "warning",
  "pink darken-2",
  "red lighten-1",
  "deep-purple accent-4",
];
let slides = ["First", "Second", "Third", "Fourth", "Fifth"];
</script>

<style scoped>
@import "../CSS/styles.css";

.container-main {
  margin-top: 100px;
}
</style>

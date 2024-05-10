<template>
  <div class="links">
    <router-link to="/" color="info" class="link">Nosotros</router-link>
    <router-link :to="{ name: 'home' }" color="info" class="link"
      >Eventos</router-link
    >
    <router-link to="/" color="info" class="link">Resultados</router-link>
    <router-link to="/" color="info" class="link">Registrarse</router-link>
    <router-link to="/" color="info" class="link"> Mi Cuenta</router-link>
  </div>
</template>
<script lang="ts" setup></script>
<style scoped>
.link {
  margin-left: 32px;
}

.div-line {
  width: 1px;
  background-color: #ffffff;
  height: 64px;
}
</style>

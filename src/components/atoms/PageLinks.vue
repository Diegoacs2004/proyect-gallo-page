<template>
  <div class="links">
    <router-link to="/" color="info" class="link">Inicio</router-link>
    <router-link :to="{ name: 'home' }" color="info" class="link"
      >Eventos</router-link
    >
    <router-link to="/" color="info" class="link">Resultados</router-link>
    <router-link to="/register" color="info" class="link"
      >Registrarse</router-link
    >
    <router-link to="/login" color="info" class="link"
      >Iniciar Sesión</router-link
    >
    <router-link to="/" color="info" class="link"> Mi Cuenta</router-link>
  </div>
</template>
<script lang="ts" setup></script>
<style scoped>
.link {
  font-size: 16px;
  margin-left: 32px;
  color: white;
  text-decoration: none;
}
</style>

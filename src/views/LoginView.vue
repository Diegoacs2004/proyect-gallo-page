<template>
  <div class="container-main-login">
    <!--imagen -->

    <!--formulario de registro -->
    <section class="form-login">
      <form action="">
        <h4>INICIAR SESION</h4>
        <div class="form-column">
          <div class="form-group">
            <label for="nombre">Nombre/Correo:</label>
            <input
              class="controls"
              type="text"
              name="nombre"
              id="nombre"
              placeholder="Ingrese su Nombre"
            />
          </div>
          <div class="form-group">
            <label for="apellido">Contraseña:</label>
            <input
              class="controls"
              type="text"
              name="apellido"
              id="apellido"
              placeholder="Ingrese su Apellido"
            />
          </div>
        </div>
        <input class="botons" type="submit" value="INGRESAR" />
        <p><a href="#">¿Se olvidó la contraseña?</a></p>
      </form>
    </section>
    <!-- <img
      src="@/assets/gallo_logo.png"
      alt="Imagen de un gallo"
      class="image-login"
    /> -->
  </div>
</template>
<script lang="ts" setup></script>
<style scoped>
@import "../CSS/login.css";
</style>

<template>
  <div class="container-main-register">
    <!--imagen -->
    <img
      src="@/assets/gallo_logo.png"
      alt="Imagen de un gallo"
      class="image-register"
    />

    <!--formulario de registro -->
    <section class="form-register">
      <form action="">
        <h4>Formulario de Registro</h4>
        <div class="form-row">
          <div class="form-group">
            <label for="nombre">Nombre:</label>
            <input
              class="controls"
              type="text"
              name="nombre"
              id="nombre"
              placeholder="Ingrese su Nombre"
            />
          </div>
          <div class="form-group">
            <label for="apellido">Apellido:</label>
            <input
              class="controls"
              type="text"
              name="apellido"
              id="apellido"
              placeholder="Ingrese su Apellido"
            />
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="correo">Correo Electrónico:</label>
            <input
              class="controls"
              type="email"
              name="correo"
              id="correo"
              placeholder="Ingrese su Correo"
            />
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="contrasena">Contraseña:</label>
            <input
              class="controls"
              type="password"
              name="contrasena"
              id="contrasena"
              placeholder="Ingrese su Contraseña"
            />
          </div>
          <div class="form-group">
            <label for="confirmar-contrasena">Confirmar Contraseña:</label>
            <input
              class="controls"
              type="password"
              name="confirmar-contrasena"
              id="confirmar-contrasena"
              placeholder="Confirme su Contraseña"
            />
          </div>
        </div>
        <div class="form-row">
          <div class="form-group">
            <label for="telefono">Teléfono:</label>
            <input
              class="controls"
              type="text"
              name="telefono"
              id="telefono"
              placeholder="Ingrese su Teléfono"
            />
          </div>
        </div>
        <input class="botons" type="submit" value="Registrar" />
        <p><a href="#">¿Ya tengo Cuenta?</a></p>
      </form>
    </section>
  </div>
</template>
<script lang="ts" setup></script>
<style scoped>
@import "../CSS/register.css";
</style>

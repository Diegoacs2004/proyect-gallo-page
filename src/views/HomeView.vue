<template>
  <div class="container">
    <!--imagen -->
    <img src="@/assets/gallo2.jpeg" alt="Imagen de un gallo" class="image">

    <!--formulario de registro -->
    <section class="form-register">
      <h4>Formulario de Registro</h4>
      <div class="form-row">
        <div class="form-group">
          <label for="nombre">Nombre:</label>
          <input class="controls" type="text" name="nombre" id="nombre" placeholder="Ingrese su Nombre">
        </div>
        <div class="form-group">
          <label for="apellido">Apellido:</label>
          <input class="controls" type="text" name="apellido" id="apellido" placeholder="Ingrese su Apellido">
        </div>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label for="correo">Correo Electrónico:</label>
          <input class="controls" type="email" name="correo" id="correo" placeholder="Ingrese su Correo">
        </div>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label for="contrasena">Contraseña:</label>
          <input class="controls" type="password" name="contrasena" id="contrasena" placeholder="Ingrese su Contraseña">
        </div>
        <div class="form-group">
          <label for="confirmar-contrasena">Confirmar Contraseña:</label>
          <input class="controls" type="password" name="confirmar-contrasena" id="confirmar-contrasena" placeholder="Confirme su Contraseña">
        </div>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label for="telefono">Teléfono:</label>
          <input class="controls" type="text" name="telefono" id="telefono" placeholder="Ingrese su Teléfono">
        </div>
      </div>
      <input class="botons" type="submit" value="Registrar">
      <p><a href="#">¿Ya tengo Cuenta?</a></p>
    </section>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  align-items: flex-start;
}

.image {
  max-width: 40%;
  height: auto;
  margin-right: 20px;
  margin-top: 100px;
}


.form-register {
  width: 550px;
  background: white;
  padding: 30px;
  margin-right: 50px; 
  margin-left: auto; 
  margin-top: 100px;
  border-radius: 4px;
  color: black;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.form-register h4 {
  font-size: 22px;
  margin-bottom: 20px;
}

.form-row {
  display: flex;
  justify-content: space-between;
  margin-bottom: 16px;
}

.form-group {
  flex: 1;
}

.controls {
  width: 100%;
  background: white;
  padding: 10px;
  border-radius: 4px;
  border: 1px solid #ccc;
  font-size: 18px;
  color: black;
}

.form-register p {
  height: 40px;
  text-align: center;
  font-size: 18px;
  line-height: 40px;
}

.form-register a {
  color: black;
  text-decoration: none;
}

.form-register a:hover {
  text-decoration: underline;
}

.form-register .botons {
  width: 100%;
  background: #1f53c5;
  border: none;
  padding: 12px;
  color: white;
  margin: 16px 0;
  font-size: 16px;
}
</style>

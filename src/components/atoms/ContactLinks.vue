<template>
  <div class="footer-links">
    <v-row>
      <v-column>
        <div class="links">
          <a color="info" class="link">CONTACTO</a>
          <a color="info" class="link">PREGUNTAS FRECUENTES</a>
          <a color="info" class="link">TERMINOS Y CONDICIONES</a>
          <a color="info" class="link">BENEFICIOS</a>
        </div>
        <div>
          <p>
            El uso de este sitio está sujeto a las condiciones de uso de la
            empresa. Al utilizar este sitio, tú indicas que aceptas cumplir con
            estos Términos universales de servicio. ®{{
              new Date().getFullYear()
            }}
          </p>
        </div>
      </v-column>
    </v-row>
  </div>
</template>
<script lang="ts" setup></script>
<style scoped>
.link {
  margin-left: 32px;
}
</style>

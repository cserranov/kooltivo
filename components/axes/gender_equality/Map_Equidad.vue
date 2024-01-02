<template>
  <div style=" text-align: center; margin-top: 50px; bor">
    <iframe
      class="mapa-element"
      src="https://aad8012.github.io/mapa"
      width="100%"
      frameborder="0"
    ></iframe>
    <div>
      <!-- <v-btn class="rounded-btn" variant="outlined">
        <p>
          Conoce los teléfonos de ayuda de acuerdo a tu ciudad
          <br />
          ¡Descarga el directorio!
        </p>
      </v-btn> -->
    </div>
  </div>
</template>

<style scoped>
.mapa-element {
  height: 700px; /* Cambia 200px por la altura que desees */
}

@media (max-width: 1440px) {
  .mapa-element {
    height: 700px; /* Cambia 200px por la altura que desees */
  }
}
@media (max-width: 1024px) {
  .mapa-element {
    height: 500px; /* Cambia 200px por la altura que desees */
  }
}
@media (max-width: 768px) {
  .mapa-element {
    height: 300px; /* Cambia 200px por la altura que desees */
  }
}

@media (max-width: 425px) {
  .mapa-element {
    height: 200px; /* Cambia 200px por la altura que desees */
  }
}
@media (max-width: 375px) {
  .mapa-element {
    height: 200px; /* Cambia 200px por la altura que desees */
  }
}
@media (max-width: 320px) {
  .mapa-element {
    height: 170px; /* Cambia 200px por la altura que desees */
  }
}
</style>

<template>
  <div style="position: relative">
    <div class="image-container"></div>
    <div class="overlay-div">
      <img src="@/assets/img/about/text.png" alt="" style="width: 100%" />
    </div>
  </div>
</template>

<style scoped>
.image-container {
  width: 100%;
  height: 135vh;
  background-image: url(@/assets/img/about/hero_1.png);
  background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
  background-position: center; /* Centra la imagen en el contenedor */
  background-attachment: fixed; /* Agrega el efecto de parallax */
}

.overlay-div {
  position: absolute;
  width: 80%;
  bottom: 10%;
  left: 10%;
}

@media (max-width: 1440px) {
  .image-container {
    width: 100%;
    height: 90vh;
    background-image: url(@/assets/img/about/hero_1.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}

@media (max-width: 1024px) {
  .image-container {
    width: 100%;
    height: 90vh;
    background-image: url(@/assets/img/about/hero_1.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}
@media (max-width: 768px) {
  .image-container {
    width: 100%;
    height: 90vh;
    background-image: url(@/assets/img/about/hero_1.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}
@media (max-width: 425px) {
  .image-container {
    width: 100%;
    height: 45vh;
    background-image: url(@/assets/img/mobil/quienes_somos_familia.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}
@media (max-width: 375px) {
  .image-container {
    width: 100%;
    height: 40vh;
    background-image: url(@/assets/img/mobil/quienes_somos_familia.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}
@media (max-width: 320px) {
  .image-container {
    width: 100%;
    height: 35vh;
    background-image: url(@/assets/img/mobil/quienes_somos_familia.png);
    background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
    background-position: center; /* Centra la imagen en el contenedor */
    background-attachment: fixed; /* Agrega el efecto de parallax */
  }

  .overlay-div {
    position: absolute;
    width: 80%;
    bottom: 10%;
    left: 10%;
  }
}
</style>

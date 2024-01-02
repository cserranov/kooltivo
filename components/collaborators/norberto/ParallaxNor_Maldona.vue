<template>
  <div class="container">
    <div class="image-background"></div>
  </div>
</template>
<style scoped>
.container {
  width: 100%;
  height: 50vw;
}

.image-background {
  width: 100%;
  height: 100%; /* Ajusta la altura según tus preferencias */
  background-image: url("@/assets/img/parrallax/colaboradores-04.png");
  background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
  background-position: center; /* Centra la imagen en el contenedor */
  background-attachment: fixed; /* Agrega el efecto de parallax */
  border-top-left-radius: 4vw;
  border-top-right-radius: 4vw;
}

</style>

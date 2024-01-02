<template>
  <div class="container">
    <div class="image-background"></div>
  </div>
</template>
<style scoped>
.container {
  width: 100%;
  height: 50vw;
  margin-top: 5%;
}
.image-background {
  width: 100%;
  height: 100%; /* Ajusta la altura según tus preferencias */
  background-image: url("@/assets/img/adopcion/parallax.png"); /* Reemplaza con la ruta de tu imagen */
  background-size: cover; /* Ajusta el tamaño de la imagen al contenedor */
  background-position: center; /* Centra la imagen en el contenedor */
  background-attachment: fixed; /* Agrega el efecto de parallax */
}

</style>

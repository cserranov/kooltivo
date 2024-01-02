<template>
  <div style="position: relative">
    <img
      src="@/assets/img/about/about_1.png"
      alt=""
      style="width: 100%; height: 100%"
    />
    <div class="overlay-div">
      <p class="text">
        ¡Recuerda que una <span style="font-weight: bold">oportunidad</span> y
        la posibilidad de aprovecharla, puede
        <span style="color: #ffac00">cambiar tu vida</span>!
      </p>
    </div>
    <div class="overlay-div_1" id="nuestra_mision">
      <p style="font-weight: bold" class="text_1">
        Nuestra <span style="color: #0561a8">misión</span>
      </p>

      <p class="text_2">
        Usar la tecnología como cultivo para empoderar a individuos y
        comunidades a través de la educación tecnológica. Utilizando los avances
        tecnológicos como senda para brindar educación financiera, promover la
        equidad de género y generar conciencia sobre los derechos de los
        animales.
      </p>

      <p class="text_2">
        Trabajamos con la innovación tecnológica para cerrar la brecha digital,
        fomentar la inclusión y promover un mundo más justo y sostenible.
      </p>
    </div>
  </div>
</template>

<style scoped>
.overlay-div {
  position: absolute;
  top: 15%;
  left: 6%;
  width: 55%;
}
.text {
  font-size: 3.5vw;
}
.overlay-div_1 {
  position: absolute;
  bottom: 13%;
  left: 10%;
  width: 80%;
}
.text_1 {
  font-size: 4vw;
}
.text_2 {
  font-size: 2.3vw;
  text-align: justify;
}

</style>

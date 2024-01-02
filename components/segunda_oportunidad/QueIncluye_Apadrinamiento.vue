<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
          src="@/assets/img/protectorDeUnPerrito/cuidado_animal_2.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="
        position: absolute;
        top: 0%;
        right: 0%;
        width: 60%;
        height: 100%;
        overflow: hidden;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p class="title">¿Qué incluye tu donación?</p>
          </div>
        </v-col>
        <v-col cols="12">
          <div style="padding: 1% 5%">
            <ul>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Alimentación de calidad</span>: Tu apoyo garantiza que nuestros
                  perritos tengan acceso a alimentos nutritivos y sabrosos todos los días.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Cuidado médico completo</span>: Cada perrito bajo tu protección recibe
                  atención veterinaria regular, vacunas, desparasitación, y
                  tratamiento para cualquier afección médica que pueda tener.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Refugio y comodidad</span>: Les proporcionamos un refugio seguro y
                  cómodo, donde pueden jugar y descansar en
                  un entorno limpio y amoroso.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Amor y atención personalizada</span>: Nuestro equipo de cuidadores y
                  voluntarios se asegura de que cada
                  perrito se sienta amado y querido. Los pasean, juegan con ellos y les dan cariño para ayudarlos a
                  superar cualquier trauma pasado.
                </p>
              </div>


              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Preparación para la adopción</span>: Trabajamos arduamente para
                  encontrar el hogar perfecto para cada
                  perrito. Les proporcionamos entrenamiento básico y socialización para que estén listos para ser
                  adoptados.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Actualizaciones regulares</span>: Para fortalecer aún más el vínculo
                  entre tu como donante y el perrito
                  apadrinado, te enviaremos imágenes mensuales del progreso del perrito que estás apoyando. Estas
                  imágenes te permitirán ver de primera mano cómo tu generosidad está marcando la diferencia en la vida
                  de tu peludo amigo. Cada mes, recibirás fotos que muestran el estado de salud, la felicidad y la
                  evolución del perrito bajo tu protección.
                </p>
              </div>
            </ul>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 1%;
  position: relative;
  width: 100%;
}

.title {
  padding: 1% 2% 1%;
  font-size: 4vw;
  color: white;
  font-weight: bold;
}

.txt {
  color: white;
  font-size: 1.5vw;
  text-align: justify;
}

.custom-list-item {
  color: #ffac00; /* Cambia el color al que desees, por ejemplo, rojo */
  font-size: 1.5vw;
}


</style>
<script setup lang="ts">
</script>
<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
          src="@/assets/img/adopcion/unete.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="
        position: absolute;
        top: 60%;
        left: 10%;
        width: 80%;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p class="txt" style="margin-bottom: 5%">
              Nuestra comunidad de apoyadores es esencial para el éxito de este programa. Juntos,
              podemos hacer posible que más perritos tengan una segunda oportunidad en la vida y encuentren un hogar
              lleno de amor.
              Tu contribución, sin importar su tamaño, es un rayo de sol hacia la protección, cuidado y bienestar de
              estos peludos compañeros.
            </p>
            <p class="txt">
              <span style="font-weight: bold">¡Únete a nosotros y dona la cantidad que sientas en tu corazón! Cada aporte nos acerca
                más a brindarles a los perritos necesitados la atención y el cariño que merecen.</span>
            </p>
            <p class="txt">
              <span style="font-weight: bold">¡Gracias por ser parte de nuestra causa y por hacer del mundo un lugar mejor para nuestros amigos de cuatro patas!</span>
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div
        style="
        position: absolute;
        top: 25%;
        left: 10%;
        width: 80%;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p style="color: black; font-size: 2.5vw">
              <span style="font-weight: bold">Hagamos esto juntos</span>
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: -10%;
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
  font-size: 1.3vw;
  text-align: justify;
}

.custom-list-item {
  color: #ffac00; /* Cambia el color al que desees, por ejemplo, rojo */
  font-size: 1.5vw;
}


</style>
<script setup lang="ts">
</script>
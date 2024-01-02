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
              En el programa <span style="font-weight: bold">"Siembra Amor con Adopción"</span>
              creemos que cada animal merece un futuro lleno de amor y cuidado. Tu apoyo y participación son esenciales
              para hacer que esta visión
              se haga realidad. Juntos, estamos construyendo un mundo donde cada animal tenga un hogar y una esperanza.
            </p>
            <p class="txt">
              <span style="font-weight: bold">¡Únete a nosotros en esta hermosa misión!</span>
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div
        style="
        position: absolute;
        top: 35%;
        left: 10%;
        width: 80%;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p style="color: black; font-size: 2.5vw">
              <span style="font-weight: bold">Únete a esta Siembra de Amor</span>
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
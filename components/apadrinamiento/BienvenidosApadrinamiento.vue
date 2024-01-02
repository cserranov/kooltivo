<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
          src="@/assets/img/protectorDeUnPerrito/bienvenidos.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="
        position: absolute;
        top: 33%;
        left: 27%;
        width: 50%;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p class="txt">
              En Fundación Kooltivo, estamos comprometidos con el bienestar y la protección de
              nuestros amigos de cuatro patas. Con nuestro programa “Conviértete en el Protector de un Perrito”,
              labramos el campo para que
              tengas oportunidad de hacer una diferencia significativa en la vida de un perrito necesitado y cambiar su
              vida.
            </p>
            <p class="txt" style="text-align: center">
              Aquí está cómo funciona:
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div
        style="
        position: absolute;
        top: 15%;
        left: 15%;
        width: 70%;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p style="color: black; font-size: 2.1vw; text-align: center">
              <span style="font-weight: bold">¡Bienvenidos al programa “Conviértete en el Protector de un Perrito”
                <br>
                de Fundación Kooltivo!</span>
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 5%;
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
  color: black;
  font-size: 1.4vw;
  text-align: justify;
}

.custom-list-item {
  color: #ffac00; /* Cambia el color al que desees, por ejemplo, rojo */
  font-size: 1.5vw;
}


</style>
<script setup lang="ts">
</script>


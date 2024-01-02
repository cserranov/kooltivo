<template>
  <div>
    <div class="image-container">
      <img
          src="@/assets/img/equidadDeGenero/hero.png"
          alt=""
          style="width: 100%; height: 100%"
      />
      <div
          class="linea"
          style="width: 80%; height: 6%; position: absolute; top: 43%; right: 10%"
      >
        <img
            src="@/assets/img/3_botones.png"
            alt=""
            style="width: 100%; height: 100%"
        />
      </div>
      <div
          style="width: 80%; height: 6%; position: absolute; top: 43%; right: 10%"
      >
        <v-row no-gutters style="height: 100%">
          <v-col
              cols="4"
              class="text-center"
              style="display: flex; justify-content: center; align-items: center"
          >
            <v-btn
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/about')"
            >
              Quiénes somos
            </v-btn>
          </v-col>
          <v-col
              cols="4"
              class="text-center"
              style="display: flex; justify-content: center; align-items: center"
          >
            <v-btn
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/#nuestrosEjes')"
            >
              Nuestros ejes
            </v-btn>
          </v-col>
          <v-col
              cols="4"
              class="text-center"
              style="display: flex; justify-content: center; align-items: center"
              @click="navigateTo('/contactanos')"
          >
            <v-btn class="rounded-btn" variant="outlined"> Contáctanos</v-btn>
          </v-col>
        </v-row>
      </div>
      <div class="overlay-div-2">
        <p class="title-2">¿Qué Promovemos?</p>
      </div>
      <div class="overlay-div_1">
        <p class="title">
          Promovemos la equidad de género en el campo tecnológico y en la
          sociedad en general. Desarrollamos programas y actividades que
          fomentan la participación igualitaria de mujeres y jóvenes en
          disciplinas tecnológicas, así como en roles de liderazgo.
        </p>
      </div>
    </div>
    <div style="text-align: center; margin-top: 3%">
      <img class="puntos" src="@/assets/img/puntos.png" alt=""/>
    </div>
  </div>
</template>
<script>
export default {
  methods: {
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>
<style scoped>
.rounded-btn {
  border-radius: 3vw;
  padding: 1.5vw 2vw;
  font-weight: bold;
  font-size: .8vw;
  border: 1px solid white;
  color: white;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}

.image-container {
  width: 100%;
  position: relative;
}

.puntos {
  width: 10%;
}

.overlay-div_1 {
  position: absolute;
  top: 70%;
  left: 15%;
  width: 40%;
}

.title {
  font-size: 1.8vw;
  text-align: justify;
}

.overlay-div-2 {
  position: absolute;
  top: 60%;
  left: 13%;
}

.title-2 {
  font-size: 3.5vw;
  font-weight: bolder;
}


</style>

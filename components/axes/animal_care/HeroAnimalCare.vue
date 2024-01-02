<template>
  <div>
    <div class="image-container">
      <img
        src="@/assets/img/cuidado_animal/hero.png"
        alt=""
        style="width: 100%; height: 100%"
      />
      <div
        class="linea"
        style="width: 80%; height: 6%; position: absolute; top: 32%; right: 10%"
      >
        <img
          src="@/assets/img/3_botones.png"
          alt=""
          style="width: 100%; height: 100%"
        />
      </div>
      <div
        style="width: 80%; height: 6%; position: absolute; top: 32%; right: 10%"
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
            <v-btn class="rounded-btn" variant="outlined"> Contáctanos </v-btn>
          </v-col>
        </v-row>
      </div>
      <div class="overlay-div_1">
        <p class="title">
          <span class="title-hero">Cuidado Animal</span>
          <br />
          Generamos conciencia y promovemos el bienestar animal. A través de
          programas educativos y campañas de sensibilización, buscamos informar
          y educar a la comunidad sobre los derechos de los animales y el trato
          ético hacia ellos.
          <br />
          <span style="color: #0561a8"
            >Recalcamos que los animales son seres vivos que sienten.</span
          >
        </p>
      </div>
      <div class="overlay-div_2">
        <p class="title_2">¿Qué Promovemos?</p>
      </div>
      <div class="overlay-div_3">
        <p class="title_3">
          La esterilización, la adopción de forma responsable, así como él
          respeto y cuidado a los animales de compañía.
        </p>
      </div>
      <div class="overlay-div_4">
        <p class="title_4">
          ¿Con quién <span style="color: #ffac00">colaboramos</span>?
        </p>
        <p class="title_5">
          Colaboramos con las organizaciones dedicadas a la protección y el
          rescate animal, fomentando prácticas sostenibles y respetuosas con el
          entorno natural. Buscamos crear una sociedad que valore y proteja los
          derechos de los animales, impulsando su bienestar y coexistencia
          armoniosa con los seres humanos.
        </p>
      </div>
    </div>
    <div style="text-align: center; margin-top: 3%">
      <img class="puntos" src="@/assets/img/puntos.png" alt="" />
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
  border-radius: 2vw;
  padding: 1.5vw;
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
  top: 8%;
  left: 5%;
  width: 40%;
}
.title-hero {
  font-size: 3.8vw;
  font-weight: bold;
}
.title {
  font-size: 1.8vw;
  text-align: justify;
}

.overlay-div_2 {
  position: absolute;
  top: 47%;
  left: 50%;
  width: 40%;
}
.title_2 {
  font-size: 3.5vw;
  font-weight: bold;
}

.overlay-div_3 {
  position: absolute;
  top: 54%;
  left: 51%;
  width: 40%;
}
.title_3 {
  text-align: justify;
  font-size: 1.5vw;
  font-weight: bold;
}

.overlay-div_4 {
  background: rgba(0, 0, 0, 0.3);
  position: absolute;
  top: 80%;
  left: 10%;
  width: 80%;
  border-radius: 2vw;
  padding: 5%;
}
.title_4 {
  font-size: 3.5vw;
  font-weight: bold;
  color: white;
}
.title_5 {
  font-size: 1.7vw;
  text-align: justify;
  color: white;
}


</style>

<template>
  <div class="container-main">
    <div class="image-container">
      <img
        src="@/assets/img/educacionTecnologica/hero.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div
      style="width: 80%; height: 10%; position: absolute; top: 41%; right: 10%"
    >
      <img
        src="@/assets/img/3_botones.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div
      style="
        width: 80%;
        height: 10%;
        position: absolute;
        top: 41%;
        right: 10%;
        display: flex;
        justify-content: center;
        align-items: center;
      "
    >
      <v-row no-gutters class="justify-center align-center">
        <v-col cols="4" class="text-center">
          <v-btn
            class="rounded-btn"
            variant="outlined"
            @click="navigateTo('/about')"
          >
            Quiénes somos
          </v-btn>
        </v-col>
        <v-col cols="4" class="text-center">
          <v-btn
            class="rounded-btn"
            variant="outlined"
            @click="navigateTo('/#nuestosEjes')"
          >
            Nuestros ejes
          </v-btn>
        </v-col>
        <v-col cols="4" class="text-center">
          <v-btn
            class="rounded-btn"
            variant="outlined"
            @click="navigateTo('/contactanos')"
          >
            Contáctanos
          </v-btn>
        </v-col>
      </v-row>
    </div>
    <div class="container-promovemos">
      <p class="title">¿Qué Promovemos?</p>
      <div class="container-text">
        <p style="text-align: justify">
          A través de programas, cursos y certificaciones sobre saberes
          específicos del campo, kooltivo brinda capacitaciones gratuitas a
          jovenes y adultos en habilidades digitales, programación inteligencia
          artificial, robótica y otros campos de la tecnología emergente.
        </p>
      </div>
      <div class="container-puntos">
        <img class="img" src="@/assets/img/puntos.png" alt="" />
      </div>
      <div style="text-align: center">
        <v-btn
          style="margin-top: 5%"
          class="rounded-btn-1"
          variant="outlined"
          @click="navigateTo('/courses')"
        >
          Conoce nuestros cursos
        </v-btn>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    navigateTo(path) {
      this.$router.push(path);
    },
    scrollToElement(elemento) {
      // Obten el elemento con el ID "elementoDestino"
      const elementoDestino = document.getElementById(elemento);

      // Verifica si el elemento existe
      if (elementoDestino) {
        // Utiliza el método scrollIntoView para desplazarte al elemento
        elementoDestino.scrollIntoView({ behavior: "smooth" }); // Puedes ajustar el comportamiento de desplazamiento según tus preferencias
      }
    },
  },
};
</script>

<style scoped>
.container-main {
  width: 100%;
  position: relative;
}

.image-container {
  width: 100%;
  height: 100%;
}

.container-promovemos {
  width: 50%;
  position: absolute;
  top: 55%;
  right: 3%;
  text-align: end;
  padding: 1%;
}

.title {
  font-weight: bold;
  font-size: 3.5vw;
}

.container-text {
  padding: 5%;
  font-size: 2vw;
  border: solid 1px black;
  /* si va */
  border-radius: 2vw;
  background-color: white;
}

.container-puntos {
  margin-top: 2%;
}

.container-puntos img {
  width: 20%;
}

.rounded-btn {
  border-radius: 2.5vw;
  padding: 1.5vw;
  font-weight: bold;
  font-size: 1vw;
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

.rounded-btn-1 {
  border-radius: 2.5vw;
  padding: 1.5vw;
  font-weight: bold;
  font-size: 1vw;
  border: 1px solid white;
  color: white;
  background-color: #ffac00;
}

.rounded-btn-1:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn-1.v-btn--density-default {
  height: auto;
}
</style>

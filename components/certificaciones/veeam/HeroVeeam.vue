<template>
  <div class="container-main desktop">
    <div class="image-container">
      <img
          src="@/assets/img/veeam/hero.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div class="linea">
      <img
          src="@/assets/img/3_botones.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="
        width: 80%;
        height: 20%;
        position: absolute;
        bottom: 0%;
        right: 10%;
      "
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
  </div>

  <div class="container-main mobil">
    <div class="image-container">
      <img
          src="@/assets/img/veeam/hero.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div class="linea">
      <img
          src="@/assets/img/3_botones.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="width: 90%; height: 30%; position: absolute; bottom: 0%; right: 5%"
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
        >
          <v-btn class="rounded-btn" variant="outlined"> Contáctanos</v-btn>
        </v-col>
      </v-row>
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
        elementoDestino.scrollIntoView({behavior: "smooth"}); // Puedes ajustar el comportamiento de desplazamiento según tus preferencias
      }
    },
  },
};
</script>

<style scoped>
.desktop {
  display: block;
}

.mobil {
  display: none;
}

.container-main {
  width: 100%;
  height: 90vh;
  position: relative;
}

.image-container {
  width: 100%;
  height: 90%;
}

.linea {
  width: 80%;
  height: 20%;
  position: absolute;
  bottom: 0%;
  right: 10%;
}

.rounded-btn {
  border-radius: 50px;
  padding: 30px;
  font-weight: bold;
  font-size: 15px;
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

@media (max-width: 1440px) {
  .container-main {
    height: 84vh;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 5%;

    font-size: 10px;
  }
}

@media (max-width: 1024px) {
  .container-main {
    height: 60vh;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 5%;

    font-size: 10px;
  }
}

@media (max-width: 768px) {
  .container-main {
    height: 45vh;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 5%;

    font-size: 10px;
  }
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 33vh;
  }

  .image-container {
    width: 100%;
    height: 80%;
  }

  .linea {
    width: 90%;
    height: 30%;
    position: absolute;
    bottom: 0%;
    right: 5%;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 6%;
    font-size: 8px;
  }
}

@media (max-width: 375px) {
  .container-main {
    height: 30vh;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 6%;
    font-size: 7px;
  }
}

@media (max-width: 320px) {
  .container-main {
    height: 23vh;
  }

  .rounded-btn {
    border-radius: 20px;
    padding: 6%;
    font-size: 6px;
  }
}
</style>

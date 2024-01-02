<template>
  <div class="container-main">

    <img
        src="@/assets/img/adopcion/hero.png"
        alt=""
        style="width: 100%;"
        class="desktop"
    />
    <img
        src="@/assets/img/adopcion/hero.png"
        alt=""
        style="width: 100%;"
        class="movil"
    />
    <div style="position: absolute; bottom: -10%; width: 80%; left: 10%">
      <div style="position: relative">
        <img
            src="@/assets/img/3_botones.png"
            alt=""
            style="width: 100%;"
        />
        <div style="position: absolute; top: 0%;width: 100%;height: 100%"
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

.movil {
  display: none;
}

.container-main {
  width: 100%;
  position: relative;
}

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

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }
  .rounded-btn {
    border-radius: 2vw;
    padding: 1.5vw;
    font-weight: bold;
    font-size: 1.2vw;
    border: 1px solid white;
    color: white;
  }
}

</style>




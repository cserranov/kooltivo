<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="6" style="
                  padding: 5% 0% 0%;
                  display: flex;
                  justify-content: center;
                  align-items: center;
                ">
        <div style="text-align: center">
          <img src="@/assets/img/elementos_automation/AA_Movil/chica.png" style="width: 100%" />
        </div>
      </v-col>
      <v-col cols="6" style="padding: 5%">
        <p style="font-size: 2.3vw; font-weight: bold; margin-bottom: 5%">
          Descripción:
        </p>
        <p style="font-size: 1.5vw; margin-bottom: 5%">
          La automatización de procesos robóticos(RPA) es el futuro de la
          eficiencia operativa en el mundo empresarial. Si deseas aprender a
          identificar y automatizar procesos repetitivos, ¡Te damos la
          bienvenida al Curso de Automation Anywhere!
        </p>
        <p style="font-size: 1.5vw; margin-bottom: 5%">
          Este curso te proporcionará las habilidades necesarias para dominar
          esta herramienta y aprovechar su potencial en el ámbito bancario, para
          optimizar las operaciones en el sector financiero y administrativo y
          más allá.
        </p>
        <p style="font-size: 1.5vw">
          <span style="font-size: 2.3vw; font-weight: bold">Plataforma: </span>Todos los cursos se llevarán a cabo de
          manera virtual a través del
          portal de Automation Anywhere.
        </p>
        <div style="text-align: center; margin-top: 10%" class="btn-route">
          <img src="@/assets/img/btn-registro.png" alt="" style="width: 35%" @click="registro()" />
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 4vw; font-weight: bold">Descripción:</p>
        <p style="font-size: 2.8vw; text-align: justify; margin-bottom: 5%">
          La automatización de procesos robóticos(RPA) es el futuro de la
          eficiencia operativa en el mundo empresarial. Si deseas aprender a
          identificar y automatizar procesos repetitivos, ¡Te damos la
          bienvenida al Curso de Automation Anywhere!
        </p>
        <p style="font-size: 2.8vw; text-align: justify">
          Este curso te proporcionará las habilidades necesarias para dominar
          esta herramienta y aprovechar su potencial en el ámbito bancario, para
          optimizar las operaciones en el sector financiero y administrativo y
          más allá.
        </p>
      </v-col>
      <v-col cols="12" style="
                  padding: 2%;

                  display: flex;
                  justify-content: center;
                  align-items: center;
                  text-align: center;
                ">
        <div>
          <img src="@/assets/img/elementos_automation/AA_Movil/chica.png" style="width: 50%" />
        </div>
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 4vw; font-weight: bold">Plataforma:</p>
        <p style="font-size: 2.8vw; text-align: justify">
          Todos los cursos se llevarán a cabo de manera virtual a través del
          portal de Automation Anywhere.
        </p>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  methods: {
    registro() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
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
.desktop {
  display: block;
}

.movil {
  display: none;
}

.container-main {
  width: 100%;
  background-color: gainsboro;
  border-radius: 3vw;
  padding: 0% 5%;
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }

  .container-main {
    width: 100%;
    background-color: white;
    border-radius: 0vw;
  }
}
</style>

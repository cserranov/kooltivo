<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="7" style="padding: 5%">
        <p style="font-size: 3vw; font-weight: bold">
          Procesos de Automatización
        </p>
        <p style="margin-top: 6%; font-size: 1.7vw; font-weight: bold">
          Módulos ofrecidos:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            Getting Started with Robotic Process Automation(RPA)
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            Building Resilient Bots Using Automations 360
          </li>
        </ul>

        <p style="margin-top: 6%; font-size: 1.7vw">
          <span style="font-weight: bold">Fecha de inicio: </span>23 de octubre
          2023
        </p>
        <p style="margin-top: 6%; font-size: 1.7vw">
          <span style="font-weight: bold">Duración: </span>6 semanas(2 semanas
          para tomar los cursos online en formato on-demand*; 1 semana de
          entrenamiento en formato híbrido; una sesión práctica presencial y 3
          semanas para completar proyecto individual de beneficio comunitario)
        </p>
        <div style="text-align: center; margin-top: 5%" class="btn-route">
          <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
        </div>
        <div style="margin-top: 6%; text-align: center">
          <img src="@/assets/img/puntos.png" style="width: 18%" />
        </div>
      </v-col>

      <v-col cols="5" style="
                padding: 5%;
                display: flex;
                justify-content: center;
                align-items: center;
              ">
        <img src="@/assets/img/elementos_automation/mano.png" style="width: 100%" />
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="
                padding: 5%;
                display: flex;
                justify-content: center;
                align-items: center;
              ">
        <img src="@/assets/img/elementos_automation/mano.png" style="width: 50%" />
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 3.5vw; font-weight: bold">
          Procesos de Automatización
        </p>
        <p style="margin-top: 6%; font-size: 2.5vw; font-weight: bold">
          Módulos ofrecidos:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 2vw; margin-bottom: 3%">
            Getting Started with Robotic Process Automation(RPA)
          </li>
          <li style="font-size: 2vw; margin-bottom: 3%">
            Building Resilient Bots Using Automations 360
          </li>
        </ul>

        <p style="margin-top: 6%; font-size: 2.5vw">
          <span style="font-weight: bold">Fecha de inicio: </span>23 de octubre
          2023
        </p>
        <p style="margin-top: 6%; font-size: 2.5vw">
          <span style="font-weight: bold">Duración: </span>6 semanas(2 semanas
          para tomar los cursos online en formato on-demand*; 1 semana de
          entrenamiento en formato híbrido; una sesion práctica presencial y 3
          semanas para completar proyecto individual de beneficio comunitario)
        </p>
        <div style="margin-top: 6%; text-align: center">
          <img src="@/assets/img/puntos.png" style="width: 18%" />
        </div>
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
  margin-top: 5%;
  padding: 0% 6%;
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }
}
</style>

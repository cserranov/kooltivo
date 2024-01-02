<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="6" style="padding: 6%">
        <p style="font-size: 2vw; font-weight: bold">Requisitos:</p>
        <ul style="margin-top: 4%; margin-bottom: 5%">
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Nivel de inglés:</span>
            <p>Intermedio o avanzado.</p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold"> Perfil Ideal:</span>
            <p>
              Preferiblemente, estudiantes en los últimos semestres o egresados
              de ingeniería, informática, contabilidad y administración; así
              como profesionales que ya trabajan en el área tecnológica.
            </p>
          </li>
        </ul>
        <p style="font-size: 2vw; font-weight: bold">
          Sesión Práctica para tu Proyecto Específico:
        </p>

        <p style="font-size: 1.3vw; margin-top: 4%; margin-bottom: 5%">
          Este curso no solo te proporcionará conocimientos teóricos, sino que
          también te ofrecerá una sesión práctica para aplicar lo que aprendas
          en tu proyecto espécifico. La experiencia práctica es esencial para la
          comprensión profunda de la automatización.
        </p>

        <p style="font-size: 2vw; font-weight: bold">
          Beneficios de la Automatización con Automation Anywhere
        </p>

        <p style="font-size: 1.3vw; margin-top: 4%">
          La tecnología RPA dentro de una máquina de cómputo te permitirá
          realizar tareas rutinarias en las empresas de manera más rápida y sin
          errores. Esto significa una mayor eficiencia y precisión en tus
          operaciones diarias.
        </p>
      </v-col>
      <v-col cols="6">
        <div style="margin-top: 5%; text-align: center">
          <img src="@/assets/img/elementos_automation/AA_Movil/chico.png" style="width: 70%" />
          <div style="text-align: center; margin-top: 5%" class="btn-route">
            <img src="@/assets/img/btn-registro.png" alt="" style="width: 35%" @click="registro()" />
          </div>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 5% 10%">
        <div style="margin-top: 10%; text-align: center">
          <img src="@/assets/img/elementos_automation/AA_Movil/chico.png" style="width: 50%" />
        </div>
      </v-col>
      <v-col cols="12" style="padding: 5% 10%; text-align: center">
        <p style="font-size: 4vw; font-weight: bold">Requisitos:</p>
        <ul style="margin-top: 4%">
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Nivel de inglés:</span>
            <p>Intermedio o avanzado.</p>
          </li>
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Perfil Ideal:</span>
            <p style="text-align: justify">
              Preferiblemente, estudiantes en los últimos semestres o egresados
              de ingeniería, informática, contabilidad y administración; así
              como profesionales que ya trabajan en el área tecnológica.
            </p>
          </li>
        </ul>

        <p style="font-size: 4vw; font-weight: bold; margin-top: 5%">
          Sesión Práctica para tu Proyecto Específico:
        </p>

        <p style="font-size: 3vw; text-align: justify">
          Este curso no solo te proporcionará conocimientos teóricos, sino que
          también te ofrecerá una sesión práctica para aplicar lo que aprendas
          en tu proyecto espécifico. La experiencia práctica es esencial para la
          comprensión profunda de la automatización.
        </p>

        <p style="font-size: 4vw; font-weight: bold; margin-top: 5%">
          Beneficios de la Automatización con Automation Anywhere
        </p>

        <p style="font-size: 3vw; text-align: justify">
          La tecnología RPA dentro de una máquina de cómputo te permitirá
          realizar tareas rutinarias en las empresas de manera más rápida y sin
          errores. Esto significa una mayor eficiencia y precisión en tus
          operaciones diarias.
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
  margin-top: 5%;
  padding: 0% 5%;
}

ul {
  list-style-type: none;
  /* Elimina los marcadores de la lista */
  padding-left: 1.2em;
  /* Espacio para simular el punto (o cualquier otro marcador) */
}

ul li::before {
  content: "\2022";
  /* Código del carácter del marcador de lista (punto) */
  color: #ffac00;
  /* Color del marcador (amarillo en este caso) */
  display: inline-block;
  width: 1.5vw;
  /* Ajusta el ancho según sea necesario */
  margin-left: -1.2em;
  /* Alinea el marcador con el texto y ajusta según el padding-left */
}

ul li {
  color: black;
  /* Color del texto (negro en este caso) */
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

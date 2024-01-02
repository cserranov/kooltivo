<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="6" style="padding: 5%">
        <p style="font-size: 3vw; font-weight: bold">Requisitos:</p>
        <p style="margin-top: 6%; font-size: 1.7vw">
          Personas con conocimiento de programación, tecnología, sistemas, o
          experiencia en la industria.
        </p>
        <div style="margin-top: 10%; text-align: center">
          <img src="@/assets/img/microfocus/cuadro_azul.png" style="width: 45%" />
        </div>
      </v-col>
      <v-col cols="6" style="padding: 5%">
        <ul style="margin-top: 4%">
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Nivel de inglés:</span>
            <p>Intermedio (entendimiento y habla fluida).</p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Herramientas de Productividad:</span>
            <p>
              Experiencia en el uso de herramientas de productividad como Excel.
            </p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Ingenierías Afines a Tecnología:</span>
            <p>
              Estudiantes o graduados de ingeniería relacionadas con la
              tecnología.
            </p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Perfilados en Áreas de Sistemas:</span>
            <p>
              Profesionales en áreas relacionadas con sistemas y tecnología.
            </p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Argot Tecnológico:</span>
            <p>
              Conocimiento del argot tecnológico y la capacidad de comprender y
              comunicarse eficazmente en términos técnicos.
            </p>
          </li>
        </ul>
        <div style="text-align: center; margin-top: 10%" class="btn-route">
          <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 4vw; font-weight: bold">Requisitos:</p>
        <p style="margin-top: 6%; font-size: 3.5vw">
          Personas con conocimiento de programación, tecnología, sistemas, o
          experiencia en la industria.
        </p>
        <div style="margin-top: 10%; text-align: center">
          <img src="@/assets/img/microfocus/cuadro_azul.png" style="width: 50%" />
        </div>
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <ul style="margin-top: 4%">
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Nivel de inglés:</span>
            <p>Intermedio (entendimiento y habla fluida).</p>
          </li>
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Herramientas de Productividad:</span>
            <p>
              Experiencia en el uso de herramientas de productividad como Excel.
            </p>
          </li>
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Ingenierías Afines a Tecnología:</span>
            <p>
              Estudiantes o graduados de ingeniería relacionadas con la
              tecnología.
            </p>
          </li>
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Perfilados en Áreas de Sistemas:</span>
            <p>
              Profesionales en áreas relacionadas con sistemas y tecnología.
            </p>
          </li>
          <li style="font-size: 3vw; margin-bottom: 3%">
            <span style="font-weight: bold">Argot Tecnológico:</span>
            <p>
              Conocimiento del argot tecnológico y la capacidad de comprender y
              comunicarse eficazmente en términos técnicos.
            </p>
          </li>
        </ul>
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

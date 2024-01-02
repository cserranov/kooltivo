<template>
  <div class="container-main">
    <div class="image-container">
      <img
          src="@/assets/img/educacionTecnologica/banner.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div class="container-promovemos">
      <v-row no-gutters style="width: 100%; height: 100%">
        <v-col cols="6" style="width: 100%; height: 100%">
          <div
              class="container-text"
              style="
              width: 100%;
              height: 100%;
              display: flex;
              justify-content: center;
              align-items: center;
            "
          >
            <p style="text-align: justify">
              Nos enfocamos en resolver las necesidades de conocimiento y
              capacitación especificó que atraviesa cada uno de ustedes. Puede

              ser desde hardware, software, automatización, hasta almacenamiento

              y gestión en la nube, ya sea pública, privada o híbrida.
            </p>
          </div>
        </v-col>
        <v-col cols="6" style="width: 100%; height: 100%">
          <div
              class="justify-center container-nuestro"
              style="
              width: 100%;
              height: 100%;
              display: flex;
              justify-content: center;
              align-items: center;
            "
          >
            <p class="title">
              Nuestro <span style="color: #613683">Enfoque</span>
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="container-solucion">
      <p class="title-solucion">
        Nuestra <span style="color: #613683">Solución</span>
      </p>
      <p class="text-solucion">
        Se adoptan a tus necesidades particulares mediante el análisis que
        realizamos para brindar el perfilamiento adecuado para una nueva vida con
        un desarrollo laboral.
      </p>
    </div>
    <div class="container-solucion-2">
      <p class="text-solucion-2">
        Buscamos con ello cerrar la brecha digital y capacitarte en habilidades
        relevantes para el mundo actual y futuro. Al acercarte estas
        herramientas y empoderarte, preparamos un suelo fértil, donde puedes
        prepararte y crecer hacia un futuro con mayores oportunidades
        profesionales.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
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
.container-main {
  margin-top: 8%;
  width: 100%;
  position: relative;
}

.image-container {
  width: 100%;
  height: 100%;
}

.container-promovemos {
  width: 90%;
  position: absolute;
  top: 1%;
  right: 5%;
  text-align: center;
  padding: 1%;
  height: 25%;
}

.container-nuestro {
  padding: 10%;
}

.title {
  font-weight: bold;
  font-size: 3.3vw;
}

.container-text {
  padding: 5%;
  font-size: 2vw;
}

.container-solucion {
  width: 35%;
  position: absolute;
  top: 53%;
  left: 10%;
  text-align: start;
  padding: 1%;
}

.title-solucion {
  font-weight: bold;
  font-size: 3vw;
}

.text-solucion {
  font-size: 1.8vw;
  text-align: justify;
}

.container-solucion-2 {
  width: 35%;
  position: absolute;
  top: 50%;
  right: 5%;
  text-align: start;
  padding: 1%;
}

.text-solucion-2 {
  font-size: 1.7vw;
  text-align: justify;
}


</style>

<template>
  <div class="container-main">
    <div class="container">
      <v-row no-gutters>
        <v-col cols="12">
          <div class="container-gray">
            <p class="text" style="margin-bottom: 4vw">
              La organización se origina bajo el principio de que cada hombre o
              mujer, sin importar su origen o situación socioeconómica, merece
              tener las mismas oportunidades para crecer, alcanzar sus metas y
              florecer. Con este propósito, la fundación
              <span style="font-weight: bolder"
              >KO<span style="color: #0561a8">O</span>LTIVO</span
              >
              germinó una misión para impulsar el desarrollo integral de las
              personas en diversas áreas de interés.
            </p>

            <p class="text" style="margin-bottom: 4vw">
              La educación tecnológica se convirtió en el tallo fundamental de
              la organización. A él se agregó: educación financiera, equidad de
              género y compromiso con el bienestar animal. Cada una de ellas
              arraigada a una parte importante en la vida de Norberto.
            </p>

            <p class="text" style="margin-bottom: 4vw">
              Los testimonios de éxito y los frutos obtenidos por aquellos que
              han sido beneficiados por la fundación han reafirmado la importancia
              y relevancia de su labor. Han surgido emprendedores, innovadores y
              agentes de cambio que, gracias a las herramientas y oportunidades
              proporcionadas por
              <span style="font-weight: bolder"
              >KO<span style="color: #0561a8">O</span>LTIVO</span
              >, han logrado alcanzar sus sueños y contribuir al desarrollo de
              sus comunidades.
            </p>

            <p class="text" style="margin-bottom: 4vw">
              En la actualidad, la fundación
              <span style="font-weight: bolder"
              >KO<span style="color: #0561a8">O</span>LTIVO</span
              >
              ha madurado y continúa su compromiso inquebrantable de utilizar la
              tecnología como un medio poderoso para impulsar la igualdad de
              oportunidades. A través de su labor inalcanzable, sigue preparando
              el terreno, abriendo camino y sentando un futuro más inclusivo y
              equitativo para todas las personas.
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="overlay-div"></div>
  </div>
</template>

<style scoped>
.overlay-div {
  position: absolute;
  bottom: 33%;
  left: 0%;
  background-color: rgba(128, 128, 128, 0.5); /* Fondo semitransparente */
  width: 100%;
  height: 15vw;
}

.container-main {
  padding: 0px 10vw 0px;
  position: relative;
}

.container {
  padding: 2vw;
  background-color: gainsboro;
  border-bottom-left-radius: 2vw;
  border-bottom-right-radius: 2vw;
}

.container-gray {
  padding: 2vw 8vw;
}

.text {
  font-size: 1.8vw;
  text-align: justify;
}

</style>

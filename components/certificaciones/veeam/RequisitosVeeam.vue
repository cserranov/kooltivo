<template>
  <div class="container-main">
    <v-row no-gutters>
      <v-col cols="12">
        <div style="text-align: center; padding: 0% 0% 5%">
          <p class="title">REQUISITOS</p>
        </div>
      </v-col>
      <v-col cols="12">
        <v-row>
          <v-col sm="4" cols="6" class="container-cuadro-colores">
            <div style="border: solid #318ae0 1px; padding: 20% 10% 5%" class="txt-container container-requisitos">
              Para tener éxito en nuestros cursos, es fundamental que tengas un
              interés por aprender a garantizar que los datos estén seguros y
              disponibles en todo momento. Si te entusiasma la idea de
              respaldar, recuperar y asegurar la integridad de la información
              crítica, ¡estás en el lugar adecuado!
            </div>
            <div class="title-container cuadro1">
              Interés por la
              <br />
              Protección de Datos
            </div>
          </v-col>
          <v-col sm="4" cols="6" class="container-cuadro-colores">
            <div style="border: solid #ffac00 1px; padding: 20% 10% 5%" class="txt-container container-requisitos">
              Debido a que nuestros cursos se ofrecen en linea, necesitarás una
              conexión a Internet estable y un dispositivo (computadora, tableta
              o smartphone) que te permita acceder al contenido del curso y
              participar en las actividades en linea. La flexibilidad de
              aprender desde cualquier lugar está a tu alcance.
            </div>
            <div class="title-container cuadro2">
              Conexión a Internet
              <br />
              y Dispositivo
            </div>
          </v-col>
          <v-col sm="4" cols="6" class="container-cuadro-colores">
            <div style="border: solid #318ae0 1px; padding: 20% 10% 5%" class="txt-container container-requisitos">
              Si tienes conocimientos básicos sobre virtualización, esto te
              proporcionará una base sólida para comprender mejor los conceptos
              relacionados con la protección de datos y la virtualización que se
              abordarán en el curso.
            </div>
            <div class="title-container cuadro3">
              Conocimiento Básico
              <br />
              sobre Virtualización
            </div>
          </v-col>

          <v-col sm="4" cols="6" class="container-cuadro-colores">
            <div style="border: solid #318ae0 1px; padding: 20% 10% 5%" class="txt-container container-requisitos">
              Para aprovechar al máximo el contenido de los cursos, es
              recomendable tener un nivel de inglés intermedio, ya que parte del
              material y la documentación están en este idioma.
            </div>
            <div class="title-container cuadro4">
              Nivel de Inglés
              <br />
              Intermedio
            </div>
          </v-col>
          <v-col sm="8" cols="12" class="container-cuadro-colores">
            <div style="border: solid #ffac00 1px; padding: 10% 10% 5%" class="txt-container container-requisitos">
              Se recomienda que quienes quieran tomar estos cursos hayan cursado
              o estén cursando materias en ingeniería informática, sistemas,
              virtualización y tecnologías afines, así como para cualquier
              persona interesada en la tecnología de respaldo de información y
              la gestión de datos críticos, sin importar la edad. Valoramos la
              diversidad de experiencias y antecedentes.
            </div>
            <div class="title-container cuadro5">
              Orientado a alumnos de Ingeniería, Tecnología,
              <br />
              Sistemas, Virtualización o afines (sin límite de edad)
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
    <div style="text-align: center; margin-top: 5%" class="btn-route">
      <img src="@/assets/img/btn-registro.png" alt="" style="width: 15%" @click="registro()" />
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    registro() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
  }
}
</script>

<style scoped>
.btn-route:hover {
  transform: scale(1.1);
}

.container-requisitos {
  border-radius: 20px;
  text-align: justify;
  height: 100%;
}

.container-main {
  padding: 5% 7%;
  width: 100%;
  height: 150vh;
}

.title {
  font-size: 40px;
  font-weight: bold;
  margin-bottom: 3%;
}

.title-container {
  font-size: 30px;
}

.txt-container {
  font-size: 27px;
}

.container-cuadro-colores {
  padding: 1%;
  text-align: justify;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}

.cuadro1 {
  position: absolute;
  top: 0%;
  background-color: white;
  text-align: center;
  font-weight: bold;
}

.cuadro2 {
  position: absolute;
  top: 0%;

  background-color: white;
  text-align: center;
  font-weight: bold;
}

.cuadro3 {
  position: absolute;
  top: 0%;

  background-color: white;

  text-align: center;
  font-weight: bold;
}

.cuadro4 {
  position: absolute;
  top: 0%;

  background-color: white;

  text-align: center;
  font-weight: bold;
}

.cuadro5 {
  position: absolute;
  top: 0%;

  background-color: white;
  text-align: center;
  font-weight: bold;
}

@media (max-width: 1440px) {
  .container-main {
    padding: 5% 7%;
    height: 120vh;
  }

  .title {
    font-size: 35px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 23px;
  }

  .txt-container {
    font-size: 19px;
  }
}

@media (max-width: 1024px) {
  .container-main {
    padding: 5% 7%;
    height: 100vh;
  }

  .title {
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 16px;
  }

  .txt-container {
    font-size: 15px;
  }
}

@media (max-width: 768px) {
  .container-main {
    padding: 5% 7%;
    height: 80vh;
  }

  .title {
    font-size: 25px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 12px;
  }

  .txt-container {
    font-size: 11px;
  }
}

@media (max-width: 599px) {
  .cuadro1 {
    position: absolute;
    top: 0%;

    background-color: white;
    text-align: center;
    font-weight: bold;
  }

  .cuadro2 {
    position: absolute;
    top: 0%;

    background-color: white;
    text-align: center;
    font-weight: bold;
  }

  .cuadro3 {
    position: absolute;
    top: 0%;

    background-color: white;

    text-align: center;
    font-weight: bold;
  }

  .cuadro4 {
    position: absolute;
    top: 0%;

    background-color: white;

    text-align: center;
    font-weight: bold;
  }

  .cuadro5 {
    position: absolute;
    top: 0%;

    background-color: white;
    text-align: center;
    font-weight: bold;
  }
}

@media (max-width: 430px) {
  .container-requisitos {
    border-radius: 10px;
    text-align: justify;
    height: 100%;
  }

  .container-main {
    padding: 5% 5%;
    height: 65vh;
  }

  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 10px;
  }

  .txt-container {
    font-size: 9px;
  }
}

@media (max-width: 425px) {
  .container-requisitos {
    border-radius: 10px;
    padding: 20% 10% 5%;
    text-align: justify;
    height: 100%;
  }

  .container-main {
    padding: 5% 3%;
    height: 65vh;
  }

  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 10px;
  }

  .txt-container {
    font-size: 9px;
  }
}

@media (max-width: 375px) {
  .container-main {
    padding: 5%;
    height: 70vh;
  }

  .title {
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 10px;
  }

  .txt-container {
    font-size: 9px;
  }
}

@media (max-width: 360px) {
  .container-main {
    padding: 5%;
    height: 75vh;
  }

  .title {
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 10px;
  }

  .txt-container {
    font-size: 9px;
  }
}

@media (max-width: 320px) {
  .container-main {
    padding: 5%;
    height: 60vh;
  }

  .title {
    font-size: 15px;
    font-weight: bold;
    margin-bottom: 3%;
  }

  .title-container {
    font-size: 9px;
  }

  .txt-container {
    font-size: 8px;
  }
}
</style>


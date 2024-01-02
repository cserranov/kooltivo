<template>
  <div class="container-main" style="padding: 0% 5%">
    <v-row no-gutters>
      <v-col cols="6">
        <div style="padding: 5% 10%">
          <p class="title-1">Requisitos:</p>
          <p class="text-1">
            Personas con conocimientos de programación, tecnología, sistemas, o
            experiencia en la industria.
          </p>
        </div>
        <div style="padding: 0% 5%">
          <img src="@/assets/img/elementos_microsoft/requisitos.png" alt="" style="max-width: 100%" />
        </div>
      </v-col>
      <v-col cols="6" style="
              padding: 1% 3%;
              display: flex;
              justify-content: start;
              align-items: center;
            ">
        <ul style="list-style: none">
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Nivel de inglés:</span>
            <p class="text">Intermedio (entendimiento y habla fluida).</p>
          </li>
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Herramientas de Productividad:</span>
            <p class="text">
              Experiencia en el uso de herramientas de productividad como Excel.
            </p>
          </li>
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Conocimiento de programación:</span>
            <p class="text">
              Familiaridad con al menos un lenguaje de programación.
            </p>
          </li>
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Ingenierías Afines a tecnología:</span>
            <p class="text">
              Estudiantes o graduados de ingenierías relacionadas con la
              tecnología
            </p>
          </li>
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Perfilados en Áreas de Sistemas:</span>
            <p class="text">
              Profesionales en áreas relacionadas con sistemas y tecnología.
            </p>
          </li>
          <li style="margin-bottom: 5%">
            <span style="font-weight: bold" class="title">Argot Tecnológico:</span>
            <p class="text">
              Conocimiento del argot tecnológico y la capacidad de comprender y
              comunicarse eficazmente en términos técnicos.
            </p>
            <div style="text-align: center; margin-top: 10%" class="btn-route">
              <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
            </div>
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
  }
}
</script>

<style scoped>
ul {
  list-style: none;
  /* Quitar el estilo de lista predeterminado (punto) */
}

.title-1 {
  font-size: 35px;
  font-weight: bold;
  margin-bottom: 2%;
}

.text-1 {
  font-size: 31px;
}

.title {
  font-size: 25px;
}

.text {
  font-size: 25px;
}

.container-main {
  margin-top: 5%;
}

@media (max-width: 1440px) {
  .title-1 {
    font-size: 35px;
    font-weight: bold;
    margin-bottom: 2%;
  }

  .text-1 {
    font-size: 31px;
  }

  .title {
    font-size: 25px;
  }

  .text {
    font-size: 23px;
  }

  .container-main {
    margin-top: 5%;
  }
}

@media (max-width: 1024px) {
  .title-1 {
    font-size: 33px;
  }

  .text-1 {
    font-size: 28px;
  }

  .title {
    font-size: 20px;
  }

  .text {
    font-size: 18px;
  }

  .container-main {
    margin-top: 5%;
  }
}

@media (max-width: 768px) {
  .title-1 {
    font-size: 30px;
  }

  .text-1 {
    font-size: 25px;
  }

  .title {
    font-size: 18px;
  }

  .text {
    font-size: 13px;
  }

  .container-main {
    margin-top: 5%;
  }
}

@media (max-width: 425px) {
  .title-1 {
    font-size: 18px;
  }

  .text-1 {
    font-size: 13px;
  }

  .title {
    font-size: 10px;
  }

  .text {
    font-size: 7px;
  }

  .container-main {
    margin-top: 5%;
  }
}

@media (max-width: 375px) {
  .title-1 {
    font-size: 15px;
  }

  .text-1 {
    font-size: 10px;
  }

  .title {
    font-size: 9px;
  }

  .text {
    font-size: 6px;
  }

  .container-main {
    margin-top: 5%;
  }
}

@media (max-width: 320px) {
  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 85%;
  }

  .title {
    font-size: 12px;
    font-weight: bold;
  }

  .title-modulo {
    font-size: 10px;
    font-weight: bold;
  }

  .list {
    font-size: 8px;
  }

  .logos {
    width: 100%;
  }
}
</style>

<template>
  <div class="container-main">
    <v-row no-gutters>
      <v-col cols="7" style="display: flex; justify-content: center; align-items: center; text-align: center; ">
        <div class="container-text">
          <p class="title">
            Herramientas de Microsoft
            (Word, Excel y PowerPoint)
          </p>

          <p class="title-modulo">Módulos ofrecidos:</p>

          <p style="text-align: start;">
          <ul style="padding-left: 5%;  list-style-type: none; " class="list">
            <li>Word básico</li>
            <li>Word intermedio</li>
            <li>Word avanzado</li>
            <li>Power Point básico</li>
            <li>Power Point intermedio</li>
            <li>Power Point avanzado</li>
            <li>Excel básico</li>
            <li>Excel intermedio</li>
            <li>Excel avanzado</li>
          </ul>
          </p>

        </div>
      </v-col>
      <v-col cols="5" style="text-align: start; display: flex; justify-content: center; align-items: center;">

        <img src="@/assets/img/elementos_microsoft/excel_word.png" alt="" class="logos" />
      </v-col>
    </v-row>
    <div style="text-align: center;">
      <div style="text-align: center; margin-top: 5%" class="btn-route">
        <img src="@/assets/img/btn-registro.png" alt="" style="width: 15%" @click="registro()" />
      </div>
      <img src="@/assets/img/puntos.png" alt="" style="width: 10%; margin-top: 5%;">
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
.container-main {
  margin-top: 2%;
  padding: 0% 5%;
}

.container-text {
  width: 50%;
}

.title {
  font-size: 40px;
  font-weight: bold;
  margin-bottom: 5%
}

.title-modulo {
  text-align: start;
  font-size: 30px;
  font-weight: bold;
  margin-bottom: 5%
}

.list {
  font-size: 28px;
}

.logos {
  width: 80%
}

@media (max-width: 1440px) {
  .container-main {
    margin-top: 5%;
  }

  .title {
    font-size: 30px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 25px;
    font-weight: bold;
  }

  .list {
    font-size: 20px;
  }

  .logos {
    width: 100%
  }
}

@media (max-width: 1024px) {
  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 70%;
  }

  .title {
    font-size: 25px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 25px;
    font-weight: bold;
  }

  .list {
    font-size: 20px;
  }
}

@media (max-width: 768px) {

  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 70%;
  }

  .title {
    font-size: 23px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 20px;
    font-weight: bold;
  }

  .list {
    font-size: 15px;
  }

  .logos {
    width: 100%
  }
}

@media (max-width: 425px) {

  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 80%;
  }

  .title {
    font-size: 14px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 10px;
    font-weight: bold;
  }

  .list {
    font-size: 8px;
  }

  .logos {
    width: 100%
  }
}

@media (max-width: 375px) {

  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 85%;
  }

  .title {
    font-size: 12px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 10px;
    font-weight: bold;
  }

  .list {
    font-size: 8px;
  }

  .logos {
    width: 100%
  }
}

@media (max-width: 375px) {

  .container-main {
    margin-top: 5%;
  }

  .container-text {
    width: 85%;
  }

  .title {
    font-size: 12px;
    font-weight: bold
  }

  .title-modulo {
    font-size: 10px;
    font-weight: bold;
  }

  .list {
    font-size: 8px;
  }

  .logos {
    width: 100%
  }
}
</style>

<template>
  <v-container class="about">
    <v-row no-gutters class="justify-center align-center align-self-start">
      <v-col cols="6">
        <img
          class="imag-media"
          src="../assets/img/Pagkooltivo2-13.png"
          alt=""
        />
      </v-col>

      <v-col cols="6" class="container-text align-self-start">
        <div><h2 class="title">¿Quienes Somos?</h2></div>

        <div>
          <p class="text1">
            Somos un grupo de personas que creemos y promovemos el desarrollo de
            habilidades digitales para avivar la igualdad de oportunidades y el
            progreso social.
          </p>

          <p class="text2">
            Juntos, conformamos una fundación empresarial y sin fines de lucro
            que obra en favor de la equidad de género y la conciencia sobre los
            derechos de los animales.
          </p>

          <div style="text-align: center">
            <v-btn class="rounded-btn" variant="outlined"> SABER MÁS </v-btn>
          </div>

          <div style="text-align: center">
            <img src="../assets/img/puntos.png" alt="" class="points" />
          </div>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.container-text {
  padding-left: 90px !important;
}
.imag-media {
  width: 100%;
}
.title {
  text-align: start;
  font-size: 50px;
}

.text1 {
  font-size: 30px;
  text-align: justify;
}

.text2 {
  font-size: 30px;
  text-align: justify;
}

.rounded-btn {
  border-radius: 50px;
  padding: 30px;
  margin-top: 15%;
  font-weight: bold;
  font-size: 20px;
  border: 1px solid black;
  color: black;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
  color: white;
}
.rounded-btn.v-btn--density-default {
  height: auto;
}
@media (max-width: 2561px) {
  .title {
    font-size: 70px;
    margin-bottom: 30px;
  }

  .text1 {
    font-size: 35px;
    margin-bottom: 40px;
  }

  .text2 {
    font-size: 35px;
  }

  .rounded-btn {
    border-radius: 70px;
    padding: 30px;
    margin-top: 15%;
    margin-bottom: 30px;
    font-size: 35px;
  }

  .points {
    width: 200px;
  }
}
@media (max-width: 1440px) {
  .container-text {
    padding-left: 25px !important;
  }
  .title {
    font-size: 35px;
    margin-bottom: 25px;
  }

  .text1 {
    font-size: 23px;
    margin-bottom: 25px;
  }

  .text2 {
    font-size: 23px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    margin-top: 15%;
    font-weight: bold;
    font-size: 20px;
    margin-bottom: 30px;
  }

  .points {
    width: 100px;
  }
}
@media (max-width: 1024px) {
  .container-text {
    padding-left: 20px !important;
  }
  .title {
    font-size: 33px;
    margin-bottom: 18px;
  }

  .text1 {
    font-size: 20px;
    margin-bottom: 18px;
  }

  .text2 {
    font-size: 20px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    margin-top: 10%;
    font-weight: bold;
    font-size: 15px;
    margin-bottom: 10px;
  }

  .points {
    width: 70px;
  }
}
@media (max-width: 768px) {
  .container-text {
    padding-left: 10px !important;
  }
  .title {
    font-size: 25px;
    margin-bottom: 15px;
  }

  .text1 {
    font-size: 15px;
    margin-bottom: 15px;
  }

  .text2 {
    font-size: 15px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    margin-top: 12%;
    font-weight: bold;
    font-size: 10px;
    margin-bottom: 0px;
  }

  .points {
    width: 50px;
  }
}

@media (max-width: 425px) {
  .container-text {
    padding-left: 10px !important;
  }
  .title {
    font-size: 14px;
    margin-bottom: 6px;
  }

  .text1 {
    font-size: 8px;
    margin-bottom: 8px;
  }

  .text2 {
    font-size: 8px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 9px;
    margin-top: 11%;
    font-weight: bold;
    font-size: 6px;
    margin-bottom: 0px;
  }

  .points {
    width: 30px;
  }
}

@media (max-width: 375px) {
  .container-text {
    padding-left: 10px !important;
  }
  .title {
    font-size: 10px;
    margin-bottom: 6px;
  }

  .text1 {
    font-size: 7px;
    margin-bottom: 6px;
  }

  .text2 {
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 7px;
    margin-top: 10%;
    font-weight: bold;
    font-size: 5px;
    margin-bottom: 0px;
  }

  .points {
    width: 30px;
  }
}

@media (max-width: 322px) {
  .container-text {
    padding-left: 10px !important;
  }
  .title {
    font-size: 8px;
  }

  .text1 {
    font-size: 6px;
  }

  .text2 {
    font-size: 6px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 7px;
    margin-top: 10%;
    font-weight: bold;
    font-size: 5px;
    margin-bottom: 0px;
  }

  .points {
    width: 30px;
  }
}
</style>

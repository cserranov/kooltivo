<template>
  <v-container class="cursos">
    <div class="principal">
      <div class="sub-principal">
        <v-row no-gutters class="justify-center align-center">
          <v-col cols="12">
            <div class="container-title">
              <h2 class="title">Cursos de tecnología</h2>
              <p class="text1">
                Nos enfocamos en resolver las necesidades de conocimiento y
                capacitación especifica que atraviesa cada una de ustedes.
              </p>
            </div>
          </v-col>
          <v-col cols="12" class="container-carrucel">
            <v-carousel
              cycle
              hide-delimiter-background
              show-arrows="hover"
              hide-delimiters
            >
              <template v-slot:prev="{ props }">
                <img
                  src="../assets/img/boton1.png"
                  alt=""
                  @click="props.onClick"
                  class="btn-direction"
                />
              </template>
              <template v-slot:next="{ props }">
                <img
                  src="../assets/img/boton2.png"
                  alt=""
                  @click="props.onClick"
                  class="btn-direction"
                />
              </template>
              <v-carousel-item>
                <v-sheet height="100%">
                  <div
                    class="d-flex fill-height justify-center align-center"
                    style="background-color: #eeecec"
                  >
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel separador-img"
                    />
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel separador-img"
                    />
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel"
                    />
                  </div>
                </v-sheet>
              </v-carousel-item>
              <v-carousel-item>
                <v-sheet height="100%">
                  <div
                    class="d-flex fill-height justify-center align-center"
                    style="background-color: #eeecec"
                  >
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel separador-img"
                    />
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel separador-img"
                    />
                    <img
                      src="../assets/img/Pagkooltivo2-21.png"
                      alt=""
                      class="img-carrucel"
                    />
                  </div>
                </v-sheet>
              </v-carousel-item>
            </v-carousel>
            <div class="container-btn">
              <v-btn class="rounded-btn" variant="outlined"> SABER MÁS </v-btn>
            </div>
          </v-col>
        </v-row>
      </div>
      <div class="container-points">
        <img src="../assets/img/puntos.png" alt="" class="points" />
      </div>
    </div>
  </v-container>
</template>

<style scoped>
.cursos {
  padding-top: 0px !important;
}
.principal {
  background-color: #2b80a4;
  padding-top: 150px;
}

.sub-principal {
  background-color: #eeecec;
  border-radius: 200px 200px 0px 0px;
}

.title {
  font-weight: bold;
  font-size: 50px;
  text-align: start;
}
.text1 {
  font-size: 18px;
  margin-top: 15px;
}

.btn-direction {
  width: 90px;
}
.rounded-btn {
  border-radius: 50px;
  padding: 35px;
  margin-top: 1%;
  font-weight: bold;
  font-size: 25px;
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
.container-btn {
  text-align: center;
}
.container-points {
  text-align: center;
  background-color: white;
  padding: 20px;
}
.points {
  width: 130px;
}

@media (max-width: 2561px) {
  .principal {
    padding-top: 30px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 80px 20px 10px 80px;
  }
  .title {
    font-weight: bold;
    font-size: 60px;
  }
  .text1 {
    font-size: 30px;
    margin-top: 15px;
  }

  .v-carousel {
    margin: auto;
    height: 800px !important;
    width: 90%;
  }
  .btn-direction {
    width: 100px;
  }

  .img-carrucel {
    width: 32%;
  }
  .separador-img {
    margin-right: 30px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 30px;
    margin-top: 2%;
    font-weight: bold;
    font-size: 40px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 50px;
  }
  .container-points {
    padding: 20px;
  }
  .points {
    width: 200px;
  }
}
@media (max-width: 1440px) {
  .principal {
    padding-top: 30px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 45px;
  }
  .text1 {
    font-size: 20px;
    margin-top: 15px;
  }

  .v-carousel {
    margin: auto;
    height: 500px !important;
    width: 100%;
  }
  .btn-direction {
    width: 60px;
  }

  .img-carrucel {
    width: 32%;
  }
  .separador-img {
    margin-right: 10px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    margin-top: 2%;
    font-weight: bold;
    font-size: 20px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 25px;
  }
  .container-points {
    padding: 20px;
  }
  .points {
    width: 100px;
  }
}
@media (max-width: 1024px) {
  .principal {
    padding-top: 25px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 35px;
  }
  .text1 {
    font-size: 15px;
    margin-top: 15px;
  }

  .v-carousel {
    margin: auto;
    height: 300px !important;
    width: 100%;
  }
  .btn-direction {
    width: 55px;
  }

  .img-carrucel {
    width: 32%;
  }
  .separador-img {
    margin-right: 10px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    margin-top: 2%;
    font-weight: bold;
    font-size: 15px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 15px;
  }
  .container-points {
    padding: 3px;
  }
  .points {
    width: 80px;
  }
}
@media (max-width: 768px) {
  .principal {
    padding-top: 20px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 30px;
  }
  .text1 {
    font-size: 13px;
    margin-top: 15px;
  }

  .v-carousel {
    margin: auto;
    height: 250px !important;
    width: 87%;
  }
  .btn-direction {
    width: 50px;
  }

  .img-carrucel {
    width: 31%;
  }
  .separador-img {
    margin-right: 5px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 12px;
    margin-top: 1%;
    font-weight: bold;
    font-size: 10px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 15px;
  }
  .container-points {
    padding: 3px;
  }
  .points {
    width: 40px;
  }
}

@media (max-width: 425px) {
  .principal {
    padding-top: 17px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 17px;
  }
  .text1 {
    font-size: 8px;
    margin-top: 10px;
  }

  .v-carousel {
    height: 130px !important;
  }
  .btn-direction {
    width: 25px;
  }

  .img-carrucel {
    width: 30%;
  }
  .separador-img {
    margin-right: 5px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 10px;
    margin-top: 3%;
    font-weight: bold;
    font-size: 7px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 10px;
  }
  .container-points {
    padding: 3px;
  }
  .points {
    width: 40px;
  }
}

@media (max-width: 375px) {
  .principal {
    padding-top: 17px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 17px;
  }
  .text1 {
    font-size: 8px;
    margin-top: 10px;
  }

  .v-carousel {
    height: 100px !important;
  }
  .btn-direction {
    width: 25px;
  }

  .img-carrucel {
    width: 29%;
  }
  .separador-img {
    margin-right: 5px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 10px;
    margin-top: 1%;
    font-weight: bold;
    font-size: 7px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 10px;
  }
  .container-points {
    padding: 3px;
  }
  .points {
    width: 40px;
  }
}
@media (max-width: 322px) {
  .principal {
    padding-top: 17px;
  }

  .sub-principal {
    border-radius: 50px 50px 0px 0px;
  }

  .container-title {
    padding: 30px 20px 10px 20px;
  }
  .title {
    font-weight: bold;
    font-size: 17px;
  }
  .text1 {
    font-size: 8px;
    margin-top: 10px;
  }

  .v-carousel {
    height: 100px !important;
  }
  .btn-direction {
    width: 25px;
  }

  .img-carrucel {
    width: 28%;
  }
  .separador-img {
    margin-right: 5px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 10px;
    margin-top: 1%;
    font-weight: bold;
    font-size: 7px;
    border: 1px solid black;
    color: black;
  }

  .container-btn {
    margin-bottom: 10px;
  }
  .container-points {
    padding: 3px;
  }
  .points {
    width: 40px;
  }
}
</style>

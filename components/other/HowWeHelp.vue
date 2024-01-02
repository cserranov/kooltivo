<template>
  <v-container>
    <v-row no-gutters>
      <v-col cols="5">
        <v-row no-gutters>
          <v-col cols="12">
            <div class="container-text">¿Cómo Ayudamos?</div>
          </v-col>
          <v-col cols="12">
            <div class="container-float">
              <p>
                Ofrecemos cursos, capacitaciones y certificaciones que
                favoorecen al progreso social. Reconocemos que el desarrollo
                comunitario depende en gran medida del acceso a las
                oportunidades, autoestimas, respeto y cuidado a los individuos y
                todas las formas de vida.
              </p>
              <br />
              <p>
                Por ello, facilitamos opciones educativasy laborales capaces de
                mejorar el día a día de las personas, buscando obtener frutos en
                la sociedad.
              </p>
            </div>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="7">
        <div class="container-img">
          <img src="../assets/img/Pagkooltivo2-22.png" alt="" class="img" />
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.container-component {
  margin-top: 400px;
}

.container-img {
  padding: 30px;
}
.img {
  width: 100%;
}

.container-text {
  font-size: 50px;
  font-weight: bold;
  padding-top: 250px;
  text-align: center;
  height: 470px;
}
.container-float {
  text-align: justify;
  position: absolute;
  width: 40%;
  height: 32%;
  background-color: rgba(0, 0, 0, 0.5);
  color: rgba(255, 255, 255, 0.479);
  padding: 80px;
  border-radius: 60px;
  font-size: 25px;
  left: 345px;
}

@media (max-width: 1920px) {
  .container-img {
    padding: 100px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 50px;
    font-weight: bold;
    padding-top: 230px;
    text-align: center;
    height: 460px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 49%;
    height: 32%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 60px;
    border-radius: 30px;
    font-size: 20px;
    left: 140px;
  }
}
@media (max-width: 1440px) {
  .container-component {
    margin-top: 220px;
  }

  .container-img {
    padding: 20px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 35px;
    font-weight: bold;
    padding-top: 150px;
    text-align: center;
    height: 300px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 45%;
    height: 28%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 40px;
    border-radius: 20px;
    font-size: 17px;
    left: 135px;
  }
}
@media (max-width: 1024px) {
  .container-component {
    margin-top: 170px;
  }

  .container-img {
    padding: 20px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 25px;
    font-weight: bold;
    padding-top: 120px;
    text-align: center;
    height: 225px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 47%;
    height: 20%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 10px;
    border-radius: 15px;
    font-size: 14px;
    left: 75px;
  }
}
@media (max-width: 768px) {
  .container-component {
    margin-top: 170px;
  }

  .container-img {
    padding: 20px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 20px;
    font-weight: bold;
    padding-top: 100px;
    text-align: center;
    height: 190px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 53%;
    height: 17%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 10px;
    border-radius: 15px;
    font-size: 12px;
    left: 17px;
  }
}

@media (max-width: 425px) {
  .container-component {
    margin-top: 120px;
  }

  .container-img {
    padding: 15px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 15px;
    font-weight: bold;
    padding-top: 50px;
    text-align: center;
    height: 100px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 53%;
    height: 9%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 13px;
    border-radius: 15px;
    font-size: 7px;
    left: 17px;
  }
}

@media (max-width: 375px) {
  .container-component {
    margin-top: 100px;
  }

  .container-img {
    padding: 5px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 12px;
    font-weight: bold;
    padding-top: 35px;
    text-align: center;
    height: 85px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 50%;
    height: 8%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 8px;
    border-radius: 10px;
    font-size: 7px;
    left: 17px;
  }
}

@media (max-width: 322px) {
  .container-img {
    padding: 5px;
  }
  .img {
    width: 100%;
  }

  .container-text {
    font-size: 10px;
    font-weight: bold;
    padding-top: 35px;
    text-align: center;
    height: 75px;
  }
  .container-float {
    text-align: justify;
    position: absolute;
    width: 50%;
    height: 6%;
    background-color: rgba(0, 0, 0, 0.5);
    color: rgba(255, 255, 255, 0.479);
    padding: 3px;
    border-radius: 10px;
    font-size: 6px;
    left: 17px;
  }
}
</style>

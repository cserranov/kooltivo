<template>
  <div class="container-main desktop" style="position: relative">
    <div class="image-container">
      <img
        src="@/assets/img/Pagkooltivo2-20.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div
      style="
        position: absolute;
        top: 3%;
        width: 30%;
        right: 5%;
        color: white;
        text-align: center;
        height: 35%;
      "
    >
      <p class="title">SOMOS KOOL</p>
      <p class="texto">
        Ofrecemos programas de capacitación tecnológica, educación financiera y
        cultural con la intención de brindarte oportunidades que pueden cambiar
        tu vida.
      </p>
      <img src="@/assets/img/circuloskool.png" alt="" style="width: 15%" />
      <div>
        <v-btn
          style="margin-top: 2%"
          class="rounded-btn-somos"
          variant="outlined"
          @click="navigateTo('/courses')"
        >
          Cursos y certificaciones en Tecnología
        </v-btn>
      </div>
    </div>
    <v-row no-gutters class="container-courses">
      <v-col
        cols="3"
        style="
          position: relative;
          width: 100%;
          height: 100%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              left: 14%;
              position: absolute;
              top: 0%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CURSOS
              </p>
              <p style="text-align: center" class="txtnew">Paquetería office</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="3"
        style="
          position: relative;
          width: 100%;
          height: 100%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              position: absolute;
              top: 0%;
              left: 14%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">Veeam</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="3"
        style="
          position: relative;
          width: 100%;
          height: 100%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              position: absolute;
              top: 0%;
              left: 14%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">
                Automation Anywhere
              </p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="3"
        style="
          position: relative;
          width: 100%;
          height: 100%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              position: absolute;
              top: 0%;
              left: 14%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">Micro Focus</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main mobil" style="position: relative">
    <div class="image-container">
      <img
        src="@/assets/img/mobil/Pag_kooltivo_familia_movi.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div
      style="
        position: absolute;
        top: 7%;
        width: 30%;
        right: 5%;
        color: white;
        text-align: center;
        height: 35%;
      "
    >
      <p class="title">SOMOS KOOL</p>
      <p class="texto">
        Ofrecemos programas de capacitación financiera, tecnológica, educativa y
        cultural, con la finalidad de integrarlo en su día a día
      </p>
      <img src="@/assets/img/circuloskool.png" alt="" style="width: 15%" />
    </div>
    <v-row no-gutters class="container-courses">
      <v-col
        cols="6"
        style="
          position: relative;
          width: 100%;
          height: 50%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              left: 14%;
              position: absolute;
              top: 0%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CURSOS
              </p>
              <p style="text-align: center" class="txtnew">Paquetería office</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="6"
        style="
          position: relative;
          width: 100%;
          height: 50%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              left: 14%;
              position: absolute;
              top: 0%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;

              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">Veeam</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="6"
        style="
          position: relative;
          width: 100%;
          height: 50%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              left: 14%;
              position: absolute;
              top: 0%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;

              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">
                Automation Anywhere
              </p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        cols="6"
        style="
          position: relative;
          width: 100%;
          height: 50%;
          padding: 2% 1% 1% 1%;
        "
      >
        <div
          style="
            width: 100%;
            height: 100%;
            border: solid black 1px;
            border-radius: 20px;
          "
        >
          <img
            class="img"
            src="@/assets/img/cursos/cuadro_cursos.png"
            alt=""
            style="width: 100%; height: 100%"
          />
          <div
            style="
              width: 20%;
              height: 25%;
              left: 14%;
              position: absolute;
              top: 0%;
            "
          >
            <img
              src="@/assets/img/EducacionTecnologica.png"
              alt=""
              style="width: 100%; height: 100%"
            />
          </div>
          <div class="title-course">
            <p>EDUCACIÓN TECNOLÓGICA</p>
          </div>
          <div
            style="
              width: 70%;
              left: 15%;
              height: 55%;
              top: 29%;
              position: absolute;
              text-align: center;
              color: #898888;
            "
          >
            <div>
              <p
                style="
                  text-align: center;
                  font-weight: bold;
                  margin-bottom: 5%;
                  margin-top: 5%;
                "
                class="txtnew"
              >
                CERTIFICADOS
              </p>
              <p style="text-align: center" class="txtnew">Micro Focus</p>
              <v-btn
                style="margin-top: 10%"
                class="rounded-btn"
                variant="outlined"
                @click="navigateTo('/courses')"
              >
                Inscríbete
              </v-btn>
            </div>
          </div>
        </div>
      </v-col>
    </v-row>
  </div>
</template>
<script>
export default {
  methods: {
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>
<style scoped>
.container-main {
  width: 100%;
  height: 100vh;
}

.image-container {
  width: 100%;
  height: 65%;
}

.container-courses {
  width: 90%;
  height: 39%;
  bottom: 0%;
  right: 5%;
  position: absolute;
}

.title {
  font-size: 2.5vw;
  font-weight: bold;
  margin-bottom: 5%;
}

.texto {
  font-size: 1.5vw;
  text-align: justify;
  margin-bottom: 5%;
}

.title-course {
  color: #888888;
  width: 53%;
  left: 34%;
  top: 18%;
  font-size: 0.8vw;
  position: absolute;
  font-weight: bold;
  text-align: end;
}

.txtnew {
  font-size: 1.1vw;
}

.rounded-btn {
  text-transform: capitalize;
  border-radius: 1.5vw;
  padding: 7% 10%;
  font-weight: bold;
  font-size: 0.8vw;
  color: white;
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}

.rounded-btn-somos {
  text-transform: capitalize;
  border-radius: 1.5vw;
  padding: 3% 5%;
  font-weight: bold;
  font-size: 1vw;
  color: white;
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn-somos.v-btn--density-default {
  height: auto;
}

.desktop {
  display: block;
}

.mobil {
  display: none;
}

@media (max-width: 1440px) {
  .container-main {
    height: 100vh;
  }

  .texto {
    margin-bottom: 5%;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 1024px) {
  .container-main {
    height: 60vh;
  }

  .texto {
    margin-bottom: 5%;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 768px) {
  .container-main {
    height: 45vh;
  }

  .texto {
    margin-bottom: 5%;
  }

  ¿ .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 75vh;
  }

  .image-container {
    width: 100%;
    height: 40%;
  }

  .container-courses {
    width: 90%;
    height: 62%;
    bottom: 0%;
    right: 5%;
    position: absolute;
  }

  .title {
    font-size: 4vw;
    font-weight: bold;
    margin-bottom: 5%;
  }

  .texto {
    font-size: 1.8vw;
    margin-bottom: 5%;
    text-align: center;
  }

  .title-course {
    color: #888888;
    width: 53%;
    left: 34%;
    top: 18%;
    font-size: 1.5vw;
    position: absolute;
    font-weight: bold;
    text-align: end;
  }

  .txtnew {
    font-size: 2vw;
  }

  .rounded-btn {
    text-transform: capitalize;
    font-size: 1.5vw;
    padding: 7% 10%;
  }
}

@media (max-width: 375px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 50vh;
  }

  .image-container {
    width: 100%;
    height: 40%;
  }

  .container-courses {
    width: 90%;
    height: 62%;
    bottom: 0%;
    right: 5%;
    position: absolute;
  }

  .title {
    margin-bottom: 2%;
  }

  .texto {
    margin-bottom: 2%;
    text-align: center;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 75vh;
  }

  .image-container {
    width: 100%;
    height: 40%;
  }

  .container-courses {
    width: 90%;
    height: 62%;
    bottom: 0%;
    right: 5%;
    position: absolute;
  }

  .texto {
    margin-bottom: 5%;
    text-align: center;
  }

  .title-course {
    color: #888888;
    width: 53%;
    left: 34%;
    top: 18%;

    position: absolute;
    font-weight: bold;
    text-align: end;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 360px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 50vh;
  }

  .image-container {
    width: 100%;
    height: 40%;
  }

  .container-courses {
    width: 90%;
    height: 62%;
    bottom: 0%;
    right: 5%;
    position: absolute;
  }

  .title {
    margin-bottom: 2%;
  }

  .texto {
    margin-bottom: 2%;
    text-align: center;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}

@media (max-width: 320px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    height: 45vh;
  }

  .image-container {
    width: 100%;
    height: 40%;
  }

  .container-courses {
    width: 90%;
    height: 62%;
    bottom: 0%;
    right: 5%;
    position: absolute;
  }

  .title {
    margin-bottom: 2%;
  }

  .texto {
    margin-bottom: 2%;
    text-align: center;
  }

  .rounded-btn {
    text-transform: capitalize;

    padding: 7% 10%;
  }
}
</style>

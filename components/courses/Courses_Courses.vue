<template>
  <div style="margin-top: 5%; width: 100%">
    <v-row>
      <v-col class="container-text" cols="4">
        <p class="title">CURSOS KOOLTIVO</p>
      </v-col>
      <v-col cols="8">
        <img src="@/assets/img/linea_gris_ejes.png" alt="" style="width: 100%" />
      </v-col>
    </v-row>
  </div>
  <div class="container">
    <div>
      <v-row>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT EXCEL</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_excel/excel.png" alt="" style="width: 20%" />
                <p class="txt">EXCEL BÁSICO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT EXCEL</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_excel/excel.png" alt="" style="width: 20%" />
                <p class="txt">EXCEL INTERMEDIO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT EXCEL</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_excel/excel.png" alt="" style="width: 20%" />
                <p class="txt">EXCEL AVANZADO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT WORD</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_word/word.png" alt="" style="width: 20%" />
                <p class="txt">WORD BÁSICO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT WORD</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_word/word.png" alt="" style="width: 20%" />
                <p class="txt">WORD INTERMEDIO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT WORD</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_word/word.png" alt="" style="width: 20%" />
                <p class="txt">WORD AVANZADO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT POWER</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_power_point/powerpoint.png" alt=""
                  style="width: 20%" />
                <p class="txt">
                  POWER POINT <br />
                  BÁSICO
                </p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT POWER</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_power_point/powerpoint.png" alt=""
                  style="width: 20%" />
                <p class="txt">POWER POINT INTERMEDIO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="6" sm="4" class="text-center" style="position: relative">
          <div style="position: relative; border-radius: 20px">
            <img class="img" src="@/assets/img/cursos/cuadro_cursos1.png" alt="" style="width: 100%; height: 100%" />
            <div style="
                    position: absolute;
                    top: 20%;
                    right: 20%;
                    color: #8a8a8a;
                    font-weight: 600;
                  ">
              <p class="title-curso">MICROSOFT POWER</p>
            </div>
            <div style="
                    position: absolute;
                    width: 73%;
                    top: 30%;
                    left: 11%;
                    height: 50%;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    color: #8a8a8a;
                    padding: 8%;
                  ">
              <div>
                <img src="https://kooltivo.s3.us-east-2.amazonaws.com/cursos_power_point/powerpoint.png" alt=""
                  style="width: 20%" />
                <p class="txt">POWER POINT AVANZADO</p>
                <v-btn class="rounded-btn btn-route" variant="outlined" @click="facebook()">
                  INSCRIBIRSE
                </v-btn>
              </div>
            </div>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    enviarCorreo() {
      const correo = "contacto@kooltivo.org";
      const url = `mailto:${correo}`;
      window.open(url);
    },
    whatsApp() {
      window.open(
        "https://wa.me/+525511519270?text=%C2%A1Hola,%20quisiera%20recibir%20informaci%C3%B3n!"
      );
    },
    instagram() {
      window.open("https://www.instagram.com/kooltivo_/?hl=es-la", "_blank");
    },
    twitter() {
      window.open("https://twitter.com/Kooltivo_", "_blank");
    },
    facebook() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
  },
};
</script>
<style scoped>
.container-text {
  display: flex;
  padding-left: 8%;
  align-items: center;
}

.btn-route {
  transition: all 0.3s ease;
  /* Agregar una transición suave */
}

.btn-route:hover {
  transform: scale(1.1);
}

.container {
  padding: 5%;
}

.container-title {
  padding: 0% 5% 5%;
  text-align: start;
}

.title {
  font-size: 30px;
  color: #8a8a8a;
  font-weight: 600;
}

.title-curso {
  text-align: end;
  font-size: 15px;
}

.txt {
  font-size: 20px;
}

.rounded-btn {
  border-radius: 50px;
  padding: 30px 40px;
  font-weight: bold;
  font-size: 15px;
  border: 1px solid #ffac00;
  color: white;
  background-color: #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}

@media (max-width: 1440px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 30px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 15px;
  }

  .txt {
    font-size: 18px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 20px;
    font-weight: bold;
    font-size: 15px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 1024px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 20px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 12px;
  }

  .txt {
    font-size: 12px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 15px;

    font-weight: bold;
    font-size: 10px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 768px) {
  .container-cursos {
    width: 35%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 65%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 18px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 8px;
  }

  .txt {
    font-size: 10px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 10px;

    font-weight: bold;
    font-size: 9px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 430px) {
  .container-cursos {
    width: 40%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 7px;
  }

  .txt {
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 5px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 425px) {
  .container-cursos {
    width: 40%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 60%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 7px;
  }

  .txt {
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 5px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 390px) {
  .container-cursos {
    width: 45%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 6px;
  }

  .txt {
    font-size: 6px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 2px 0px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 375px) {
  .container-cursos {
    width: 45%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 6px;
  }

  .txt {
    font-size: 6px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 2px 0px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 360px) {
  .container-cursos {
    width: 45%;
    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea -curso {
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 6px;
  }

  .txt {
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 2px 0px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}

@media (max-width: 322px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 5% 5%;
    text-align: start;
  }

  .title {
    font-size: 13px;
  }

  img {
    width: 100%;
  }

  .title-curso {
    text-align: end;
    font-size: 7px;
  }

  .txt {
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 50px;
    padding: 2px 0px;

    font-weight: bold;
    font-size: 5px;
    border: 1px solid #ffac00;
    color: white;
    background-color: #ffac00;
  }

  .rounded-btn.v-btn--density-default {
    height: auto;
  }

  .v-btn--size-default {
    min-width: 50px;
  }
}
</style>

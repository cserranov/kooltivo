<template>
  <!--  <div style="display: flex; margin-top: 5%">-->
  <!--    <div class="container-title-linea">-->
  <!--      <p class="title">CERTIFICACIONES</p>-->
  <!--    </div>-->
  <!--    <div class="container-linea">-->
  <!--      <img src="@/assets/img/linea_gris_ejes.png" alt="" style="width: 100%" />-->
  <!--    </div>-->
  <!--  </div>-->
  <div class="container">
    <div class="container-title desktop">
      <v-tabs v-model="tab">
        <v-tab
          style="flex: 1"
          value="three"
          :class="{ 'tab-1': tab === 'three', 'tab-2': tab !== 'three' }"
          @click="tab = 'three'"
          id="space-tabs"
          >MICROSOFT
        </v-tab>
      </v-tabs>
      <div>
        <v-window v-model="tab">
          <v-window-item value="three">
            <div class="container-courses">
              <p>
                <span class="title-course" style="text-transform: uppercase"
                  >Capacitación en Tecnología Microsoft
                  <br />
                  para el Empoderamiento Digital
                </span>
                <br />
                <br />
                <span class="subtitle-course" style="text-transform: uppercase"
                  >Herramientas de Microsoft (Word, Excel y PowerPoint)
                </span>
                <br />
                <br />
                <span class="content">
                  Con estos cursos podrás adquirir habilidades esenciales en
                  tecnología Microsoft y avanzar en tu carrera profesional.
                  Nuestra misión es promover el empoderamiento digital y el
                  acceso a la educación de calidad para todos, y estos cursos
                  son parte fundamental, básica y necesaria de ese compromiso.
                  <br />
                  <br />
                  <span style="font-weight: bold">Fecha de inicio</span>:
                  Siempre disponible
                  <br />
                  <br />
                  <span style="font-weight: bold">Duración</span>: A tu tiempo.
                  Formato on-demand*
                  <br />
                  <br />
                  <span style="font-weight: bold">Plataforma</span>: Todos los
                  cursos se llevarán a cabo de manera virtual a través de la
                  plataforma de Kooltivo.
                  <br />
                  <br />
                  <span style="font-weight: bold">Certificación</span>: Al
                  finalizar con éxito cada curso, recibirás un certificado
                  avalado por Fundacion Kooltivo.
                </span>
              </p>
              <p class="final">¡Me interesa!</p>
              <div style="text-align: center; margin-top: 5%">
                <button @click="navigateTo('/certificaciones/microsoft')">
                  <img
                    src="@/assets/img/cursos/microsoft.png"
                    alt=""
                    style="width: 30%"
                  />
                </button>
              </div>
            </div>

            <div class="tiempo">
              <p></p>
            </div>
          </v-window-item>
        </v-window>
      </div>
    </div>

    <div class="container-title mobil">
      <div style="margin-bottom: 5%">
        <div
          style="display: flex; justify-content: center; align-items: center"
        >
          <div
            style="
              width: 60%;
              height: 70px;
              display: flex;
              justify-content: center;
              align-items: center;
              border-radius: 20px;
              background-image: linear-gradient(to right, #318ae0, #3eb9f4);
              color: white;
              font-size: 15px;
              font-weight: bold;
            "
            @click="cambio_microsoft()"
          >
            <p>Microsoft</p>
          </div>
        </div>
        <div v-if="microsoft">
          <div class="container-courses">
            <p>
              <span class="title-course" style="text-transform: uppercase"
                >Microsoft
                <br />
                <br />
                <span class="letra-mobil">
                  Capacitación en Tecnología
                  <br />
                  para el Empoderamiento Digital</span
                >
              </span>
              <br />
              <br />
              <span class="subtitle-course" style="text-transform: uppercase"
                >Herramientas de Microsoft (Word, Excel y PowerPoint)
              </span>
              <br />
              <br />
              <span class="content">
                Con estos cursos podrás adquirir habilidades esenciales en
                tecnología Microsoft y avanzar en tu carrera profesional.
                Nuestra misión es promover el empoderamiento digital y el acceso
                a la educación de calidad para todos, y estos cursos son parte
                fundamental, básica y necesaria de ese compromiso.
                <br />
                <br />
                <span style="font-weight: bold">Fecha de inicio</span>: Siempre
                disponible.
                <br />
                <br />
                <span style="font-weight: bold">Duración</span>: A tu tiempo.
                Formato on-demand*.
                <br />
                <br />
                <span style="font-weight: bold">Plataforma</span>: Todos los
                cursos se llevarán a cabo de manera virtual a través de la
                plataforma de Kooltivo.
                <br />
                <br />
                <span style="font-weight: bold">Certificación</span>: Al
                finalizar con éxito cada curso, recibirás un certificado avalado
                por Fundacion Kooltivo.
              </span>
            </p>
            <p class="final">¡Me interesa!</p>
            <div style="text-align: center; margin-top: 5%">
              <button @click="navigateTo('/certificaciones/microsoft')">
                <img
                  src="@/assets/img/cursos/microsoft.png"
                  alt=""
                  style="width: 40%"
                />
              </button>
            </div>
          </div>
          <div class="tiempo">
            <p></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    tab: "one", // Establece la pestaña predeterminada
    veeam: false,
    microsoft: false,
    micro: false,
    auto: false,
  }),
  methods: {
    cambio_microsoft() {
      this.microsoft = !this.microsoft;
    },
    cambio_micro() {
      this.micro = !this.micro;
    },
    cambio_veeam() {
      this.veeam = !this.veeam;
    },
    cambio_auto() {
      this.auto = !this.auto;
    },
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>

<style scoped>
.container-title-linea {
  width: 23%;
  padding-left: 5%;
  display: flex;
  align-items: center;
}

.container-linea {
  width: 77%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.desktop {
  display: block;
}

.mobil {
  display: none;
}

.container {
  padding: 5% 5% 3%;
}

.container-title {
  padding: 0px 50px;
  text-align: start;
  /* margin-bottom: 50px; */
}

.title {
  font-size: 30px;
  color: #8a8a8a;
  font-weight: 600;
}

.tab-1 {
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  background-image: linear-gradient(to right, #318ae0, #3eb9f4);
  color: white;
  font-size: 1.2vw;
}

.tab-2 {
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  color: black;
  font-size: 1.2vw;
}

.container-courses {
  background-color: #eeecec;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
  padding: 50px;
  text-align: justify;
}

.title-course {
  font-size: 35px;
  font-weight: bold;
  text-align: start;
}

.subtitle-course {
  font-size: 30px;
  color: #318ae0;
}

.content {
  font-size: 25px;
}

.final {
  margin-top: 100px;
  font-size: 25px;
  text-align: center;
}

.tiempo {
  margin-top: 50px;
  font-size: 20px;
}

.linea {
  width: 35%;
  position: absolute;
  top: 40%;
  left: 33%;
}

#space-tabs {
  /* margin-right: px; */
  padding: 0px 30px;
}

@media (max-width: 1440px) {
  .container-title-linea {
    width: 30%;
    padding-left: 7%;
    display: flex;
    align-items: center;
  }

  .container-linea {
    width: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 30px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 50px;
  }

  .title-course {
    font-size: 25px;
  }

  .subtitle-course {
    font-size: 30px;
  }

  .content {
    font-size: 25px;
  }

  .final {
    margin-top: 100px;
    font-size: 25px;
    text-align: center;
  }

  .tiempo {
    margin-top: 50px;
    font-size: 20px;

    height: 50px;
  }

  .linea {
    width: 52%;
    position: absolute;
    top: 40%;
    left: 24%;
  }

  #space-tabs {
    /* margin-right: px; */

    padding: 0px 40px;
  }
}

@media (max-width: 1024px) {
  .container-title-linea {
    width: 30%;
    padding-left: 7%;
    display: flex;
    align-items: center;
  }

  .container-linea {
    width: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 25px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 28px;
  }

  .subtitle-course {
    font-size: 27px;
  }

  .content {
    font-size: 25px;
  }

  .final {
    margin-top: 10%;
    font-size: 25px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 20px;
  }

  #space-tabs {
    padding: 0px 30px;
  }
}

@media (max-width: 768px) {
  .container-title-linea {
    width: 40%;

    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea {
    width: 60%;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 25px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 23px;
  }

  .subtitle-course {
    font-size: 20px;
  }

  .content {
    font-size: 18px;
  }

  .final {
    margin-top: 10%;
    font-size: 20px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 20px;
  }

  #space-tabs {
    padding: 0px 20px;
  }
}

@media (max-width: 600px) {
  .letra-mobil {
    font-size: 15px;
  }

  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }
}

@media (max-width: 425px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 18px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 20px;
  }

  .subtitle-course {
    font-size: 18px;
  }

  .content {
    font-size: 15px;
  }

  .final {
    margin-top: 10%;
    font-size: 18px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 12px;
  }

  .linea {
    width: 100%;
    position: absolute;
    top: 80%;
    left: 0%;
  }

  #space-tabs {
    padding: 0px 5px;
  }
}

@media (max-width: 375px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 15px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 17px;
  }

  .subtitle-course {
    font-size: 15px;
  }

  .content {
    font-size: 15px;
  }

  .final {
    margin-top: 10%;
    font-size: 15px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 15px;
  }

  #space-tabs {
    padding: 0px 40px;
  }
}

@media (max-width: 360px) {
  .letra-mobil {
    font-size: 14px;
  }
}

@media (max-width: 322px) {
  .container-title-linea {
    width: 50%;

    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea {
    width: 50%;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 15px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 15px;
  }

  .subtitle-course {
    font-size: 14px;
  }

  .content {
    font-size: 13px;
  }

  .final {
    margin-top: 10%;
    font-size: 15px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 15px;
  }

  #space-tabs {
    padding: 0px 40px;
  }
}
</style>

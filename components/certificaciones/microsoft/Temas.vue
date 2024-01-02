<template>
  <div class="container-main">
    <v-row no-gutters>
      <v-col cols="12">
        <div style="text-align: center">
          <p class="title">Temas que se abordarán:</p>
          <p class="txt">
            Esta serie de cursos te enseñará los fundamentos básicos de
            Microsoft Office Suite, es decir:
          </p>
          <p class="txt">Word, Excel y Power Point.</p>
        </div>
      </v-col>
      <v-col cols="12" style="padding-top: 5%">
        <v-row>
          <v-col cols="6">
            <v-row>
              <v-col cols="12">
                <img src="@/assets/img/elementos_microsoft/text_2.png" alt="" style="width: 100%" />
              </v-col>
              <v-col cols="12" style="
                        position: relative;

                        display: flex;
                        justify-content: center;
                        align-items: center;
                      ">
                <div class="cuadro-azul-title">
                  <p>Contacto para Consultas</p>
                </div>
                <div class="cuadro-azul-txt">
                  <p>
                    Para cualquier pregunta o para obtener más información, no
                    dudes en ponerte en contacto con nosotros a través de
                    contacto@kooltivo.org
                  </p>
                </div>
              </v-col>
            </v-row>
          </v-col>

          <!--                    <v-col cols="6" style="position: relative; display: flex;
                                  justify-content: center;
                                  align-items: center;
                                  border: solid red 1px">
                                <div class="inscribirme-title">
                                  <p>Como Inscribirme</p>
                                </div>
                                <div class="inscribirme-txt">
                                  <div style="padding: 5%">
                                    <p style="margin-bottom: 2%">
                                      1. Visita nuestro sitio web en https://www.kooltivo.org/
                                    </p>
                                    <p style="margin-bottom: 2%">
                                      2. Completa el formulario de inscripción en linea
                                    </p>
                                    <p style="margin-bottom: 2%">
                                      3. Recibirás un correo electrónico de confirmación con
                                      detalles sobre como acceder a los cursos
                                    </p>
                                  </div>
                                  <div class="no-pierdas">
                                    <p style="margin-bottom: 5%">
                                      No pierdas la oportunidad de fortalecer tus habilidades en
                                      tecnología Microsoft y aumentar tus perspectivas laborales.
                                    </p>
                                    <p>
                                      En fundación Kooltivo. estamos comprometidos en brindarte las
                                      herramientas necesarias para tu éxito.¡Esperamos verte en
                                      linea !
                                    </p>
                                  </div>
                                </div>
                              </v-col>-->

          <v-col cols="6" style="padding: 2%">
            <div style="width: 100%; height: 100%; position: relative; padding: 3%">
              <div style="
                        z-index: 1;
                        width: 25%;
                        height: 25%;
                        background-color: #ffb608;
                        position: absolute;
                        top: 0%;
                        left: 0%;
                        border-radius: 15px;
                      "></div>
              <div style="
                        width: 25%;
                        height: 25%;
                        background-color: #80b806;
                        position: absolute;
                        bottom: 0%;
                        right: 0%;
                        border-radius: 15px;
                      "></div>
              <div style="
                        z-index: 2;
                        position: relative;
                        background-color: white;
                        width: 100%;
                        height: 100%;
                        border-radius: 10px;
                        border: solid #05a2ec 1px;
                        display: flex;
                        justify-content: center;
                        align-items: center;
                      ">
                <div class="inscribirme-txt">
                  <div style="padding: 5%">
                    <p style="margin-bottom: 2%">
                      1. Visita nuestro sitio web en https://www.kooltivo.org/
                    </p>
                    <p style="margin-bottom: 2%">
                      2. Completa el formulario de inscripción en linea
                    </p>
                    <p style="margin-bottom: 2%">
                      3. Recibirás un correo electrónico de confirmación con
                      detalles sobre como acceder a los cursos
                    </p>
                  </div>
                  <div class="no-pierdas">
                    <p style="margin-bottom: 5%">
                      No pierdas la oportunidad de fortalecer tus habilidades en
                      tecnología Microsoft y aumentar tus perspectivas
                      laborales.
                    </p>
                    <p>
                      En fundación Kooltivo. estamos comprometidos en brindarte
                      las herramientas necesarias para tu éxito.¡Esperamos verte
                      en linea !
                    </p>
                    <div style="text-align: center; margin-top: 10%" class="btn-route">
                      <img src="@/assets/img/btn-registro.png" alt="" style="width: 40%" @click="registro()" />
                    </div>
                  </div>
                </div>
                <div class="inscribirme-title">
                  <p>Como Inscribirme</p>
                </div>
              </div>
            </div>
          </v-col>
        </v-row>
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
.container-main {
  padding: 5% 7%;
}

.title {
  font-size: 2.5vw;
  font-weight: bold;
  margin-bottom: 3%;
}

.txt {
  font-size: 1.8vw;
}

.cuadro-azul-title {
  position: absolute;
  top: 0%;
  font-size: 1.5vw;
  background-color: white;
  font-weight: bold;
  padding: 0% 2%;
}

.cuadro-azul-txt {
  border: solid 1px blue;
  font-size: 1.3vw;
  padding: 7% 15%;
  text-align: center;
  border-radius: 40px;
}

.inscribirme-title {
  position: absolute;
  top: -4%;
  font-size: 1.5vw;
  background-color: white;
  font-weight: bold;
  padding: 0% 2%;
}

.inscribirme-txt {
  font-size: 1.2vw;
  width: 90%;
  padding: 5%;
}

.no-pierdas {
  font-weight: bold;
  font-size: 1.2vw;
}

@media (max-width: 1000px) {
  .cuadro-azul-txt {
    border-radius: 20px;
  }
}

@media (max-width: 600px) {
  .cuadro-azul-txt {
    border-radius: 10px;
  }
}
</style>


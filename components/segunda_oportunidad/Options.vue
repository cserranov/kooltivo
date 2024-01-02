<template>
  <div style="position: relative; margin-top: 5%">
    <v-row no-gutters>
      <v-col cols="4">
        <img
          class="img"
          src="@/assets/img/perrito_mayor/perro.png"
          alt=""
          style="width: 100%"
        />
      </v-col>
      <v-col cols="8">
        <div>
          <div style="margin-bottom: 5%">
            <div
              style="
                display: flex;
                justify-content: center;
                align-items: center;
              "
            >
              <div
                style="
                  padding: 1vw 4vw;
                  width: 35vw;
                  border-radius: 4vw;
                  background-color: #ffac00;
                  color: white;
                  font-size: 1.2vw;
                  font-weight: bold;
                "
              >
                <p style="text-align: center">¿Cómo Puedes Ayudar?</p>
              </div>
            </div>
            <div v-if="auto">
              <div style="padding: 0% 5%">
                <div class="container-txt">
                  <p class="txt">
                    Apadrinar a un perro mayor significa brindar apoyo
                    financiero para su cuidado, incluyendo su salud,
                    alimentación y campaña especial de adopción. Tú puedes hacer
                    una gran diferencia en sus vidas.
                  </p>

                  <p class="txt">
                    Al unirte al programa "Segunda Oportunidad para un Perro
                    Mayor", tienes la flexibilidad de contribuir mensualmente
                    con el monto completo de $2,600 pesos mexicanos o con la
                    cantidad que desees. Todo suma. Cuando varias personas se
                    unen y sus donaciones mensuales acumuladas alcanzan el total
                    de $2,600, asignamos esos fondos a un perrito mayor en
                    necesidad. Esto garantiza que todos puedan participar y que
                    cada donación, sin importar su tamaño, se recolecte y sea
                    una contribución significativa.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <v-row>
            <v-col cols="6" style="padding: 2%">
              <div style="margin-bottom: 5%">
                <div>
                  <div
                    class="btn-route"
                    style="
                      padding: 1vw 4vw;

                      display: flex;
                      justify-content: center;
                      align-items: center;
                      border-radius: 4vw;
                      background-color: #ffac00;
                      color: white;
                      font-size: 1.2vw;
                      font-weight: bold;
                      text-align: center;
                    "
                    @click="cambio_microsoft()"
                  >
                    <p>
                      Opciones de Donación
                      <br />
                      Personalizada
                    </p>
                  </div>
                </div>
                <div v-if="microsoft">
                  <div style="padding: 0% 5%">
                    <div class="container-txt">
                      <p class="txt">
                        Te damos la libertad de elegir la cantidad que deseas
                        donar mensualmente. Puedes abonar cualquier suma que
                        esté dentro de tus posibilidades y voluntad de apoyar a
                        estos perritos que necesitan de una segunda oportunidad.
                        Cada contribución, nos acerca más a nuestro objetivo de
                        proporcionarles cuidado, amor, protección y promocionar
                        su adopción.
                      </p>
                      <div style="text-align: center">
                        <v-btn
                          style="margin-top: 10%"
                          class="rounded-btn btn-route"
                          variant="outlined"
                          @click="navigateTo('/courses')"
                        >
                          Donar
                        </v-btn>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </v-col>
            <v-col cols="6" style="padding: 2%">
              <div style="margin-bottom: 5%">
                <div>
                  <div
                    class="btn-route"
                    style="
                      padding: 1vw 4vw;
                      display: flex;
                      justify-content: center;
                      align-items: center;
                      border-radius: 4vw;
                      background-color: #ffac00;
                      color: white;
                      font-size: 1.2vw;
                      font-weight: bold;
                      text-align: center;
                    "
                    @click="cambio_micro()"
                  >
                    <p>
                      Apoyo por
                      <br />
                      $2,600 pesos
                    </p>
                  </div>
                </div>
                <div v-if="micro">
                  <div style="padding: 0% 5%">
                    <div class="container-txt">
                      <p class="txt">
                        Cuando las donaciones mensuales acumuladas para un
                        perrito mayor alcanzan la suma de $2,600 pesos, ese
                        perrito se convierte oficialmente en el beneficiario del
                        programa "Segunda Oportunidad para un Perro Mayor". Esto
                        significa que el perrito recibe todos los beneficios,
                        incluyendo alimentación, atención médica, amor,
                        preparación y una campaña especial para su adopción.
                      </p>
                      <div style="text-align: center">
                        <v-btn
                          style="margin-top: 10%"
                          class="rounded-btn btn-route"
                          variant="outlined"
                          @click="navigateTo('/courses')"
                        >
                          Apadrinar
                        </v-btn>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </v-col>
          </v-row>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      microsoft: false,
      micro: false,
      auto: true,
    };
  },
  methods: {
    cambio_microsoft() {
      this.microsoft = !this.microsoft;
    },
    cambio_micro() {
      this.micro = !this.micro;
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
.btn-route {
  transition: all 0.3s ease; /* Agregar una transición suave */
}

.btn-route:hover {
  transform: scale(1.1);
}

.container-txt {
  padding: 5%;
  border-radius: 2vw;
  background-color: gainsboro;
}

.txt {
  text-align: justify;
  font-size: 1.2vw;
}

.rounded-btn {
  text-transform: capitalize;
  border-radius: 1.5vw;
  padding: 5%;
  font-weight: bold;
  font-size: 1vw;
  color: white;
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}
</style>

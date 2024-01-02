<template>
  <div style="position: relative; margin-top: 5%">
    <v-row no-gutters>
      <v-col cols="4">
        <img
            class="img"
            src="@/assets/img/protectorDeUnPerrito/cuidado_animal_4.png"
            alt=""
            style="width: 100%"
        />
      </v-col>
      <v-col cols="8">
        <div>
          <div style="margin-bottom: 5%">
            <div style="display: flex; justify-content: center; align-items: center">
              <div
                  style="
                  padding: 1vw 4vw;
                  width:35vw;
                  border-radius: 4vw;
                  background-color: #ffac00;
                  color: white;
                  font-size: 1.2vw;
                  font-weight: bold;"
              >
                <p style="text-align: center">Conviértete en el Protector
                  <br>
                  de un Perrito</p>
              </div>
            </div>
            <div v-if="auto">
              <div style="padding: 0% 5%">
                <div class="container-txt">
                  <p class="txt">
                    Al unirte a este programa tienes la flexibilidad de contribuir mensualmente con la cantidad que esté
                    dentro de tus
                    posibilidades o con el monto completo de $2,500 pesos mexicanos para completar el apadrinamiento de
                    un perrito. Todo suma.
                    Cuando varias personas se unen y sus donaciones mensuales acumuladas alcanzan la suma de $2,500, se
                    convierten en protectores de
                    un adorable perrito. Tu contribución asegura que estos peludos amigos reciban todo lo que necesitan
                    para llevar una vida feliz y
                    saludable mientras esperan encontrar un hogar amoroso.
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
                    <p>Opciones de Donación
                      <br>
                      Personalizada</p>
                  </div>
                </div>
                <div v-if="microsoft">
                  <div style="padding: 0% 5%">
                    <div class="container-txt">
                      <p class="txt">
                        Te damos la libertad de elegir la cantidad que deseas donar mensualmente. Puedes contribuir
                        con cualquier cantidad que esté dentro de tus posibilidades y voluntad de apoyar a nuestros
                        amigos peludos. Cada apoyo, sin importar el monto, nos acerca más a
                        nuestro objetivo de proporcionar cuidado y protección a los perritos necesitados.
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
                    <p>Apadrinamiento por
                      <br>
                      $2,500 pesos</p>
                  </div>
                </div>
                <div v-if="micro">
                  <div style="padding: 0% 5%">
                    <div class="container-txt">
                      <p class="txt">
                        Cuando las donaciones mensuales acumuladas para un perrito alcanzan la suma de $2,500 pesos
                        mexicanos, ese perrito se convierte oficialmente en el beneficiario de un apadrinamiento. Esto
                        significa que el perrito recibe todos los beneficios del programa,
                        incluyendo alimentación, atención médica, amor y preparación para la adopción </p>
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



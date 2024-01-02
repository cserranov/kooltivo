<template>
  <div id="nuestro_equipo">
    <v-row no-gutters>
      <v-col cols="12" class="text-star">
        <div class="container-title">
          <p class="title">
            Nuestro <span style="color: #0561a8">equipo</span>
          </p>
          <p class="text" style="margin-bottom: 3vw">
            Nuestro equipo está compuesto por profesionales apasionados y
            comprometidos con nuestra causa, por personas que creen y promueven
            el desarrollo de habilidades digitales con el ánimo de fomentar la
            igualdad de oportunidades y el progreso social.
          </p>
          <p class="text">
            Contamos con expertos en educación tecnológica, finanzas, género, y
            derechos de los animales, que trabajan en colaboración para
            desarrollar programas educativos y actividades transformadoras y
            efectivas. Además, nos apoyamos en voluntarios dedicados que
            comparten nuestra visión y contribuyen con sus habilidades y tiempo,
            gracias a lo cual perdura nuestro ciclo de vida y nos permite seguir
            cosechando frutos en la sociedad.
          </p>
        </div>
      </v-col>

      <v-col cols="12" id="colaboradores">
        <div class="container-text-img">
          <v-row>
            <v-col cols="4" style="position: relative">
              <div class="container-text-equipo">
                <p class="title-equipo">
                  NORBERTO MALDONADO
                  <br/>
                  Fundador
                </p>
              </div>
              <div class="container-img desktop">
                <img
                    class="img"
                    id="nor"
                    src="@/assets/img/about/NM0_BN.png"
                    alt=""
                    @click="navigateToMaldonado()"
                />

              </div>

              <div class="container-img-movil movil">
                <img
                    class="img"
                    id="nor"
                    src="@/assets/img/about/nm_movil.png"
                    alt=""
                    @click="navigateToMaldonado()"
                />
              </div>
              <div style="padding: 5%; text-align: center">
                <v-btn
                    class="rounded-btn"
                    variant="outlined"
                    @click="navigateToMaldonado()"
                >
                  SABER MÁS
                </v-btn>
              </div>
            </v-col>

            <v-col cols="4" style="position: relative">
              <div class="container-text-equipo">
                <p class="title-equipo">
                  MARLENE MIZRAHI
                  <br/>
                  Directora
                </p>
              </div>
              <div class="container-img desktop">
                <img
                    id="mar"
                    class="img"
                    src="@/assets/img/about/MARLENE_BN.png"
                    alt=""
                    @click="navigateToMizrahi()"
                />
              </div>
              <div class="container-img-movil movil">
                <img
                    id="mar"
                    class="img"
                    src="@/assets/img/about/mar_movil.png"
                    alt=""
                    @click="navigateToMizrahi()"
                />
              </div>
              <div style="padding: 5%; text-align: center">
                <v-btn
                    class="rounded-btn"
                    variant="outlined"
                    @click="navigateToMizrahi()"
                >
                  SABER MÁS
                </v-btn>
              </div>
            </v-col>
            <v-col cols="4" style="position: relative">
              <div class="container-text-equipo">
                <p class="title-equipo">
                  ILAN CARRILLO
                  <br/>
                  Coordinador
                </p>
              </div>
              <div class="container-img desktop">
                <img
                    class="img"
                    id="ilan"
                    src="@/assets/img/about/ILAN_BN.png"
                    alt=""
                    @click="navigateToCarrillo()"
                />
              </div>
              <div class="container-img-movil movil">
                <img
                    class="img"
                    id="ilan"
                    src="@/assets/img/about/ilan_movil.png"
                    alt=""
                    @click="navigateToCarrillo()"
                />
              </div>
              <div style="padding: 5%; text-align: center">
                <v-btn
                    class="rounded-btn"
                    variant="outlined"
                    @click="navigateToCarrillo()"
                >
                  SABER MÁS
                </v-btn>
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
  methods: {
    navigateToCarrillo() {
      this.$router.push("/collaborators/carrillo");
    },
    navigateToMaldonado() {
      this.$router.push("/collaborators/maldonado");
    },
    navigateToMizrahi() {
      this.$router.push("/collaborators/mizrahi");
    },
  },
};
</script>
<style scoped>
.desktop {
  display: block
}

.movil {
  display: none
}

.rounded-btn {
  border-radius: 3vw;
  padding: 1vw 2vw;
  font-weight: bold;
  font-size: 1.3vw;
  border: 1px solid black;
  color: white;
  background-color: black;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}

.container-title {
  padding: 4vw 12vw;

}

.title {
  font-size: 3.5vw;
  font-weight: bold;
}

.text {
  font-size: 2.3vw;
  text-align: justify;
}

.container-text-img {
  background-color: gainsboro;
  padding: 4vw 10vw 8vw;
  border-top-left-radius: 5vw;
  border-top-right-radius: 5vw;
}

.container-text-equipo {
  padding: 2vw;
  text-align: center;
}

.container-img {
  position: relative;
  display: inline-block;
}

.img {
  width: 100%;
}

.title-equipo {
  font-size: 1.1vw;
  font-weight: bold;
}

.container-img img {
  display: block;
  transition: all 0.3s ease; /* Agregar una transición suave */
}

.container-img #ilan:hover {
  content: url("@/assets/img/about/ILAN_COLOR.png");
  transform: scale(1.1); /* Opcional: aplicar un efecto de escala en hover */
}

.container-img #nor:hover {
  content: url("@/assets/img/about/NM_COLOR.png");
  transform: scale(1.1); /* Opcional: aplicar un efecto de escala en hover */
}

.container-img #mar:hover {
  content: url("@/assets/img/about/MARLENE_COLOR.png");
  transform: scale(1.1); /* Opcional: aplicar un efecto de escala en hover */
}


@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }

}
</style>

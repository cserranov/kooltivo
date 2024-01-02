<template>
  <div>
    <div class="overlay-div" id="nuestra_vision">
      <v-row no-gutters>
        <v-col cols="12" class="text-end">
          <div class="container-title">
            <p class="title">
              Nuestra <span style="color: #ffac00">visión</span>
            </p>
          </div>
        </v-col>
        <v-col cols="12">
          <div class="container-text-img">
            <v-row no-gutters>
              <v-col
                  cols="5"
                  style="
                  display: flex;
                  justify-content: center;
                  align-items: center;
                "
              >
                <div class="container-img">
                  <img src="@/assets/img/about/about.png" alt=""/>
                </div>
              </v-col>
              <v-col cols="7">
                <div class="container-text">
                  <p class="text" style="margin-bottom: 3vw">
                    Nuestra visión es crear un futuro en el que todas las
                    personas tengan acceso igualitario a la educación
                    tecnológica, se desarrollen y crezcan en el mundo laboral
                    digital.

                  </p>
                  <p class="text" style="margin-bottom: 3vw">
                    Buscamos que la tecnología se utilice para acercar temas de
                    beneficio social y nutra a una sociedad donde la educación
                    financiera sea una habilidad básica para todos, la igualdad
                    de género sea una realidad y los derechos de los animales
                    sean respetados y protegidos.

                  </p>
                  <p class="text">
                    A través de nuestra labor, esperamos estimular el cambio
                    social y contribuir a un mundo más equitativo, consciente e
                    innovador.
                  </p>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container-title {
  padding: 2vw 8vw;
}

.title {
  font-size: 3.5vw;
  font-weight: bold;
}

.container-text-img {
  background-color: gainsboro;
  padding: 2.5vw;
}

.container-img img {
  width: 100%;
}

.container-text {
  padding: 3vw;
}

.text {
  font-size: 2.3vw;
  text-align: justify;
}


</style>

<template>
  <div class="container-main">
    <div class="container-gray">
      <v-row no-gutters>
        <v-col cols="12">
          <div>
            <p class="title">Nuestra historia</p>
          </div>
        </v-col>
        <v-col cols="12">
          <div class="container-subtitle">
            <p class="subtitle">
              fundación KOOLTIVO, cultivando la educación de México
            </p>
          </div>
        </v-col>
        <v-col cols="12">
          <div class="container-text">
            <p class="text" style="margin-bottom: 3vw">
              En el año 2022, nació una iniciativa con un claro propósito:
              aprovechar los avances tecnológicos para generar igualdad de
              oportunidades y ayudar a las personas a sacar su máximo potencial.
            </p>

            <p class="text" style="margin-bottom: 3vw">
              Esta visión fue lo que sembró la creación de
              <span style="font-weight: bolder"
              >KO<span style="color: #0561a8">O</span>LTIVO</span
              >, una organización sin fines de lucro con el firme compromiso de
              devolver a México las oportunidades que su fundador
              <span style="font-weight: bolder">Norberto Maldonado</span>, ha
              recibido a lo largo de su vida, oportunidades que lo han llevado a
              ser un experto y apasionado del campo tecnológico.
            </p>

            <p class="text">
              <span style="font-weight: bolder"
              >KO<span style="color: #0561a8">O</span>LTIVO</span
              >
              fue una semilla en la mente de un experto en tecnología, cuya
              trayectoria profesional lo han llevado a ser partícipe de
              importantes avances del campo de la innovación, al tiempo que ha
              adquirido un entendimiento profundo del mismo. Consiente de que no
              todas las personas tienen acceso a las herramientas y
              conocimientos necesarios para aprovechar al máximo su
              potencial, Norberto decidió canalizar su pasión y conocimientos en
              una causa con impacto significativo: acerca la educación
              tecnológica a más personas y otras áreas clave para su desarrollo
              personal.
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div class="overlay-div"></div>
  </div>
</template>

<style scoped>
.container-main {
  padding: 4vw 10vw 0vw;
  position: relative;

}

.container-gray {
  border-top-left-radius: 2vw;
  border-top-right-radius: 2vw;
  padding: 2vw;
  background-color: gainsboro;

}

.title {
  font-size: 3.5vw;
  font-weight: bold;
}

.container-subtitle {
  margin-top: 1.5vw;
}

.subtitle {
  font-size: 2vw;
  font-weight: bolder;
}

.container-text {
  padding: 2.5vw 8vw;
}

.text {
  font-size: 1.8vw;
  text-align: justify;
}

.overlay-div {
  position: absolute;
  top: 62%;
  background-color: rgba(128, 128, 128, 0.5);
  width: 100%;
  height: 33%;
  left: 0%;
}


</style>

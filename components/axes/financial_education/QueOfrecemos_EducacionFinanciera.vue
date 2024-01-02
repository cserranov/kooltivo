<template>
  <div style="margin-top: 4%; margin-bottom: 4%">
    <div class="image-container">
      <img
          src="@/assets/img/educacionFinanciera/banner.png"
          alt=""
          style="width: 100%; height: 100%"
      />
      <div class="overlay-div">
        <v-row no-gutters class="justify-center align-center">
          <v-col cols="12" class="text-center">
            <div>
              <p class="title">
                ¿Qué <span class="title_color">ofrecemos</span>?
              </p>
              <p class="text" style="text-align: center">
                Brindamos capacidades que te permitan una toma de decisiones
                informada, fomentando a que saques el mayor provecho de tus
                servicios.
              </p>
            </div>
          </v-col>
        </v-row>
      </div>
    </div>
  </div>
</template>

<style scoped>
.image-container {
  width: 100%;
  position: relative;
}

.overlay-div {
  border-radius: 2vw;
  position: absolute;
  top: 10%;
  right: 5%;
  width: 41%;
  height: 40%;
  padding: 3%;
  background: rgba(0, 0, 0, 0.5);

}

.title {
  font-size: 3.5vw;
  color: white;
  font-weight: bold;
}

.title_color {
  color: orange;
}

.text {
  font-size: 1.8vw;
  color: white;
}


</style>

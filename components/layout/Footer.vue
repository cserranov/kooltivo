<template>
  <div class="container-main">
    <div style="width: 100%; height: 20%"></div>
    <div
      style="width: 100%; height: 80%; background-color: black; color: white"
    ></div>
    <div style="width: 100%; height: 100%; position: absolute; top: 0%">
      <div style="width: 100%; height: 70%; position: relative">
        <img
          src="@/assets/img/Pagkooltivo2-24.png"
          alt=""
          style="width: 100%; height: 100%"
        />
        <v-row style="position: absolute; top: 0%; width: 100%; height: 100%">
          <v-col
            cols="6"
            style="
              display: flex;
              justify-content: center;
              align-items: center;
              width: 100%;
              height: 100%;
            "
          >
            <p class="title" @click="navigateTo('/contactanos')">
              ÚNETE A NOSOTROS
            </p>
          </v-col>
          <v-col
            cols="6"
            style="
              display: flex;
              justify-content: center;
              align-items: center;
              width: 100%;
              height: 100%;
            "
          >
            <v-btn
              class="rounded-btn"
              variant="outlined"
              @click="navigateTo('/contactanos')"
            >
              Contáctanos
            </v-btn>
          </v-col>
        </v-row>
      </div>
      <div
        style="
          color: black;
          width: 100%;
          height: 30%;
          display: flex;
          justify-content: flex-end;
          align-items: center;
        "
      >
        <img
          src="@/assets/img/Pagkooltivo2-03.png"
          alt="logo-kooltivo"
          class="img"
          style="height: 100%"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-main {
  width: 100%;
  height: 13vw;
  position: relative;
}

.title {
  color: white;
  font-size: 1.8vw;
  font-weight: bold;
}

.rounded-btn {
  border-radius: 1vw;
  padding: 3% 5%;
  font-weight: bold;
  font-size: 0.8vw;
  border: 1px solid white;
  color: white;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}
</style>

<template>
  <div>
    <v-row no-gutters class="justify-center align-center">
      <v-col
        cols="12"
        style="
          display: flex;
          justify-content: center;
          align-items: center;
          margin-bottom: 5%;
        "
      >
        <div style="flex: 1; text-align: end">
          <p style="font-size: 2.5vw">¿Qué es kooltivo?</p>
        </div>

        <div style="flex: 3">
          <img
            src="@/assets/img/linea_gris_ejes.png"
            alt=""
            style="width: 100%"
          />
        </div>
      </v-col>
      <v-col cols="12" class="text-center">
        <video class="video-element" controls autoplay muted>
          <source src="@/assets/videos/nota_1.mp4" type="video/mp4" />
        </video>
      </v-col>
    </v-row>
  </div>
</template>

<style scoped>
.video-element {
  width: 100%;
}
</style>

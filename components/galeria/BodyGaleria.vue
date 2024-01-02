<template>
  <v-container style="margin-top: 5%">
    <v-row no-gutters>
      <v-col cols="12" sm="6">
        <v-carousel hide-delimiters>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/1.jpg"
              cover
          ></v-carousel-item>

          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/2.jpg"
              cover
          ></v-carousel-item>


          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/4.jpg"
              cover
          ></v-carousel-item>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/5.jpg"
              cover
          ></v-carousel-item>

        </v-carousel>
      </v-col>
      <v-col cols="12" sm="6">
        <v-carousel hide-delimiters>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/7.jpg"
              cover
          ></v-carousel-item>

          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/15.jpg"
              cover

          ></v-carousel-item>

          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/8.jpg"
              cover
          ></v-carousel-item>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/9.jpg"
              cover
          ></v-carousel-item>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/10.jpg"
              cover
          ></v-carousel-item>
        </v-carousel>
      </v-col>
      <v-col cols="12" sm="6">
        <v-row no-gutters>
          <v-col cols="12" sm="6">
            <v-carousel hide-delimiters>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/3.jpg"

              ></v-carousel-item>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/16.jpg"

              ></v-carousel-item>





              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/19.jpg"

              ></v-carousel-item>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/20.jpg"

              ></v-carousel-item>

            </v-carousel>
          </v-col>
          <v-col cols="12" sm="6">
            <v-carousel hide-delimiters>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/6.jpg"

              ></v-carousel-item>

              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/12.jpg"

              ></v-carousel-item>

              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/13.jpg"

              ></v-carousel-item>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/14.jpg"

              ></v-carousel-item>
              <v-carousel-item
                  src="https://aad8012.github.io/imagenes/img/11.jpg"

              ></v-carousel-item>
            </v-carousel>
          </v-col>
        </v-row>

      </v-col>
      <v-col cols="12" sm="6">
        <v-carousel hide-delimiters>
          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/17.jpg"
              cover
          ></v-carousel-item>



          <v-carousel-item
              src="https://aad8012.github.io/imagenes/img/18.jpg"
              cover
          ></v-carousel-item>

        </v-carousel>
      </v-col>


    </v-row>
  </v-container>
</template>

<!-- <div style="display: flex; justify-content: center; align-items: center">
    <div style="width: 50%">
      <v-carousel hide-delimiters>
        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
    </div>
  </div>
  <div style="display: flex; justify-content: center; align-items: center">
    <div style="width: 50%">
      <v-carousel hide-delimiters>
        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
    </div>
  </div>
  <div style="display: flex; justify-content: center; align-items: center">
    <div style="width: 50%">
      <v-carousel hide-delimiters>
        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/hotel.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
    </div>
  </div> -->

<style scoped>
.mosaic-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 10px; /* Espacio entre las imágenes */
}

.mosaic-item {
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #f0f0f0; /* Color de fondo para el espacio vacío entre las imágenes */
  border: 1px solid #ccc; /* Borde opcional */
}

.mosaic-image {
  max-width: 100%;
  max-height: 100%;
  object-fit: cover;
  object-position: center;
}
</style>
<script setup lang="ts">
</script>
<template>
  <div class="image-container">
    <v-row no-gutters class="justify-center align-center">
      <v-col cols="6" class="text-center">
        <h2 class="title">ÚNETE A NOSOTROS</h2>
      </v-col>
      <v-col cols="6" class="text-center">
        <v-btn class="rounded-btn" variant="outlined"> Contáctanos </v-btn>
      </v-col>
    </v-row>
  </div>
  <div>
    <v-row no-gutters class="justify-center align-center">
      <v-col cols="12" class="text-center">
        <div class="container-footer">
          <p class="title_2">
            "Empoderando a través del conocimiento: educación tecnologica,
            educación financiera, equidad de género y conciencia de cuidado
            animal"
          </p>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<style scoped>
.image-container {
  width: 100%;
  height: 197px;
  background-image: url(/_nuxt/assets/img/Pagkooltivo2-24.png);
  background-size: cover;
  padding-top: 70px;
}

.title {
  color: white;
  font-weight: bold;
  font-size: 40px;
}

.rounded-btn {
  border-radius: 50px;
  padding: 35px;
  font-weight: bold;
  font-size: 20px;
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

.container-footer {
  background-color: black;
  height: 100px;
  padding: 30px;
}

.title_2 {
  color: white;
  font-size: 27px;
  font-weight: lighter;
}

@media (max-width: 1440px) {
  .image-container {
    width: 100%;
    height: 140px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 40px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 27px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 15px;
    font-weight: bold;
    font-size: 23px;
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
}

@media (max-width: 1024px) {
  .image-container {
    width: 100%;
    height: 110px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 30px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 20px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 10px;
    font-weight: bold;
    font-size: 17px;
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
}

@media (max-width: 768px) {
  .image-container {
    width: 100%;
    height: 95px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 25px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 15px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 7px;
    font-weight: bold;
    font-size: 12px;
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
}

@media (max-width: 425px) {
  .image-container {
    width: 100%;
    height: 50px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 10px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 10px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 7px;
    font-weight: bold;
    font-size: 7px;
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
}

@media (max-width: 375px) {
  .image-container {
    width: 100%;
    height: 40px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 7px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 8px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 4px;
    font-weight: bold;
    font-size: 6px;
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
}

@media (max-width: 322px) {
  .image-container {
    width: 100%;
    height: 35px;
    background-image: url(../assets/img/Pagkooltivo2-24.png);
    background-size: contain;
    padding-top: 4px;
  }

  .title {
    color: white;
    font-weight: bold;
    font-size: 7px;
  }

  .rounded-btn {
    border-radius: 5px;
    padding: 4px;
    font-weight: bold;
    font-size: 5px;
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
}
</style>

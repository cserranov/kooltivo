<template>
  <div id="quienesSomos" class="container-main" style="margin-top: 4%">
    <v-row
      class="align-center"
      style="text-align: center; width: 100%; height: 100%"
    >
      <v-col
        cols="12"
        style="
          width: 100%;
          height: 25%;
          display: flex;
          justify-content: center;
          align-items: center;

          padding: 2% 0% 0%;
        "
      >
        <p class="title">¿Quiénes Somos?</p>
      </v-col>
      <v-col
        class="container-text"
        cols="12"
        style="display: flex; justify-content: center; align-items: center"
      >
        <div>
          <p class="text">
            Somos un grupo de personas que creemos y promovemos el desarrollo de
            habilidades digitales para avivar la igualdad de oportunidades y el
            progreso social.
          </p>
          <br />
          <p class="text">
            Juntos, conformamos una fundación empresarial y sin fines de lucro
            que obra en favor de la equidad de género y la conciencia sobre los
            derechos de los animales.
          </p>
        </div>
      </v-col>
      <v-col
        cols="12"
        style="
          width: 100%;
          height: 25%;
          display: flex;
          justify-content: center;
          align-items: center;

          padding: 0% 0% 2%;
        "
      >
        <v-btn
          class="rounded-btn"
          variant="outlined"
          @click="navigateTo('/about#colaboradores')"
        >
          SABER MÁS
        </v-btn>
      </v-col>
    </v-row>
  </div>
</template>
<script>
export default {
  methods: {
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>
<style scoped>
.container-main {
  background-color: #f7f7f7;
  border-radius: 70px;
  height: 70vh;
  width: 100%;
}
.title {
  font-size: 50px;
  font-weight: bold;
}
.text {
  font-size: 25px;
  text-align: justify;
}
.container-text {
  text-align: center;
  padding: 1% 27%;
  width: 100%;
  height: 50%;
}
.rounded-btn {
  border-radius: 20px;
  padding: 15px;
  font-size: 15px;
  border: 1px solid black;
  color: black;
  text-transform: uppercase;
  font-weight: bold;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
  color: white;
}
.rounded-btn.v-btn--density-default {
  height: auto;
}

@media (max-width: 1440px) {
  .container-main {
    border-radius: 70px;
    height: 60vh;
  }
  .title {
    font-size: 40px;
  }
  .container-text {
    text-align: center;
    width: 100%;
    height: 50%;
  }
  .text {
    font-size: 20px;
  }
  .rounded-btn {
    border-radius: 20px;
    padding: 15px;
    font-size: 13px;
    font-weight: bold;
  }
}
@media (max-width: 1024px) {
  .container-main {
    border-radius: 70px;
    height: 50vh;
  }
  .title {
    font-size: 35px;
  }
  .container-text {
    text-align: center;

    width: 100%;
    height: 50%;
  }
  .text {
    font-size: 15px;
  }
  .rounded-btn {
    border-radius: 20px;
    padding: 15px;
    font-size: 10px;
    font-weight: bold;
  }
}
@media (max-width: 768px) {
  .container-main {
    border-radius: 70px;
    height: 40vh;
  }
  .title {
    font-size: 25px;
  }
  .container-text {
    text-align: center;

    width: 100%;
    height: 50%;
  }
  .text {
    font-size: 11px;
  }
  .rounded-btn {
    border-radius: 20px;
    padding: 15px;
    font-size: 8px;
    font-weight: bold;
  }
  @media (max-width: 425px) {
    .container-main {
      border-radius: 40px;
      height: 40vh;
    }
    .title {
      font-size: 20px;
    }
    .container-text {
      text-align: center;
      padding: 10% 15%;

      width: 100%;
      height: 50%;
    }
    .text {
      font-size: 11px;
    }
    .rounded-btn {
      border-radius: 20px;
      padding: 15px;
      font-size: 8px;
      font-weight: bold;
    }
  }
  @media (max-width: 375px) {
    .container-main {
      border-radius: 40px;
      height: 50vh;
    }
    .title {
      font-size: 20px;
    }
    .container-text {
      text-align: center;
      padding: 10% 15%;

      width: 100%;
      height: 50%;
    }
    .text {
      font-size: 11px;
    }
    .rounded-btn {
      border-radius: 20px;
      padding: 15px;
      font-size: 8px;
      font-weight: bold;
    }
  }
  @media (max-width: 320px) {
    .container-main {
      border-radius: 40px;
      height: 45vh;
    }
    .title {
      font-size: 20px;
    }
    .container-text {
      text-align: center;
      padding: 10%;

      width: 100%;
      height: 50%;
    }
    .text {
      font-size: 11px;
    }
    .rounded-btn {
      border-radius: 20px;
      padding: 15px;
      font-size: 8px;
      font-weight: bold;
    }
  }
}
</style>

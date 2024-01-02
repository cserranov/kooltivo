<template>
  <div class="desktop "

       style="width: 100%; background-color: #f2f2f2;  padding: 5% 0% ">
    <v-row
        no-gutters
    >
      <v-col
          sm="6"
          cols="12"
          style="
          display: flex;
          justify-content: center;
          align-items: center;
        "
      >
        <div style="text-align: center">
          <p style="font-weight: bold;" class="title">SOMOS KOOL</p>
          <img src="@/assets/img/puntos.png" alt="" style="width: 50%"/>
        </div>

      </v-col>

      <v-col
          sm="6"
          cols="12"
          style="
          display: flex;
          justify-content: center;
          align-items: center;


        "
      >
        <div style=" text-align: center; " class="container-text">
          <p style="text-align: justify; margin-bottom: 5%" class="text">
            Creemos que con la tecnología podemos cultivar un mejor presente y
            futuro.
          </p>
          <v-btn
              class="rounded-btn"
              variant="outlined"
              @click="navigateTo('/about')"
          >
            SABER MÁS
          </v-btn>
        </div>
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
.desktop {
  margin-top: 5%
}


.title {
  font-size: 2.5vw
}

.container-text {
  width: 50%
}

.text {
  font-size: 1.5vw;
}

.rounded-btn {
  border-radius: 1.5vw;
  padding: 1vw;
  font-weight: bold;
  font-size: .9vw;
  border: 1px solid black;
  color: black;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
  color: white;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}


@media (max-width: 600px) {
  .desktop {
    margin-top: 10%
  }

  .title {
    font-size: 4vw
  }

  .container-text {
    width: 50%;
    margin-top: 5%;
  }

  .text {
    font-size: 3vw;
  }

  .rounded-btn {
    border-radius: 4vw;
    padding: 2vw;
    font-weight: bold;
    font-size: 2vw;
    border: 1px solid black;
    color: black;
  }

}


</style>

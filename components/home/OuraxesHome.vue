<template>
  <div style="margin-top: 5%" id="nuestrosEjes" class="desktop">
    <v-row no-gutters>
      <v-col
        cols="12"
        style="display: flex; justify-content: center; align-items: center"
      >
        <div style="flex: 1; text-align: end">
          <p style="font-size: 2.5vw">Nuestros Ejes</p>
        </div>

        <div style="flex: 4">
          <img
            src="@/assets/img/linea_gris_ejes.png"
            alt=""
            style="width: 100%"
          />
        </div>
      </v-col>
      <v-col
        cols="7"
        style="
          position: relative;
          padding: 5% 2% 5% 5%;
          display: flex;
          justify-content: center;
          align-items: center;
        "
      >
        <img
          src="@/assets/img/Pag_kooltivo13.png"
          alt=""
          style="width: 100%"
          @click="navigateTo('/ejes/educacion_tecnologica')"
        />
        <div
          style="
            position: absolute;
            top: 15%;
            right: 3%;
            background-color: #613683;
            padding: 3%;
            color: white;
            font-size: 1.5vw;
            border-radius: 1vw;
          "
          class="btn-route"
          @click="navigateTo('/ejes/educacion_tecnologica')"
        >
          <p>EDUCACIÓN TECNOLÓGICA</p>
        </div>
      </v-col>
      <v-col
        cols="5"
        style="
          padding: 5% 5% 5% 2%;
          display: flex;
          justify-content: center;
          align-items: center;
        "
      >
        <v-row no-gutters>
          <v-col cols="12" style="position: relative">
            <img
              src="@/assets/img/Pag_kooltivo-17.png"
              alt=""
              style="width: 50%"
              @click="navigateTo('/ejes/educacion_financiera')"
            />

            <div
              style="
                position: absolute;
                top: 40%;
                right: 0%;
                background-color: #ffac00;
                width: 70%;
                padding: 3% 0%;
                color: white;
                font-size: 1.5vw;
                border-radius: 1vw;
                text-align: center;
              "
              class="btn-route"
              @click="navigateTo('/ejes/educacion_financiera')"
            >
              <p>EDUCACIÓN FINANCIERA</p>
            </div>
          </v-col>

          <v-col cols="12" style="position: relative">
            <img
              src="@/assets/img/Pagkooltivo2-16.png"
              alt=""
              style="width: 50%"
              @click="navigateTo('/ejes/cuidado_animal')"
            />

            <div
              style="
                position: absolute;
                top: 40%;
                right: 0%;
                background-color: #84c5c9;
                width: 70%;
                padding: 3% 0%;
                color: white;
                font-size: 1.5vw;
                border-radius: 1vw;
                text-align: center;
              "
              class="btn-route"
              @click="navigateTo('/ejes/cuidado_animal')"
            >
              <p>CUIDADO ANIMAL</p>
            </div>
          </v-col>
          <v-col cols="12" style="position: relative">
            <img
              src="@/assets/img/Pag_kooltivo-16.png"
              alt=""
              style="width: 50%"
              @click="navigateTo('/ejes/equidad_de_genero')"
            />

            <div
              style="
                position: absolute;
                top: 40%;
                right: 0%;
                background-color: #d882af;
                width: 70%;
                padding: 3% 0%;
                color: white;
                font-size: 1.5vw;
                text-align: center;
                border-radius: 1vw;
              "
              @click="navigateTo('/ejes/equidad_de_genero')"
              class="btn-route"
            >
              <p>EQUIDAD DE GÉNERO</p>
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>

  <div style="margin-top: 5%" id="nuestrosEjes" class="mobile">
    <v-row no-gutters>
      <v-col
        cols="12"
        style="display: flex; justify-content: center; align-items: center"
      >
        <div style="flex: 1; text-align: end">
          <p style="font-size: 4vw">Nuestros Ejes</p>
        </div>

        <div style="flex: 2">
          <img
            src="@/assets/img/linea_gris_ejes.png"
            alt=""
            style="width: 100%"
          />
        </div>
      </v-col>
      <v-col cols="12" style="position: relative; padding: 10% 10% 0% 10%">
        <img
          src="@/assets/img/Pag_kooltivo13.png"
          alt=""
          style="width: 60%"
          @click="navigateTo('/ejes/educacion_tecnologica')"
        />
        <div
          style="
            position: absolute;
            bottom: 30%;
            right: 5%;
            background-color: #613683;
            padding: 3%;
            color: white;
            font-size: 3vw;
            border-radius: 1vw;
            width: 50%;
          "
          @click="navigateTo('/ejes/educacion_tecnologica')"
        >
          <p style="text-align: center">EDUCACIÓN TECNOLÓGICA</p>
        </div>
      </v-col>
      <v-col cols="12" style="position: relative; padding: 0% 10%">
        <img
          src="@/assets/img/Pag_kooltivo-17.png"
          alt=""
          style="width: 60%"
          @click="navigateTo('/ejes/educacion_financiera')"
        />
        <div
          style="
            position: absolute;
            bottom: 30%;
            right: 5%;
            background-color: #ffac00;
            padding: 3%;
            color: white;
            font-size: 3vw;
            border-radius: 1vw;
            width: 50%;
          "
          @click="navigateTo('/ejes/educacion_financiera')"
        >
          <p style="text-align: center">EDUCACIÓN FINANCIERA</p>
        </div>
      </v-col>

      <v-col cols="12" style="position: relative; padding: 0% 10% 0% 10%">
        <img
          src="@/assets/img/Pagkooltivo2-16.png"
          alt=""
          style="width: 60%"
          @click="navigateTo('/ejes/cuidado_animal')"
        />
        <div
          style="
            position: absolute;
            bottom: 30%;
            right: 5%;
            background-color: #84c5c9;
            padding: 3%;
            color: white;
            font-size: 3vw;
            border-radius: 1vw;
            width: 50%;
          "
          @click="navigateTo('/ejes/cuidado_animal')"
        >
          <p style="text-align: center">CUIDADO ANIMAL</p>
        </div>
      </v-col>

      <v-col cols="12" style="position: relative; padding: 0% 10% 10% 10%">
        <img
          src="@/assets/img/Pag_kooltivo-16.png"
          alt=""
          style="width: 60%"
          @click="navigateTo('/ejes/equidad_de_genero')"
        />
        <div
          style="
            position: absolute;
            bottom: 30%;
            right: 5%;
            background-color: #d882af;
            padding: 3%;
            color: white;
            font-size: 3vw;
            width: 50%;
          "
          @click="navigateTo('/ejes/equidad_de_genero')"
        >
          <p style="text-align: center">EQUIDAD DE GÉNERO</p>
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
.btn-route {
  transition: all 0.3s ease; /* Agregar una transición suave */
}

.btn-route:hover {
  transform: scale(1.1);
}

.desktop {
  display: block;
}

.mobile {
  display: none;
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .mobile {
    display: block;
  }
}
</style>

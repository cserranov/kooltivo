<template>
  <div class="container" style="width: 100%; margin-bottom: 5%" id="apadrinamientos">
    <v-row no-gutters class="justify-center align-center" style="width: 100%">
      <v-col cols="4" class="text-center" style="width: 100%">
        <div style="position: relative; width: 100%">
          <img
              class="img"
              src="@/assets/img/cuidado_animal/animal_1.png"
              alt=""
              style="width: 100%"
          />
          <div class="container-uno btn-route" @click="navigateTo('/apadrinamiento_1')">
            <p>Apadrina un perrito</p>
          </div>
        </div>
      </v-col>

      <v-col cols="4" class="text-center" style="width: 100%">
        <div style="position: relative; width: 100%">
          <img
              class="img"
              src="@/assets/img/cuidado_animal/animal_3.png"
              alt=""
              style="width: 100%"
          />
          <div class="container-dos btn-route" @click="navigateTo('/segunda_oportunidad')">
            <p>Segunda oportunidad para un perrito mayor</p>
          </div>
        </div>
      </v-col>

      <v-col cols="4" class="text-center" style="width: 100%">
        <div style="position: relative; width: 100%">
          <img
              class="img"
              src="@/assets/img/cuidado_animal/animal_2.png"
              alt=""
              style="width: 100%"
          />
          <div class="container-uno btn-route" @click="navigateTo('/adopcion')">
            <p>Adopción</p>
          </div>
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
.container-dos:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.container-uno:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.container-uno {
  position: absolute;
  bottom: 0%;
  left: 10%;
  width: 80%;
  height: 20%;
  background-color: #005772;
  border-radius: 5vw;
  color: white;
  font-size: 1.5vw;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container-dos {
  position: absolute;
  bottom: 0%;
  left: 10%;
  width: 80%;
  height: 20%;
  background-color: #005772;
  border-radius: 5vw;
  color: white;
  font-size: 1.5vw;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10%;
  line-height: 0.8;
}


.container {
  padding: 5%;
}

.img {
  width: 100%;
}


</style>

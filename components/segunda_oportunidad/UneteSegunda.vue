<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
        src="@/assets/img/perrito_mayor/unete.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div style="position: absolute; top: 48%; left: 10%; width: 80%">
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p class="txt" style="margin-bottom: 5%">
              Unirte al programa
              <span style="font-weight: bold"
                >"Segunda Oportunidad para un Perro Mayor"</span
              >
              te da la oportunidad de cultivar una mejor vida para un perro en
              edad adulta. Tu contribución, ya sea grande o pequeña, marca la
              diferencia al darles a estos perritos una segunda oportunidad para
              vivir sus últimos años con dignidad y amor; así como la
              oportunidad de ser adoptados por una familia comprometida.
            </p>
            <p class="txt" style="margin-bottom: 5%">
              <span
                >De parte de Kooltivo, te damos las gracias por considerar
                unirte a esta misión de cuidado y compasión hacia estos
                compañeros caninos mayores. Juntos, estamos haciendo posible que
                vivan sus años dorados con alegría y satisfacción.
              </span>
            </p>
            <p class="txt">
              <span style="font-weight: bold"
                >¡Únete a nosotros en esta hermosa causa y sé un héroe para los
                perritos mayores!</span
              >
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
    <div style="position: absolute; top: 18%; left: 5%; width: 80%">
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p style="color: black; font-size: 2.5vw">
              <span style="font-weight: bold"
                >Únete a Esta Misión de Cuidado y Compasión</span
              >
            </p>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 5%;
  position: relative;
  width: 100%;
}

.title {
  padding: 1% 2% 1%;
  font-size: 4vw;
  color: white;
  font-weight: bold;
}

.txt {
  color: white;
  font-size: 1.5vw;
  text-align: justify;
}

.custom-list-item {
  color: #ffac00; /* Cambia el color al que desees, por ejemplo, rojo */
  font-size: 1.5vw;
}
</style>
<script setup lang="ts"></script>

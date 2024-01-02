<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
        src="@/assets/img/protectorDeUnPerrito/cuidado_animal_2.png"
        alt=""
        style="width: 100%; height: 100%"
      />
    </div>
    <div style="position: absolute; top: 15%; right: 0%; width: 60%">
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div style="padding: 0% 2%">
            <p class="title">El Cuidado y Atención que Proporcionamos</p>
            <p class="txt">
              Tu apoyo mensual completo o combinado con el de otros donantes,
              permite que estos perritos mayores reciban:
            </p>
          </div>
        </v-col>
        <v-col cols="12">
          <div style="padding: 1% 5%">
            <ul>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold"
                    >Cuidado de salud completo</span
                  >: Nuestros perritos mayores reciben atención veterinaria
                  regular, medicamentos si es necesario y un plan de bienestar
                  diseñado específicamente para sus necesidades.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Alimentación nutritiva</span>:
                  Proporcionamos una dieta equilibrada y adecuada para su edad,
                  asegurando que estén saludables y felices.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold"
                    >Preparación para la adopción</span
                  >: Reconocemos que adoptar a un perrito mayor es un compromiso
                  especial, por eso trabajamos arduamente y preparamos una
                  campaña especializada para encontrar hogares amorosos que
                  estén dispuestos a ofrecerles la atención que necesitan.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Comodidad y amor</span>: Les
                  ofrecemos un ambiente cálido y amoroso, rodeados de cuidadores
                  compasivos que les brindan atención individualizada.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold"
                    >Conexión personalizada y progreso compartido</span
                  >: Como donante, también tendrás la oportunidad de conectar
                  con el perrito mayor apadrinado y recibirás actualizaciones
                  mensuales, incluyendo fotos y noticias sobre su progreso.
                  Verás cómo tu apoyo les cambia la vida y les permite vivir sus
                  años de madurez con alegría y satisfacción.
                </p>
              </div>
            </ul>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<style scoped>
.container {
  margin-top: 1%;
  position: relative;
  width: 100%;
}

.title {
  padding: 1% 2% 1%;
  font-size: 2.5vw;
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

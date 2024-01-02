<template>
  <div class="container">
    <div style="width: 100%; height: 100%">
      <img
          src="@/assets/img/protectorDeUnPerrito/cuidado_animal_2.png"
          alt=""
          style="width: 100%; height: 100%"
      />
    </div>
    <div
        style="
        position: absolute;
        top: 20%;
        right: 0%;
        width: 60%;
        overflow: hidden;
      "
    >
      <v-row no-gutters>
        <v-col cols="12" class="text-star">
          <div>
            <p class="title">Cómo Puedes Ayudar</p>
          </div>
        </v-col>
        <v-col cols="12">
          <div style="padding: 1% 5%">
            <ul>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Adopta, no compres</span>: Si estás buscando un nuevo miembro para tu
                  familia, considera la adopción
                  como tu primera opción. Nuestros animales esperan ansiosos un hogar amoroso. Si ya tomaste la decisión
                  de adoptar ¡escríbenos!
                  Te ayudaremos a encontrar al compañero ideal.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Donativos y Voluntariado</span>: Tu contribución financiera o tu
                  tiempo como voluntario son invaluables para
                  continuar nuestra labor. Cada donación nos acerca a la meta de proporcionar a más animales un nuevo
                  comienzo.
                </p>
              </div>
              <div style="display: flex">
                <li class="custom-list-item"></li>
                <p class="txt">
                  <span style="font-weight: bold">Comparte Nuestra Misión</span>: Ayúdanos a difundir la palabra sobre
                  la importancia de la
                  adopción, la esterilización y el cuidado responsable de los animales.
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
<script setup lang="ts">
</script>
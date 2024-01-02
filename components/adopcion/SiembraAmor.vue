<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col
          cols="6"
          style="padding: 3%;display: flex; justify-content: center; align-items: center ">
        <p style="font-size: 3.5vw; font-weight: bold">Siembra <span style="color: #036687">Amor</span><br>
          con Adopción</p>
      </v-col>
      <v-col
          cols="6"
          style="padding: 2%;">
        <p style="font-size: 1.5vw; text-align: justify">Siembra Amor con Adopción
          La Fundación Kooltivo se enorgullece de presentar nuestro programa de adopción "Siembra Amor con Adopción".
          Creemos que todos los animales
          merecen un lugar seguro y lleno de amor que sea su hogar. Por eso, a través de alianzas con varios albergues y
          la realización de jornadas de adopción,
          donativos de comida y campañas de esterilización, estamos comprometidos a hacer que esta visión se convierta
          en una realidad.
        </p>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col
          cols="12"
          style="padding: 5%;display: flex; justify-content: center; align-items: center ">
        <p style="font-size: 4.5vw; font-weight: bold">Siembra <span style="color: #036687">Amor</span>
          con Adopción</p>
      </v-col>
      <v-col
          cols="12"
          style="padding: 5% 10%;">
        <p style="font-size: 3vw; text-align: justify">Siembra Amor con Adopción
          La Fundación Kooltivo se enorgullece de presentar nuestro programa de adopción "Siembra Amor con Adopción".
          Creemos que todos los animales
          merecen un lugar seguro y lleno de amor que sea su hogar. Por eso, a través de alianzas con varios albergues y
          la realización de jornadas de adopción,
          donativos de comida y campañas de esterilización, estamos comprometidos a hacer que esta visión se convierta
          en una realidad.
        </p>
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
    scrollToElement(elemento) {
      // Obten el elemento con el ID "elementoDestino"
      const elementoDestino = document.getElementById(elemento);

      // Verifica si el elemento existe
      if (elementoDestino) {
        // Utiliza el método scrollIntoView para desplazarte al elemento
        elementoDestino.scrollIntoView({behavior: "smooth"}); // Puedes ajustar el comportamiento de desplazamiento según tus preferencias
      }
    },
  },
};
</script>

<style scoped>

.desktop {
  display: block;
}

.movil {
  display: none;
}

.container-main {
  width: 100%;
  margin-top: 5%;
  padding: 3%;
  background-color: gainsboro;
  border-radius: 2vw;
}

ul {
  list-style-type: none; /* Elimina los marcadores de la lista */
  padding-left: 1.2em; /* Espacio para simular el punto (o cualquier otro marcador) */
}

ul li::before {
  content: '\2022'; /* Código del carácter del marcador de lista (punto) */
  color: #ffac00; /* Color del marcador (amarillo en este caso) */
  display: inline-block;
  width: 1.5vw; /* Ajusta el ancho según sea necesario */
  margin-left: -1.2em; /* Alinea el marcador con el texto y ajusta según el padding-left */
}

ul li {
  color: black; /* Color del texto (negro en este caso) */
}


@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }


}

</style>




<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col
        cols="6"
        style="
          padding: 3%;
          display: flex;
          justify-content: center;
          align-items: center;
        "
      >
        <p style="font-size: 3.3vw; font-weight: bold">
          <span style="color: #036687">¡Bienvenidos al Programa</span><br />
          "Segunda Oportunidad para un Perro Mayor"!
        </p>
      </v-col>
      <v-col cols="6" style="padding: 2%">
        <p style="font-size: 1.5vw; text-align: justify">
          En Fundación Kooltivo creemos que todos los perros merecen amor,
          cuidado y un hogar para toda la vida.
        </p>
        <p style="font-size: 1.5vw; text-align: justify">
          “Segunda Oportunidad para un Perro Mayor” es un programa diseñado para
          brindar apoyo y cariño a aquellos perritos que tienen más años de
          vida. Aquellos que cuentan 7 años o más y que, lamentablemente,
          enfrentan mayores dificultades para encontrar un hogar. Descubre cómo
          puedes marcar la diferencia en sus vidas.
        </p>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 3% 7%; text-align: center">
        <p style="font-size: 3.5vw; font-weight: bold">
          <span style="color: #036687">¡Bienvenidos al Programa</span> "Segunda
          Oportunidad para un Perro Mayor"!
        </p>
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 3vw; text-align: justify">
          En Fundación Kooltivo creemos que todos los perros merecen amor,
          cuidado y un hogar para toda la vida.
        </p>
        <p style="font-size: 3vw; text-align: justify">
          “Segunda Oportunidad para un Perro Mayor” es un programa diseñado para
          brindar apoyo y cariño a aquellos perritos que tienen más años de
          vida. Aquellos que cuentan 7 años o más y que, lamentablemente,
          enfrentan mayores dificultades para encontrar un hogar. Descubre cómo
          puedes marcar la diferencia en sus vidas.
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
        elementoDestino.scrollIntoView({ behavior: "smooth" }); // Puedes ajustar el comportamiento de desplazamiento según tus preferencias
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
  content: "\2022"; /* Código del carácter del marcador de lista (punto) */
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

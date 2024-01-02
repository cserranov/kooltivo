<template>
  <div class="container-main desktop">
    <div style="  background-color: gainsboro;
  border-radius: 2vw; padding: 6%">

      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%">
        Este programa no sería posible sin el apoyo y la participación de nuestra comunidad. Cada adopción, donativo de
        comida o
        esterilización es un esfuerzo colectivo que refleja nuestro compromiso compartido con el bienestar animal.
        Juntos, estamos cambiando vidas y
        construyendo un futuro más brillante para los animales necesitados.
      </p>


      <div style="background-color: yellow; width: 20%; text-align: center; padding: 1%; border-radius: 3vw; font-weight: bold; color: white;
font-size: 1.5vw; left: 42%;  top: 0%; position: absolute"><p>Nuestra Comunidad <br>Comprometida</p></div>
    </div>
  </div>

  <div class="container-main movil">
    <div style="  background-color: gainsboro;
  border-radius: 2vw; padding: 15% 5%">

      <p style="font-size: 3vw; text-align: justify; margin-bottom: 2%">
        Este programa no sería posible sin el apoyo y la participación de nuestra comunidad. Cada adopción, donativo de
        comida o
        esterilización es un esfuerzo colectivo que refleja nuestro compromiso compartido con el bienestar animal.
        Juntos, estamos cambiando vidas y
        construyendo un futuro más brillante para los animales necesitados.
      </p>
      <div style="background-color: yellow; width: 40%; text-align: center; padding: 1%; border-radius: 3vw; font-weight: bold; color: white;
font-size: 3.3vw; left: 29%;  top: 0%; position: absolute"><p>Nuestra Comunidad <br>Comprometida</p></div>
    </div>
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
  padding: 2% 6%;

  position: relative;
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




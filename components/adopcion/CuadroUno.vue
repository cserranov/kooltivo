<template>
  <div class="container-main desktop">
    <div style="  background-color: gainsboro;
  border-radius: 2vw; padding: 6%">

      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Nuestra misión es clara</span>:
        encontrar hogares amorosos y
        responsables para cada animal que haya perdido su camino. Trabajamos en estrecha colaboración con albergues y
        refugios asociados para rescatar, rehabilitar y reubicar a animales necesitados. Además, a través de nuestras
        campañas de esterilización,
        buscamos prevenir el sufrimiento innecesario y el crecimiento descontrolado de poblaciones de animales en
        situación de calle.
      </p>
      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">¿Cómo funciona el programa?</span>
      </p>
      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Jornadas de Adopción</span>:
        Nos unimos a la organización regular de jornadas de adopción en colaboración con nuestros albergues
        asociados. Durante estas jornadas, se brindan a las familias la oportunidad de conocer y adoptar a su compañero
        peludo ideal.
        Cada adopción representa una historia de esperanza y un nuevo comienzo para un animal en busca de amor y
        seguridad.
      </p>
      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Donativos de Comida</span>:
        Reconocemos la importancia de asegurar que los animales en albergues y hogares temporales reciban una
        nutrición adecuada. A través de donativos de comida, proporcionamos a nuestros albergues asociados los
        recursos necesarios para mantener a los animales bien alimentados y saludables mientras esperan su adopción.
      </p>
      <p style="font-size: 1.5vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Campañas de Esterilización: </span>:
        Creemos firmemente en la prevención como parte integral de nuestra labor. Por eso, realizamos campañas de
        esterilización con la intención de controlar el
        crecimiento de poblaciones no deseadas y prevenir el sufrimiento de futuros animales en situación de calle.
        Estas campañas son esenciales para
        abordar la raíz del problema y asegurar un mejor futuro para nuestros amigos peludos.
      </p>

      <div style="background-color:  #ffac00; width: 20%; text-align: center; padding: 1%; border-radius: 3vw; font-weight: bold; color: white;
font-size: 1.5vw; left: 42%;  top: 0%; position: absolute"><p>Siembra Amor con <br> Adopción</p></div>
    </div>
  </div>

  <div class="container-main movil">
    <div style="  background-color: gainsboro;
  border-radius: 2vw; padding: 15% 5%">

      <p style="font-size: 3vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Nuestra misión es clara</span>:
        encontrar hogares amorosos y
        responsables para cada animal que haya perdido su camino. Trabajamos en estrecha colaboración con albergues y
        refugios asociados para rescatar, rehabilitar y reubicar a animales necesitados. Además, a través de nuestras
        campañas de esterilización,
        buscamos prevenir el sufrimiento innecesario y el crecimiento descontrolado de poblaciones de animales en
        situación de calle.
      </p>
      <p style="font-size: 3vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">¿Cómo funciona el programa?</span>
      </p>
      <p style="font-size: 3vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Jornadas de Adopción</span>:
        Nos unimos a la organización regular de jornadas de adopción en colaboración con nuestros albergues
        asociados. Durante estas jornadas, se brindan a las familias la oportunidad de conocer y adoptar a su compañero
        peludo ideal.
        Cada adopción representa una historia de esperanza y un nuevo comienzo para un animal en busca de amor y
        seguridad.
      </p>
      <p style="font-size: 3vw; text-align: justify; margin-bottom: 2%"><span style="font-weight: bold">Donativos de Comida</span>:
        Reconocemos la importancia de asegurar que los animales en albergues y hogares temporales reciban una
        nutrición adecuada. A través de donativos de comida, proporcionamos a nuestros albergues asociados los
        recursos necesarios para mantener a los animales bien alimentados y saludables mientras esperan su adopción.
      </p>
      <p style="font-size: 3vw; text-align: justify; "><span style="font-weight: bold">Campañas de Esterilización: </span>:
        Creemos firmemente en la prevención como parte integral de nuestra labor. Por eso, realizamos campañas de
        esterilización con la intención de controlar el
        crecimiento de poblaciones no deseadas y prevenir el sufrimiento de futuros animales en situación de calle.
        Estas campañas son esenciales para
        abordar la raíz del problema y asegurar un mejor futuro para nuestros amigos peludos.
      </p>

      <div style="background-color:  #ffac00; width: 40%; text-align: center; padding: 1%; border-radius: 3vw; font-weight: bold; color: white;
font-size: 3.3vw; left: 29%;  top: 0%; position: absolute"><p>Siembra Amor con <br> Adopción</p></div>
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




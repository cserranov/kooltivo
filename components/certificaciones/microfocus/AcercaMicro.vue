<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="12" style="position: relative">
        <div style="text-align: center">
          <img src="@/assets/img/microfocus/chica.png" style="width: 100%" />
        </div>
        <div style="
                font-size: 1.8vw;
                padding: 2%;
                text-align: justify;
                position: absolute;
                top: 42%;
                left: 15%;
                color: white;
                width: 60%;
                height: 35%;
              ">
          <p>
            Nuestros cursos son impartidos por expertos de la industria y están
            diseñados para brindarte habilidades prácticas y aplicables. Al
            finalizar cada módulo deberás presentar un examen de conocimientos,
            una vez aprobados recibirás una certificación por parte de Micro
            Focus y Fundación Kooltivo que respalda tus conocimientos y
            experiencia.
          </p>
          <div style="text-align: center; margin-top: 3%" class="btn-route">
            <img src="@/assets/img/btn-registro.png" alt="" style="width: 20%" @click="registro()" />
          </div>
        </div>
        <div style="
                font-size: 1.8vw;
                padding: 2%;
                text-align: justify;
                position: absolute;
                top: 20%;
                left: 15%;
                color: white;
              ">
          <p>Acerca de</p>
          <p style="font-size: 3vw; font-weight: bold">Nuestro Curso</p>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="
              background: linear-gradient(to right, #84c5c9, #0561a8);
              padding: 5% 10%;
            ">
        <div style="
                font-size: 3vw;
                text-align: justify;
                color: white;
                margin-bottom: 3%;
              ">
          <p>Acerca de</p>
          <p style="font-size: 4vw; font-weight: bold">Nuestro Curso</p>
        </div>
        <div style="
                font-size: 2.6vw;
                text-align: justify;
                color: white;
                border: solid white 1px;
                padding: 5%;
                border-radius: 5vw;
              ">
          <p>
            Nuestros cursos son impartidos por expertos de la industria y están
            diseñados para brindarte habilidades prácticas y aplicables. Al
            finalizar cada módulo deberás presentar un examen de conocimientos,
            una vez aprobados recibirás una certificación por parte de Micro
            Focus y Fundación Kooltivo que respalda tus conocimientos y
            experiencia.
          </p>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  methods: {
    registro() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
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
}

ul {
  list-style-type: none;
  /* Elimina los marcadores de la lista */
  padding-left: 1.2em;
  /* Espacio para simular el punto (o cualquier otro marcador) */
}

ul li::before {
  content: "\2022";
  /* Código del carácter del marcador de lista (punto) */
  color: #ffac00;
  /* Color del marcador (amarillo en este caso) */
  display: inline-block;
  width: 1.5vw;
  /* Ajusta el ancho según sea necesario */
  margin-left: -1.2em;
  /* Alinea el marcador con el texto y ajusta según el padding-left */
}

ul li {
  color: black;
  /* Color del texto (negro en este caso) */
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

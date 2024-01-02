<template>
  <div class="container-main desktop">
    <v-row no-gutters style="
              background: linear-gradient(to right, #84c5c9, #0561a8);
              padding: 5% 7%;
            ">
      <v-col cols="6" style="
                display: flex;

                align-items: center;
              ">
        <div style="padding: 2%; text-align: justify; color: white">
          <p style="margin-bottom: 5%; font-weight: bold; font-size: 2.5vw">
            Evento Final
          </p>
          <p style="font-size: 1.8vw">Conferencia con</p>
          <p style="font-size: 1.8vw">Expertos en Automatización</p>
        </div>
      </v-col>
      <v-col cols="6">
        <div style="
                  font-size: 1.8vw;
                  padding: 2% 7%;
                  text-align: justify;
                  color: white;
                ">
          <p style="margin-bottom: 5%">
            Como punto culminante del curso, tendrás la oportunidad de
            participar en un evento especial con distinguidos expertos del
            ámbito empresarial.
          </p>
          <p style="margin-bottom: 5%">
            Este Evento te permitirá presentar tu proyecto de automatización
            ante los panelistas, lo cual te brindara una visión profunda de las
            aplicaciones de la automatización en el mundo real y la oportunidad
            de conectarte con líderes de la industria.
          </p>
          <p>
            Además, recibirás un certificado por parte de Kooltivo y Automation
            Anywhere con el cual podrás avalar el haber adquirido el nuevo
            aprendizaje.
          </p>
          <div style="text-align: center; margin-top: 10%" class="btn-route">
            <img src="@/assets/img/btn-registro.png" alt="" style="width: 35%" @click="registro()" />
          </div>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters style="
              background: linear-gradient(to right, #84c5c9, #0561a8);
              padding: 5% 10%;
            ">
      <v-col cols="12">
        <div style="padding: 2%; text-align: center; color: white">
          <p style="margin-bottom: 5%; font-weight: bold; font-size: 6vw">
            Evento Final
          </p>
          <p style="font-size: 4vw">Conferencia con</p>
          <p style="font-size: 4vw">Expertos en Automatización</p>
        </div>
      </v-col>
      <v-col cols="12">
        <div style="
                  font-size: 2.6vw;
                  padding: 2%;
                  text-align: justify;
                  color: white;
                ">
          <p style="margin-bottom: 5%">
            Como punto culminante del curso, tendrás la oportunidad de
            participar en un evento especial con distinguidos expertos del
            ámbito empresarial.
          </p>
          <p style="margin-bottom: 5%">
            Este Evento te permitirá presentar tu proyecto de automatización
            ante los panelistas, lo cual te brindara una visión profunda de las
            aplicaciones de la automatización en el mundo real y la oportunidad
            de conectarte con líderes de la industria.
          </p>
          <p>
            Además, recibirás un certificado por parte de Kooltivo y Automation
            Anywhere con el cual podrás avalar el haber adquirido el nuevo
            aprendizaje.
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

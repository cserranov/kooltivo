<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="7" style="padding: 5%">
        <p style="font-size: 3vw; font-weight: bold">
          Preparando a las Empresas para la Transformación Digital
        </p>
        <p style="
              margin-top: 6%;
              font-size: 1.7vw;
              color: #0073e4;
              font-weight: bold;
            ">
          Módulos ofrecidos:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            IT Operations Management Learning Path. Universal Discovery and CMDB
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            IT Operations Management Learnig Path. Process Automation
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            Fortify Certified Pather Sales Specialist Learning Pathway
          </li>
        </ul>
        <div style="text-align: center; margin-top: 10%" class="btn-route">
          <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
        </div>
        <div style="margin-top: 6%; text-align: center">
          <img src="@/assets/img/puntos.png" style="width: 18%" />
        </div>
      </v-col>

      <v-col cols="5" style="padding: 5%">
        <img src="@/assets/img/microfocus/img1.png" style="width: 100%" />
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="
            padding: 5%;
            display: flex;
            justify-content: center;
            align-items: center;
          ">
        <img src="@/assets/img/microfocus/img1.png" style="width: 50%" />
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 3.5vw; font-weight: bold">
          Preparando a las Empresas para la Transformación Digital
        </p>
        <p style="
              margin-top: 6%;
              font-size: 2.5vw;
              color: #0073e4;
              font-weight: bold;
            ">
          Módulos ofrecidos:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 2vw; margin-bottom: 3%">
            IT Operations Management Learning Path. Universal Discovery and CMDB
          </li>
          <li style="font-size: 2vw; margin-bottom: 3%">
            IT Operations Management Learnig Path. Process Automation
          </li>
          <li style="font-size: 2vw; margin-bottom: 3%">
            Fortify Certified Pather Sales Specialist Learning Pathway
          </li>
        </ul>
        <div style="margin-top: 6%; text-align: center">
          <img src="@/assets/img/puntos.png" style="width: 18%" />
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
  margin-top: 5%;
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

<template>
  <div class="container-main desktop">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 5%">
        <p style="font-size: 2.3vw; font-weight: bold">Descripción:</p>
        <p style="font-size: 1.5vw">
          La transformación digital es el motor que impulsa a las empresas hacia
          el futuro. En este emocionante viaje hacia la innovación y la
          eficiencia, te invitamos a participar en los cursos de Micro Focus.
          Estas oportunidades de aprendizaje te prepararán para liderar la
          revolución digital y destacar en tu carrera.
        </p>
      </v-col>
      <v-col cols="7" style="padding: 5%">
        <p style="font-size: 1.7vw; color: #0073e4; font-weight: bold">
          Cuentas con tres opciones:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              IT Operations Management Learning Path. Universal Discovery and
              CMDB
            </p>
            <p>
              En estos cursos, obtendrás un inventario completo sobre cómo
              configurar activos de Tecnologías de la Información (TI) en las
              instalaciones, múltiples nubes, hardware, software y puestos
              finales virtualizados y en contenedores. Estarás preparado para
              abordar los desafíos de la gestión de activos en un mundo cada vez
              más digitalizado.
            </p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              IT Operations Management Learnig Path. Process Automation
            </p>
            <p>
              Aprenderás a automatizar, integrar y organizar cualquier proceso
              de TI, ya sea en la nube o fuera de ella. Descubrirás cómo
              automatizar mediante opciones de creación de flujos de trabajo de
              código bajo o sin código y cómo integrar una plataforma rica en
              interfaz de programación de aplicaciones (API) para orquestar
              flujos de trabajo potentes y escalables.
            </p>
          </li>
          <li style="font-size: 1.3vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              Fortify Certified Pather Sales Specialist Learning Pathway
            </p>
            <p>
              Con Software Security Center, explorarás cómo los equipos de
              gestión, desarrollo y seguridad colaboran para evaluar errores,
              hacer seguimiento, validar, automatizar y gestionar las
              actividades de seguridad del software. Adicionalmente, tendrás
              acceso a herramientas y software para poner en práctica lo
              aprendido.
            </p>
            <div style="text-align: center; margin-top: 5%" class="btn-route">
              <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
            </div>
          </li>
        </ul>
      </v-col>
      <v-col cols="5" style="
                padding: 2%;
                display: flex;
                justify-content: center;
                align-items: center;
              ">
        <div>
          <img src="@/assets/img/microfocus/chico.png" style="width: 100%" />
        </div>
      </v-col>
      <v-col cols="12" style="padding: 0% 5% 5% 5%">
        <p style="font-size: 1.8vw; font-weight: bold">
          Plataforma: Todos los cursos se llevarán a cabo de manera virtual a
          través del portal de Micro Focus
        </p>
      </v-col>
    </v-row>
  </div>

  <div class="container-main movil">
    <v-row no-gutters>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 4vw; font-weight: bold">Descripción:</p>
        <p style="font-size: 2.8vw; text-align: justify">
          La transformación digital es el motor que impulsa a las empresas hacia
          el futuro. En este emocionante viaje hacia la innovación y la
          eficiencia, te invitamos a participar en los cursos de Micro Focus.
          Estas oportunidades de aprendizaje te prepararán para liderar la
          revolución digital y destacar en tu carrera.
        </p>
      </v-col>
      <v-col cols="12" style="
                padding: 2%;

                display: flex;
                justify-content: center;
                align-items: center;
                text-align: center;
              ">
        <div>
          <img src="@/assets/img/microfocus/chico.png" style="width: 50%" />
        </div>
      </v-col>
      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 4vw; color: #0073e4; font-weight: bold">
          Cuentas con tres opciones:
        </p>
        <ul style="list-style-type: none; margin-top: 4%">
          <li style="font-size: 2.5vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              IT Operations Management Learning Path. Universal Discovery and
              CMDB
            </p>
            <p style="text-align: justify">
              En estos cursos, obtendrás un inventario completo sobre cómo
              configurar activos de Tecnologías de la Información (TI) en las
              instalaciones, múltiples nubes, hardware, software y puestos
              finales virtualizados y en contenedores. Estarás preparado para
              abordar los desafíos de la gestión de activos en un mundo cada vez
              más digitalizado.
            </p>
          </li>
          <li style="font-size: 2.5vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              IT Operations Management Learnig Path. Process Automation
            </p>
            <p style="text-align: justify">
              Aprenderás a automatizar, integrar y organizar cualquier proceso
              de TI, ya sea en la nube o fuera de ella. Descubrirás cómo
              automatizar mediante opciones de creación de flujos de trabajo de
              código bajo o sin código y cómo integrar una plataforma rica en
              interfaz de programación de aplicaciones (API) para orquestar
              flujos de trabajo potentes y escalables.
            </p>
          </li>
          <li style="font-size: 2.5vw; margin-bottom: 3%">
            <p style="font-weight: bold">
              Fortify Certified Pather Sales Specialist Learning Pathway
            </p>
            <p style="text-align: justify">
              Con Software Security Center, explorarás cómo los equipos de
              gestión, desarrollo y seguridad colaboran para evaluar errores,
              hacer seguimiento, validar, automatizar y gestionar las
              actividades de seguridad del software. Adicionalmente, tendrás
              acceso a herramientas y software para poner en práctica lo
              aprendido.
            </p>
          </li>
        </ul>
      </v-col>

      <v-col cols="12" style="padding: 5% 10%">
        <p style="font-size: 3vw; font-weight: bold">
          Plataforma: Todos los cursos se llevarán a cabo de manera virtual a
          través del portal de Micro Focus.
        </p>
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
  background-color: gainsboro;
  border-radius: 3vw;
}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .movil {
    display: block;
  }

  .container-main {
    width: 100%;
    background-color: white;
    border-radius: 0vw;
  }
}
</style>

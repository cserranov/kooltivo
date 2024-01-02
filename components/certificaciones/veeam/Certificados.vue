<template>
  <div class="container-main">
    <v-row no-gutters>
      <v-col cols="12" sm="7" style="
                padding: 3%;
                text-align: center;
                display: flex;
                justify-content: center;
                align-items: center">
        <img src="@/assets/img/veeam/computadora.png" alt="" class="img" />

      </v-col>
      <v-col sm="5" cols="12">
        <div class="container-text">
          <ul style="list-style: none" class="list">
            <li class="espacio-requisitos">
              <span style="font-weight: bold" class="title">Certificados ofrecidos:</span>
              <p class="text" style="padding-left:2%">
              <ul>
                <li>
                  <p class="text"> Veeam Sales Professional (VMSP) 2023.</p>
                </li>
                <li>
                  <p class="text"> Veeam Sales Professional Microsoft 365 Protection.</p>
                </li>
              </ul>
              </p>
            </li>
            <li class="espacio-requisitos">
              <span style="font-weight: bold" class="title">Subtítulo:</span>
              <p class="text">
                Respaldo de datos (Data Cloud Managenent)
              </p>
            </li>
            <li class="espacio-requisitos">
              <span style="font-weight: bold" class="title">
                Fecha de inicio: </span>
              <p class="text">
                Siempre disponible
              </p>
            </li>
            <li class="espacio-requisitos">
              <span style="font-weight: bold" class="title">Duración:</span>
              <p class="text">
                1 mes
              </p>
            </li>
            <li class="espacio-requisitos">
              <span style="font-weight: bold" class="title">Descripción: </span>
              <p class="text" style="text-align: justify">
                Con esta serie de cursos, tus
                habilidades en protección de datos se
                transformarán en superpoderes digitales. La
                fundación Kooltivo está entusiasmada en
                presentarte una experiencia de aprendizaje
                única que te llevará al siguiente nivel en la
                gestión de datos y la seguridad digital.
              </p>
              <div style="text-align: center; margin-top: 5%;" class="btn-route">
                <img src="@/assets/img/btn-registro.png" alt="" style="width: 40%" @click="registro()" />
              </div>
            </li>
          </ul>
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
  }
}
</script>

<style scoped>
.btn-route:hover {
  transform: scale(1.1);
}

.container-text {
  padding: 1% 3%;
  height: 100%;
  max-width: 100%;
}

.espacio-requisitos {
  margin-bottom: 5%
}

.img {
  width: 100%;
  max-width: 100%;
}

.container-main {
  width: 100%;

  padding: 10%;

}

.title {
  font-size: 25px;

}

.list {
  list-style: none;
  /* Quitar el estilo de lista predeterminado (punto) */
}

.text {
  font-size: 25px;
}

@media (max-width: 1440px) {
  .title {
    font-size: 23px;

  }

  .text {
    font-size: 20px;
  }

  .container-main {
    width: 100%;

    padding: 5% 10%;
  }
}

@media (max-width: 1024px) {
  .title {
    font-size: 20px;

  }

  .text {
    font-size: 18px;
  }

  .container-main {
    width: 100%;

    padding: 5% 0%;
  }
}

@media (max-width: 768px) {
  .title {
    font-size: 16px;

  }

  .text {
    font-size: 13px;
  }

  .container-main {
    width: 100%;

    padding: 5% 0%;
  }
}

@media (max-width: 430px) {
  .container-text {
    padding: 1% 15%;
    height: 100%;

    max-width: 100%;
  }

  .img {
    width: 80%;
    max-width: 100%;
  }

  .espacio-requisitos {
    margin-bottom: 1%
  }

  .title {
    font-size: 18px;

  }

  .text {
    font-size: 15px;
  }

  .container-main {
    width: 100%;

    padding: 5% 0%;
  }
}

@media (max-width: 375px) {
  .container-text {
    padding: 1% 15%;
    height: 100%;

    max-width: 100%;
  }

  .img {
    width: 80%;
    max-width: 100%;
  }

  .espacio-requisitos {
    margin-bottom: 1%
  }

  .title {
    font-size: 18px;

  }

  .text {
    font-size: 15px;
  }

  .container-main {
    width: 100%;

    padding: 5% 0%;
  }
}

@media (max-width: 320px) {
  .container-text {
    padding: 1% 15%;
    height: 100%;

    max-width: 100%;
  }

  .img {
    width: 80%;
    max-width: 100%;
  }

  .espacio-requisitos {
    margin-bottom: 1%
  }

  .title {
    font-size: 15px;

  }

  .text {
    font-size: 12px;
  }

  .container-main {
    width: 100%;

    padding: 5% 0%;
  }
}
</style>

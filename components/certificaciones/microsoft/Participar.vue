<template>
  <div class="container-main" style="
            background-image: linear-gradient(to right, #318ae0, #3eb9f4);
            padding: 0% 5%;
          ">
    <v-row no-gutters>
      <v-col cols="12">
        <div class="title">¿Quién puede participar?</div>
      </v-col>
      <v-col cols="12">
        <div class="text">
          <p style="margin-bottom: 2%">
            Los cursos de Capacitación en Tecnología Microsoft para el
            Empoderamiento Digital están abiertos a cualquier persona interesada
            en adquirir habilidades tecnológicas valiosas. No requiere
            experiencia previa en tecnología ¡Todos son bienvenidos a unirse!
          </p>
          <p style="margin-bottom: 2%">
            Debido a que nuestros cursos se ofrecen en linea, necesitarás una
            conexión a Internet estable y un dispositivo (computadora, tableta o
            smartphone) que te permite acceder al contenido del curso y
            participar en las actividades en linea.
          </p>
          <p style="font-weight: bold">
            ¡La flexibilidad de aprender desde cualquier lugar está a tu
            alcance!
          </p>
          <div style="text-align: center; margin-top: 5%" class="btn-route">
            <img src="@/assets/img/btn-registro.png" alt="" style="width: 20%" @click="registro()" />
          </div>
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
.container-main {
  margin-top: 5%;
}

.title {
  padding: 5% 5% 0% 7%;
  color: white;
  font-size: 60px;
  font-weight: bold;
}

.text {
  padding: 5% 15%;
  font-size: 32px;
  color: white;
  text-align: justify;
}

@media (max-width: 1440px) {
  .title {
    padding: 5% 5% 0% 7%;

    font-size: 50px;
  }

  .text {
    padding: 5% 15%;
    font-size: 25px;
  }
}

@media (max-width: 1024px) {
  .title {
    padding: 5% 5% 0% 7%;
    font-size: 40px;
  }

  .text {
    padding: 5% 15%;
    font-size: 20px;
  }
}

@media (max-width: 768px) {
  .title {
    padding: 5% 5% 0% 7%;
    font-size: 30px;
  }

  .text {
    padding: 5% 15%;
    font-size: 15px;
  }
}

@media (max-width: 425px) {
  .title {
    padding: 5% 5% 0% 7%;
    font-size: 15px;
  }

  .text {
    padding: 5% 15%;
    font-size: 10px;
  }
}

@media (max-width: 375px) {
  .title {
    padding: 5% 5% 0% 7%;
    font-size: 13px;
  }

  .text {
    padding: 5% 15%;
    font-size: 8px;
  }
}

@media (max-width: 320px) {
  .title {
    padding: 5% 5% 0% 7%;
    font-size: 13px;
  }

  .text {
    padding: 5% 15%;
    font-size: 8px;
  }
}
</style>

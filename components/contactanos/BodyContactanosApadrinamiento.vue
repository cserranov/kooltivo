<template>
  <div class="container-main">
    <p class="title" style="margin-bottom: 1%">CONTÁCTANOS</p>
    <p class="text" style="margin-bottom: 3%">
      Contáctanos a través de los distintos medios que nuestra Fundación
      KOOLTIVO tiene para tu comodidad y recuerda que tus datos serán tratados
      confidencialmente
    </p>

    <v-row no-gutters>
      <v-col sm="6" cols="12" class="text-center container-info">
        <div style="width: 50%; height: 100%">
          <div style="margin-top: 40%">
            <div style="display: flex">
              <img
                src="@/assets/img/Pagkooltivo2-10.png"
                alt=""
                class="size-img-contact"
              />
              <p class="text-contact">contacto@kooltivo.org</p>
            </div>
            <div style="display: flex">
              <img
                src="@/assets/img/Pagkooltivo2-11.png"
                alt=""
                class="size-img-contact"
              />
              <p class="text-contact">+255511519270</p>
            </div>
          </div>
          <div style="margin-top: 25%">
            <p style="font-size: 1.5vw">Conecta con Nosotros:</p>
            <div>
              <img
                src="@/assets/img/registro_iconos/face.png"
                alt=""
                style="width: 13%"
                @click="abrirFacebook()"
              />
              <img
                src="@/assets/img/registro_iconos/you.png"
                alt=""
                style="width: 13%"
                @click="abrirYoutube()"
              />
              <img
                src="@/assets/img/registro_iconos/twitteer.png"
                alt=""
                style="width: 13%"
                @click="abrirTwitter()"
              />
              <img
                src="@/assets/img/registro_iconos/insta.png"
                alt=""
                style="width: 13%"
                @click="abrirInstagram()"
              />
            </div>
          </div>
        </div>
      </v-col>
      <v-col
        sm="6"
        cols="12"
        class="text-center container-form"
        style="
          background-color: #036687;
          padding: 5%;
          border-radius: 0 2vw 2vw 0;
          color: white;
        "
      >
        <form>
          <v-text-field v-model="name" label="Nombre"></v-text-field>

          <v-text-field v-model="phone" label="Teléfono"></v-text-field>

          <v-text-field v-model="email" label="Email"></v-text-field>

          <v-select
            v-model="select"
            :items="items"
            label="Áreas de interés"
          ></v-select>
          <v-btn class="me-4" @click="fetchData()"> Enviar</v-btn>
        </form>
      </v-col>
    </v-row>
  </div>
</template>

<script setup>
import { ref } from "vue";
import axios from "axios";
import Swal from "sweetalert2";

const name = ref("");
const phone = ref("");
const email = ref("");
const select = ref("");

const items = ref([
  "Educación Tecnológica",
  "Equidad de Género",
  "Apadrina un perrito",
  "Educación Financiera",
]);
const fetchData = async () => {
  try {
    let postData = {
      name: name.value,
      phone: phone.value,
      email: email.value,
      area: select.value,
      source: "axis",
      // Otros datos que quieras enviar
    };
    const response = await axios.post(
      "http://34.229.92.23/api/reports",
      postData
    );
    Swal.fire({
      position: "top",
      icon: "success",
      title: "Envio exitoso",
      showConfirmButton: false,
      timer: 1500,
    });
  } catch (error) {
    Swal.fire({
      position: "top",
      icon: "error",
      title: "Envio no exitoso",
      showConfirmButton: false,
      timer: 1500,
    });
  }
};

const abrirFacebook = () => {
  const url = "https://www.facebook.com/FundacionKooltivo";
  window.open(url, "_blank");
};
const abrirTwitter = () => {
  const url = "https://twitter.com/Kooltivo_";
  window.open(url, "_blank");
};
const abrirInstagram = () => {
  const url = "https://www.instagram.com/kooltivo_/?hl=es-la";
  window.open(url, "_blank");
};
const abrirYoutube = () => {
  const url = "https://www.youtube.com/@norbertomaldonado107";
  window.open(url, "_blank");
};
</script>

<style scoped>
.container-main {
  background-color: #d2d3d5;
  padding: 5% 10%;
}

.container-form {
}

.title {
  color: #606060;
  font-size: 3vw;
}

.text {
  color: #606060;
  font-size: 1.5vw;
}

.container-info {
  background-color: #f7f7f7;
  border-radius: 2vw 0px 0px 2vw;
  display: flex;
  justify-content: center;
  align-items: center;
}

.size-img-contact {
  width: 13%;
}

.text-contact {
  font-size: 1.5vw;
  margin-left: 3%;
}

@media (max-width: 600px) {
  .container-main {
    background-color: #d2d3d5;
    padding: 5% 10%;
  }

  .container-form {
  }

  .title {
    color: #606060;
    font-size: 5vw;
  }

  .text {
    color: #606060;
    font-size: 3vw;
  }

  .container-info {
    background-color: #f7f7f7;
    border-radius: 2vw 2vw 0px 0vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .size-img-contact {
    width: 13%;
  }

  .text-contact {
    font-size: 3vw;
    margin-left: 3%;
  }
}
</style>

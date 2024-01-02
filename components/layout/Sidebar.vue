<template>
  <div class="sidebar">
    <v-row no-gutters>
      <v-col cols="12">
        <div class="icon-facebook">
          <img
            src="@/assets/img/iconosSidebar/facebook.png"
            alt=""
            class="img-icon"
            @click="facebook()"
          />
        </div>
      </v-col>
      <v-col cols="12">
        <div class="icon-twitter">
          <img
            src="@/assets/img/iconosSidebar/twitter.png"
            alt=""
            class="img-icon"
            @click="twitter()"
          />
        </div>
      </v-col>
      <v-col cols="12">
        <div class="icon-instagram">
          <img
            src="@/assets/img/iconosSidebar/instagram.png"
            alt=""
            class="img-icon"
            @click="instagram()"
          />
        </div>
      </v-col>
      <v-col cols="12">
        <div class="icon-correo">
          <img
            src="@/assets/img/iconosSidebar/correo.png"
            alt=""
            class="img-icon"
            @click="enviarCorreo()"
          />
        </div>
      </v-col>
      <v-col cols="12">
        <div class="icon-whatsapp">
          <img
            src="@/assets/img/iconosSidebar/whats_N.png"
            alt=""
            class="img-icon"
            @click="whatsApp()"
          />
        </div>
      </v-col>
    </v-row>
  </div>
</template>
<script>
export default {
  methods: {
    enviarCorreo() {
      const correo = "contacto@kooltivo.org";
      const url = `mailto:${correo}`;
      window.open(url);
    },
    whatsApp() {
      window.open(
        "https://wa.me/+525511519270?text=%C2%A1Hola,%20quisiera%20recibir%20informaci%C3%B3n!"
      );
    },
    instagram() {
      window.open("https://www.instagram.com/kooltivo_/?hl=es-la", "_blank");
    },
    twitter() {
      window.open("https://twitter.com/Kooltivo_", "_blank");
    },
    facebook() {
      window.open("https://www.facebook.com/FundacionKooltivo", "_blank");
    },
  },
};
</script>
<style scoped>
.sidebar {
  margin: auto;
  width: 4vw;
  background-color: white;
  color: #fff;
  position: fixed;
  top: 20%;
  left: 0px;
  height: 20.5vw;
  overflow: auto;
  border: 1px solid #ccc;
  border-radius: 1vw;
}

.img-icon {
  width: 80%;
  transition: transform 0.3s;
}

.icon-facebook:hover {
  background: linear-gradient(to right, #84c5c9, #0561a8);
}
.icon-facebook {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 4vw;
  transform: scale(1);
  overflow: hidden;
}

.icon-facebook:hover .img-icon {
  transform: scale(1.5);
  content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
}
.icon-twitter:hover {
  background: linear-gradient(to right, #84c5c9, #0561a8);
}
.icon-twitter {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 4vw;
  transform: scale(1);
  overflow: hidden;
}

.icon-twitter:hover .img-icon {
  transform: scale(1.5);
  content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
}

.icon-instagram:hover {
  background: linear-gradient(to right, #84c5c9, #0561a8);
}
.icon-instagram {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 4vw;
  transform: scale(1);
  overflow: hidden;
}

.icon-instagram:hover .img-icon {
  transform: scale(1.5);
  content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
}

.icon-correo:hover {
  background: linear-gradient(to right, #84c5c9, #0561a8);
}
.icon-correo {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 4vw;
  transform: scale(1);
  overflow: hidden;
}

.icon-correo:hover .img-icon {
  transform: scale(1.5);
  content: url("@/assets/img/iconosSidebar/correoBlanco.png");
}

.icon-whatsapp:hover {
  background: linear-gradient(to right, #84c5c9, #0561a8);
}
.icon-whatsapp {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 4vw;
  transform: scale(1);
  overflow: hidden;
}

.icon-whatsapp:hover .img-icon {
  transform: scale(1.5);
  content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
}

@media (max-width: 600px) {
  .sidebar {
    margin: auto;
    width: 10vw;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 45%;
    left: 0px;
    height: 51vw;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 1vw;
  }

  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vw;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vw;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vw;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vw;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vw;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}
/* @media (max-width: 1440px) {
  .sidebar {
    margin: auto;
    width: 70px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 360px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 70px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}
@media (max-width: 1024px) {
  .sidebar {
    margin: auto;
    width: 50px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 310px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}
@media (max-width: 768px) {
  .sidebar {
    margin: auto;
    width: 50px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 310px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}

@media (max-width: 425px) {
  .sidebar {
    margin: auto;
    width: 30px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 205px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}

@media (max-width: 375px) {
  .sidebar {
    margin: auto;
    width: 30px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 205px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
}

@media (max-width: 320px) {
  .sidebar {
    margin: auto;
    width: 30px;
    background-color: white;
    color: #fff;
    position: fixed;
    top: 10%;
    left: 0px;
    height: 205px;
    overflow: auto;
    border: 1px solid #ccc;
    border-radius: 10px;
  }
  .img-icon {
    width: 80%;
    transition: transform 0.3s;
  }

  .icon-facebook:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-facebook {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-facebook:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/facebookBlanco.png");
  }
  .icon-twitter:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-twitter {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-twitter:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/twitterBlanco.png");
  }

  .icon-instagram:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-instagram {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-instagram:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/instgramBlanco.png");
  }

  .icon-correo:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-correo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-correo:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/correoBlanco.png");
  }

  .icon-whatsapp:hover {
    background: linear-gradient(to right, #84c5c9, #0561a8);
  }
  .icon-whatsapp {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 40px;
    transform: scale(1);
    overflow: hidden;
  }

  .icon-whatsapp:hover .img-icon {
    transform: scale(1.5);
    content: url("@/assets/img/iconosSidebar/whatsappBlanco.png");
  }
} */
</style>

<template>
  <div>
    <header>
      <v-toolbar style="background-color: black">
        <div class="logo-navbar">
          <v-btn @click="navigateToHome('/')">
            <img
              src="@/assets/img/Pagkooltivo2-03.png"
              alt="logo-kooltivo"
              class="img"
            />
          </v-btn>
        </div>
        <div class="container-icon-social">
          <v-btn @click="enviarCorreo()">
            <img
              class="logo-social-networks-instagram"
              src="@/assets/img/correo_circulo.png"
              alt="logo-instagram"
            />
          </v-btn>
          <v-btn @click="instagram">
            <img
              class="logo-social-networks-instagram"
              src="@/assets/img/Pagkooltivo2-04.png"
              alt="logo-instagram"
            />
          </v-btn>
          <v-btn @click="twitter">
            <img
              class="logo-social-networks-twitter"
              src="@/assets/img/Pagkooltivo2-05.png"
              alt="logo-twitter"
            />
          </v-btn>
          <v-btn @click="facebook">
            <img
              class="logo-social-networks-facebook"
              src="@/assets/img/Pagkooltivo2-06.png"
              alt="logo-facebook"
            />
          </v-btn>

          <v-menu :location="location">
            <template v-slot:activator="{ props }">
              <v-app-bar-nav-icon style="color: white" v-bind="props">
              </v-app-bar-nav-icon>
            </template>

            <v-list>
              <v-list-item
                class="btn-menu"
                v-for="(item, index) in items"
                :key="index"
              >
                <v-list-item-title @click="navigateToHome(item.route)"
                  >{{ item.title }}
                </v-list-item-title>
              </v-list-item>
            </v-list>
          </v-menu>
        </div>
      </v-toolbar>
    </header>
  </div>
</template>

<script>
export default {
  data: () => ({
    items: [
      { title: "Quiénes Somos", route: "/about" },
      { title: "Cursos", route: "/courses" },

      { title: "Educación Tecnologíca", route: "/ejes/educacion_tecnologica" },
      { title: "Educación Financiera", route: "/ejes/educacion_financiera" },
      { title: "Equidad de Género", route: "/ejes/equidad_de_genero" },
      { title: "Cuidado Animal", route: "/ejes/cuidado_animal" },
      {
        title: "Apadrinamientos",
        route: "/ejes/cuidado_animal#apadrinamientos",
      },
      { title: "Noticias", route: "/noticias" },
      { title: "Galería", route: "/galeria" },
      { title: "Contáctanos", route: "/contactanos" },
    ],
    location: "bottom",
  }),
  methods: {
    enviarCorreo() {
      const correo = "contacto@kooltivo.org";
      const url = `mailto:${correo}`;
      window.open(url);
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
    navigateToHome(route) {
      this.$router.push(route);
    },
  },
};
</script>

<style scoped>
.btn-menu:hover {
  background-color: #ffac00;
  color: white;
}

.logo-navbar {
  width: 75%;
  height: 100%;
  display: flex;
}

.img {
  width: 55%;
}

.container-icon-social {
  width: 25%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.logo-social-networks-instagram {
  width: 35px;
}

.logo-social-networks-twitter {
  width: 35px;
}

.logo-social-networks-facebook {
  width: 35px;
}

@media (max-width: 1440px) {
  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 75%;
    height: 100%;
    display: flex;
  }

  .container-icon-social {
    width: 25%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 35px;
  }

  .logo-social-networks-twitter {
    width: 35px;
  }

  .logo-social-networks-facebook {
    width: 35px;
  }
}

@media (max-width: 1024px) {
  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 65%;
    height: 100%;
    display: flex;
  }

  .container-icon-social {
    width: 35%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 35px;
  }

  .logo-social-networks-twitter {
    width: 35px;
  }

  .logo-social-networks-facebook {
    width: 35px;
  }
}

@media (max-width: 768px) {
  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 55%;
    height: 100%;
    display: flex;
  }

  .container-icon-social {
    width: 45%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 35px;
  }

  .logo-social-networks-twitter {
    width: 35px;
  }

  .logo-social-networks-facebook {
    width: 35px;
  }
}

@media (max-width: 600px) {
  .v-btn--size-default {
    --v-btn-size: 0.875rem;
    --v-btn-height: 36px;
    font-size: var(--v-btn-size);
    min-width: 54px;
    padding: 0px 10px;
  }

  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 35%;
    height: 100%;
    display: flex;
    align-items: center;
  }

  .img {
    width: 100%;
  }

  .container-icon-social {
    width: 65%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 30px;
  }

  .logo-social-networks-twitter {
    width: 30px;
  }

  .logo-social-networks-facebook {
    width: 30px;
  }
}

@media (max-width: 375px) {
  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 35%;
    height: 100%;
    display: flex;
    align-items: center;
  }

  .img {
    width: 100%;
  }

  .container-icon-social {
    width: 65%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 30px;
  }

  .logo-social-networks-twitter {
    width: 30px;
  }

  .logo-social-networks-facebook {
    width: 30px;
  }
}

@media (max-width: 320px) {
  .btn-menu:hover {
    background-color: #ffac00;
    color: white;
  }

  .logo-navbar {
    width: 25%;
    height: 100%;
    display: flex;
    align-items: center;
  }

  .img {
    width: 150%;
  }

  .container-icon-social {
    width: 75%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .logo-social-networks-instagram {
    width: 30px;
  }

  .logo-social-networks-twitter {
    width: 30px;
  }

  .logo-social-networks-facebook {
    width: 30px;
  }
}
</style>

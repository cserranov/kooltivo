<template>
  <div style="padding: 5%">
    <v-row no-gutters style="text-align: center">
      <v-col cols="12" sm="12">
        <v-row no-gutters style="text-align: center">
          <v-col cols="12">
            <h2 class="title">Inauguración Fundación Kooltivo</h2>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            style="display: flex; justify-content: center; align-items: center"
          >
            <!-- <div>
              <img class="img" :src="newone.url_img" alt="" />
            </div> -->
            <div>
              <video class="video-element" controls autoplay muted>
                <source src="@/assets/videos/home.mp4" type="video/mp4" />
              </video>
            </div>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            class="container-txt"
            style="display: flex; justify-content: center; align-items: center"
          >
            <p class="subtitle">
              El pasado 7 de septiembre, Norberto Maldonado, un experimentado
              experto en tecnología con una amplia trayectoria en instituciones,
              conferencias y medios de comunicación, asistió a la inauguración
              de Fundación Kooltivo, la cual fue establecida en 2022 con la
              misión de empoderar a individuos y comunidades mediante el uso de
              la tecnología. Fundación Kooltivo es una entidad sin ánimo de
              lucro comprometida en aprovechar los avances tecnológicos para
              fomentar la igualdad de oportunidades y contribuir al desarrollo
              pleno de las personas. Sus áreas de enfoque incluyen la educación
              financiera básica, promoción de la igualdad de género, así como la
              protección y adopción de animales. Para obtener más información
              sobre Fundación Kooltivo, te invitamos a visitar sus perfiles en
              redes sociales bajo el nombre "Kooltivo".
            </p>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="12">
        <v-row no-gutters style="text-align: center">
          <v-col cols="12">
            <h2 class="title">Líderes del Mañana.</h2>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            style="display: flex; justify-content: center; align-items: center"
          >
            <div>
              <img
                class="img"
                src="@/assets/img/noticias/nota_2.png"
                alt=""
                style="width: 55%"
              />
            </div>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            class="container-txt"
            style="display: flex; justify-content: center; align-items: center"
          >
            <p class="subtitle">
              El mes pasado, Norberto Maldonado junto a Fundación Kooltivo
              visitaron a la comunidad 'El Plan', ubicada en el municipio de
              Huixquilucan. Durante esta visita, nuestra experta Kena, quien
              posee una amplia experiencia en el tema de la autoestima, habló
              sobre el valor de la mujer y la importancia de la autoaceptación,
              compartiendo técnicas de autoconocimiento que fortalecen la
              autoestima. Fundación Kooltivo es una organización sin fines de
              lucro que se compromete a promover la igualdad de género y brindar
              apoyo y protección a las mujeres. Si deseas obtener más
              información sobre Fundación Kooltivo, te invitamos a visitar sus
              perfiles en redes sociales bajo el nombre 'Kooltivo.'
            </p>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>
<script>
import axios from "axios";
export default {
  data() {
    return {
      colors: [
        "indigo",
        "warning",
        "pink darken-2",
        "red lighten-1",
        "deep-purple accent-4",
      ],
      slides: ["First", "Second", "Third", "Fourth", "Fifth"],
      news: [
        {
          title: "Líderes del Mañana.",
          decription:
            "El mes pasado, Norberto Maldonado junto a Fundación Kooltivo visitaron a la comunidad 'El Plan', ubicada en el municipio de Huixquilucan. Durante esta visita, nuestra experta Kena, quien posee una amplia experiencia en el tema de la autoestima, habló sobre el valor de la mujer y la importancia de la autoaceptación, compartiendo técnicas de autoconocimiento que fortalecen la autoestima. Fundación Kooltivo es una organización sin fines de lucro que se compromete a promover la igualdad de género y brindar apoyo y protección a las mujeres. Si deseas obtener más información sobre Fundación Kooltivo, te invitamos a visitar sus perfiles en redes sociales bajo el nombre 'Kooltivo.'",
          video: "assets/videos/home.mp4",
        },
      ],
    };
  },
  methods: {
    web(path) {
      window.open(path, "_blank");
    },
    async fetchData() {
      try {
        const response = await axios.get("http://127.0.0.1:8000/api/news");
        // Haz algo con la respuesta
        console.log("Respuesta exitosa:", response.data.data);
        this.news = response.data.data;
      } catch (error) {
        // Manejar el error
        console.error("Error en la petición:", error);
      }
    },
  },
  // mounted() {
  //   this.fetchData();
  // },
};
</script>
<style scoped>
.video-element {
  height: 25vw;
}
.rounded-btn {
  text-transform: capitalize;
  margin-top: 5%;
  border-radius: 1.5vw;
  padding: 1vw;
  font-weight: bold;
  font-size: 1vw;
  color: white;
  background-color: #ffac00;
  border: 1px solid #ffac00;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}
.title {
  font-size: 2.3vw;
}
.subtitle {
  font-size: 1.3vw;
  text-align: justify;
}
.img {
  width: 100%;
  border-radius: 1vw;
}
.txt {
  font-size: 1vw;
}
.container-txt {
  padding: 5% 5% 10% !important;
}
@media (max-width: 600px) {
  .title {
    font-size: 5vw;
  }
  .subtitle {
    font-size: 2.5vw;
  }
  .img {
    width: 80%;
  }
  .txt {
    font-size: 2.3vw;
  }
  .rounded-btn {
    font-size: 1.3vw;
  }
  .container-txt {
    padding: 0% 5% 10% !important;
  }
}
</style>

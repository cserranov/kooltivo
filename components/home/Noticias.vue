<template>
  <div style="padding: 0% 5%; margin-bottom: 5%">
    <v-row no-gutters class="justify-center align-center">
      <v-col
        cols="12"
        style="display: flex; justify-content: center; align-items: center"
      >
        <div style="flex: 1; text-align: end">
          <p style="font-size: 2.5vw">Prensa</p>
        </div>
        <div style="flex: 9">
          <img
            src="@/assets/img/linea_gris_ejes.png"
            alt=""
            style="width: 100%"
          />
        </div>
      </v-col>
    </v-row>
    <v-carousel
      cycle
      hide-delimiter-background
      show-arrows="hover"
      style="height: auto"
    >
      <v-carousel-item v-for="(slide, i) in news" :key="i">
        <v-row no-gutters style="text-align: center; padding: 5%">
          <v-col cols="12" style="padding: 0% 5%">
            <h2 class="title">
              {{ slide.title }}
            </h2>
            <p class="subtitle">
              {{ slide.subtitle }}
            </p>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            style="display: flex; justify-content: center; align-items: center"
          >
            <div>
              <img class="img" :src="slide.url_img" alt="" />
            </div>
          </v-col>
          <v-col
            cols="12"
            sm="6"
            class="container-txt"
            style="display: flex; justify-content: center; align-items: center"
          >
            <div>
              <p style="text-align: justify" class="txt">
                {{ slide.description }}
              </p>
              <v-btn
                class="rounded-btn"
                variant="outlined"
                @click="web(slide.url_link)"
              >
                Saber más
              </v-btn>
            </div>
          </v-col>
        </v-row>
      </v-carousel-item>
    </v-carousel>
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
          title: "Fundación Kooltivo.",
          subtitle:
            "A través de su labor, Fundación Kooltivo espera estimular el cambio social y contribuir a un mundo más equitativo, consciente e innovador.",
          url_img:
            "https://ruizhealytimes.com/wp-content/uploads/2023/09/fundacion-koltivo.jpg",
          url_link:
            "https://ruizhealytimes.com/ciencia-y-tecnologia/fundacion-kooltivo/",
          description:
            "En 2022 nació una iniciativa con un claro propósito: aprovechar los avances tecnológicos para generar igualdad de oportunidades y ayudar a las personas a sacar su máximo potencial. Esta...",
        },
        {
          title: "Un cuarto de vida de los jóvenes se queda en la red",
          subtitle: "¿es posible aprovechar eso para el desarrollo?",
          url_img:
            "https://delapazcostemalle.com.mx/wp-content/uploads/2022/10/bigstock-Businessman-Using-Mobile-Smart-431802158.jpg",
          url_link:
            "https://edomexaldia.com/un-cuarto-de-vida-de-los-jovenes-se-queda-en-la-red-es-posible-aprovechar-eso-para-el-desarrollo/",
          description:
            "En el marco del Día del Internet, «Es necesario seguir contribuyendo para que todos tengamos acceso a la web, sin embargo, entre los retos actuales más relevantes, está impulsar que la red se utilice como...",
        },
        {
          title:
            "Jóvenes pasan una cuarta parte de sus vidas en la red: el reto es que se use productivamente",
          subtitle:
            "De acuerdo con estudios globales, los jóvenes pasan más de ocho horas al día conectados a la red. Gran parte se dedica al entretenimiento.",
          url_img:
            "https://elmexicanorm.blob.core.windows.net/images/2023/05/22/sophia-galeria-3854657a-focus-0-0-690-347.png",
          url_link:
            "https://www.el-mexicano.com/nacional/jovenes-pasan-una-cuarta-parte-de-sus-vidas-en-la-red-el-reto-es-que-se-use-productivamente/2179233",
          description:
            "Es necesario seguir contribuyendo para que todos tengamos acceso a la web, sin embargo, entre los retos actuales más relevantes, está impulsar que la red se utilice como herramienta productiva, más allá de temas lúdicos o recreativos...",
        },
        {
          title: "El objetivo de la Fundación Kooltivo",
          url_img:
            "https://ruizhealytimes.com/wp-content/uploads/2023/09/fundacion-koltivo.jpg",
          url_link: "https://diarioimagenqroo.mx/noticias/?p=535706",
          description:
            "El objetivo de la Fundación Kooltivo al sumarse a la conmemoración de este día es impulsar el mensaje de que el acercamiento a las nuevas herramientas tecnológicas es una de las mejores vías para incidir en un cambio positivo en las personas y que logren mejoras en su calidad de vida, especialmente de aquellos que se encuentran en situaciones de vulnerabilidad o con recursos limitados",
        },
        {
          title:
            "El día del padre y el día del wi-fi coninciden para favorecer la paternidad responsable",

          url_img:
            "https://41spc.img.ag.d.sendibm3.com/im/2340640/8fa9d317598231364095bed4b167a5304ca224aae4b5d8da97055840e639b4e1.png?e=Q-bPLwiaiD9InwULRa4Q2Lo0vcWXdTs8BwrYPCXSDPnFgMbXdbYBGM4b-plilNby20OKg4gCZDCynyMF4Id14XdfNO9W1yH6Oa4fZaPj-nPQFoZA7brTKseAX41hpL0ytnRyzZ4KNhZp1Cg3OqKjrQR_K7dOmVfTtz26V1ZuP93HFsKWbs1nM28RUgRLGoBohHT_426vC7_iHG8aKGTGXALfaKUthi-6mutk6yI",
          url_link:
            "https://tecnologiaconmario.wordpress.com/2023/06/16/el-dia-del-padre-y-el-dia-del-wi-fi-coinciden-para-favorecer-la-paternidad-responsable/",
          description:
            "EN EL MARCO DE LA CONMEMORACIÓN DEL DÍA DEL PADRE Y DEL DÍA DEL WI-FI, NORBERTO MALDONADO, EXPERTO EN TECNOLOGÍA Y DIRECTOR DE LA FUNDACIÓN KOOLTIVO, RESALTA LOS BENEFICIOS DE UTILIZAR...",
        },
        {
          title:
            "Relación padre e hijo favorece autoestima y desarrollo de habilidades sociales",
          subtitle:
            "En el Día del Padre se debe favorecer la paternidad responsable",
          url_img:
            "https://tvazteca.brightspotcdn.com/dims4/default/b8f1f81/2147483647/strip/true/crop/1920x1090+0+0/resize/928x527!/format/jpg/quality/80/?url=http%3A%2F%2Ftv-azteca-brightspot.s3.amazonaws.com%2Fac%2F84%2Fd4a9ec274abc9c40ce57d0f6f26b%2Fpadre-e-hijos-videollamada-ok.jpg",
          url_link:
            "https://www.vertigopolitico.com/bienestar/notas/relacion-padre-e-hijo-favorece-autoestima-y-desarrollo-habilidades-sociales",
          description:
            "En el marco de la conmemoración del Día del Padre y del Día del Wi-Fi, Norberto Maldonado, experto en tecnología y director de la fundación Kooltivo, resalta los beneficios de utilizar la inteligencia artificial (IA) y la tecnología para fortalecer nuestra labor como padres...",
        },
        {
          title:
            "¿Estamos listos para incluir la inteligencia artificial en el ambiente laboral?",

          url_img:
            "https://upload.wikimedia.org/wikipedia/commons/4/4d/Logo-Imagen-Radio-2016.jpg",
          url_link: "https://www.youtube.com/watch?v=RISRfoaWV9w",
          description:
            "Norberto Maldonado, director de Desarrollo de Negocio en Sellcom Solutions, habla en entrevista sobre los usos que se le pueden dar a la inteligencia artificial y el riesgo que esto significa para la generación de empleos. No te pierdas todos los detalles de la conversación....",
        },
        {
          title:
            "Fundación kooltivo destaca sus logros en educación tecnología, financiera, equidad de género y cuidado animal",

          url_img:
            "https://factordecambio.net/wp-content/uploads/2023/09/2-7.jpg",
          url_link:
            "https://factordecambio.net/fundacion-kooltivo-destaca-sus-logros-en-educacion-tecnologia-financiera-equidad-de-genero-y-cuidado-animal/",
          description:
            "La Fundación Kooltivo, liderada por su Presidente Fundador, el Mtro. Norberto Maldonado, y dirigida por la Mtra. Marlene Mizrahi, inauguró oficialmente sus actividades en una casona de la colonia Roma, en la Ciudad de México. Esta fundación tiene como misión usar...",
        },
        {
          title: "Fundación kooltivo, cultivando la educación de México",

          url_img:
            "https://hotbook.mx/wp-content/uploads/2023/09/captura-de-pantalla-2023-09-08-a-las-103923.jpg",
          url_link: "https://hotbook.mx/kooltivo-fundacion/",
          description:
            "En un mundo donde la tecnología avanza a pasos agigantados, es fundamental que todos tengan acceso a las herramientas y conocimientos necesarios para aprovechar al máximo su potencial. En 2022, nació Kooltivo, una iniciativa con ese claro propósito: aprovechar los avances tecnológicos para generar igualdad de...",
        },
        {
          title: "La tecnología tambíen cultiva",

          url_img:
            "https://www.esferanoticias.com/images/noticias/2018/nov/d2a66523-7286-4369-8f70-d487c52dd989.jpg",
          url_link:
            "https://www.esferanoticias.com/index.php/news/80-esfera/5201-la-tecnologia-tambien-cultiva",
          description:
            "El pasado 7 de septiembre estuvo en la casa Jarana ubicado en la colonia Roma, el conferencista Norberto Maldonado, quien es reconocido por ser experto en tecnología en diversas instituciones, brindando seminarios, así como participando en diversos medios, además, es columnista de índice político, donde semanalmente escribe. Fundador de la empresa Sellcom...",
        },
        {
          title:
            "Norberto Maldonado y Marlene Mizrahi presentan Fundación Kooltivo",

          url_img:
            "https://cdn-3.expansion.mx/dims4/default/4586d09/2147483647/strip/true/crop/6000x4000+0+0/resize/1600x1067!/format/webp/quality/60/?url=https%3A%2F%2Fcdn-3.expansion.mx%2F84%2Fb1%2F444668ff4c29956fa24dac42f15f%2Fkooltivo-04.JPG",
          url_link:
            "https://www.quien.com/circulos/2023/09/11/norberto-maldonado-y-marlene-mizrahi-presentan-fundacion-kooltivo#pid=slide-0",
          description:
            "Conoce la nueva iniciativa que busca construir un mejor México para el futuro enfocándose en temas como reforzar la cultura de cuidado animal y la lucha contra la violencia de género, entre otras....",
        },
        {
          title: "Inauguran Fundación Kooltivo",

          url_img:
            "https://ruizhealytimes.com/wp-content/uploads/2023/09/fundacion-koltivo.jpg",
          url_link: "https://perspectivas.mx/inauguran-fundacion-kooltivo/",
          description:
            "La Fundación Kooltivo, liderada por su presidente Fundador, el Mtro. Norberto Maldonado, y dirigida por la Mtra. Marlene Mizrahi, inauguró oficialmente sus actividades en una casona de la colonia Roma, en la Ciudad de México. Esta fundación tiene como misión usar la tecnología para promover la igualdad de oportunidades, de la cual surgen sus cuatro ejes de acción: la educación tecnológica...",
        },
        {
          title: "Inauguran Fundación Kooltivo",

          url_img:
            "https://perspectivas.mx/wp-content/uploads/2023/09/3d3e77e1-5f71-421f-a74f-4edd72d0748c-696x928.jpg",
          url_link: "https://perspectivas.mx/inauguran-fundacion-kooltivo/",
          description:
            "La Fundación Kooltivo, liderada por su presidente Fundador, el Mtro. Norberto Maldonado, y dirigida por la Mtra. Marlene Mizrahi, inauguró oficialmente sus actividades en una casona de la colonia Roma, en la Ciudad de México. Esta fundación tiene como misión usar la tecnología para promover la igualdad de oportunidades, de la cual surgen sus cuatro ejes de acción: la educación tecnológica...",
        },
        {
          title: "El Acento",

          url_img:
            "https://scontent.fmex36-1.fna.fbcdn.net/v/t39.30808-6/294633058_1995184904011918_3396402325413862061_n.jpg?stp=dst-jpg_p180x540&_nc_cat=106&ccb=1-7&_nc_sid=5f2048&_nc_ohc=9Xt1Pdey28UAX-1t_11&_nc_ht=scontent.fmex36-1.fna&oh=00_AfDzJWfCSOlA9KOiep2V8WGgSaro4YVTJYusyXvKixqOwQ&oe=6533BE12",
          url_link:
            "https://www.facebook.com/ColectivoOllinkan/videos/964703304624472/?extid=CL-UNK-UNK-UNK-IOS_GK0T-GK1C&mibextid=cr9u03&ref=sharing",
          description: "Hoy en El Acento nos acompaña Norberto Maldonado",
        },
        {
          title: "¿Qué onda con nuestros impuestos en ciencia y tecnología?",

          url_img:
            "https://indicepolitico.com/wp-content/uploads/2023/06/norberto_maldonado-750x375.jpg",
          url_link:
            "https://indicepolitico.com/que-onda-con-nuestros-impuestos-en-ciencia-y-tecnologia/",
          description:
            "La semana pasada, el 8 de septiembre, en su fecha máxima, se presentó el Presupuesto de Egresos de la Federación 2024 en la Cámara de Diputados Federal, y quiero hablarles sobre lo que significa para la inversión en ciencia y tecnología en nuestro país...",
        },
        {
          title: "¿Y la oferta de trabajo en tecnología en México?",

          url_img:
            "https://indicepolitico.com/wp-content/uploads/2023/06/norberto_maldonado-750x375.jpg",
          url_link:
            "https://indicepolitico.com/y-la-oferta-de-trabajo-en-tecnologia-en-mexico/",
          description:
            "Dentro de la industria tecnológica, la evolución ha sido notable y brinda una visión soprendente del panorama tecnológico mexicano y las oportunidades que ofrece. Una en la que la demanda de talento tecnológico en México está en constante crecimiento...",
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
.rounded-btn {
  text-transform: capitalize;
  margin-top: 5%;
  border-radius: 1.5vw;
  padding: 3%;
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
  font-size: 3vw;
}
.subtitle {
  font-size: 2vw;
}
.img {
  width: 100%;
  border-radius: 1vw;
}
.txt {
  font-size: 1.5vw;
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

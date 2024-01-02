<template>
  <HeroHome></HeroHome>
  <AboutHome></AboutHome>
  <OuraxesHome></OuraxesHome>
  <videoHome style="margin-top: 5%; margin-bottom: 5%"></videoHome>
  <Hero1Home></Hero1Home>
  <About_3Home></About_3Home>
  <WhatDoWeDoHome></WhatDoWeDoHome>
  <WhatDoWeDo_2Home></WhatDoWeDo_2Home>
  <Noticias></Noticias>
</template>

<script>
import HeroHome from "@/components/home/HeroHome.vue";
import AboutHome from "@/components/home/AboutHome.vue";
import OuraxesHome from "@/components/home/OuraxesHome.vue";
import WhatDoWeDoHome from "@/components/home/WhatDoWeDoHome.vue";
import WhatDoWeDo_2Home from "@/components/home/WhatDoWeDo_2Home.vue";
import Hero1Home from "@/components/home/Hero1Home.vue";
import About_3Home from "@/components/home/About_3Home.vue";
import videoHome from "@/components/home/videoHome.vue";
import Noticias from "@/components/home/Noticias.vue";

export default {
  components: {
    HeroHome,
    AboutHome,
    OuraxesHome,
    WhatDoWeDo_2Home,
    WhatDoWeDoHome,
    Hero1Home,
    About_3Home,
    videoHome,
    Noticias,
  },
  data() {
    return {
      scrollY: 0, // Inicializa la propiedad scrollY
    };
  },
  computed: {
    scrollPosition() {
      // Calcula y devuelve la posición de desplazamiento vertical
      return this.scrollY;
    },
  },
  watch: {
    scrollPosition(newValue) {
      // Ejecuta una función cuando scrollPosition cambia
      console.log(`Posición de desplazamiento vertical: ${newValue}px`);
    },
  },
  mounted() {
    if (process.client) {
      // Agrega un escucha de evento de desplazamiento
      window.addEventListener("scroll", this.handleScroll);
    }
  },
  beforeDestroy() {
    if (process.client) {
      // Elimina el escucha de evento de desplazamiento cuando el componente se destruye
      window.removeEventListener("scroll", this.handleScroll);
    }
  },
  methods: {
    handleScroll() {
      // Actualiza la propiedad scrollY con la posición de desplazamiento vertical en tiempo real
      this.scrollY = window.scrollY || window.pageYOffset;
    },
  },
};
</script>

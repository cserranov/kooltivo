<template>
  <HeroMicrosoft></HeroMicrosoft>
  <Herramientas></Herramientas>
  <Personas></Personas>
  <Requisitos></Requisitos>
  <Participar></Participar>
  <Temas></Temas>
</template>

<script>
import HeroMicrosoft from "@/components/certificaciones/microsoft/HeroMicrosoft.vue";
import Herramientas from "@/components/certificaciones/microsoft/Herramientas.vue";
import Personas from "@/components/certificaciones/microsoft/Personas.vue";
import Requisitos from "@/components/certificaciones/microsoft/Requisitos.vue";
import Participar from "@/components/certificaciones/microsoft/Participar.vue";
import Temas from "@/components/certificaciones/microsoft/Temas.vue";

export default {
  components: {
    HeroMicrosoft,
    Herramientas,
    Personas,
    Requisitos,
    Participar,
    Temas,
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

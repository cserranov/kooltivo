<template>
  <HeroVeeam></HeroVeeam>
  <Certificados></Certificados>
  <QuePuedesEsperar></QuePuedesEsperar>
  <RequisitosVeeam></RequisitosVeeam>
  <InscribirteVeeam></InscribirteVeeam>
</template>

<script>
import HeroVeeam from "@/components/certificaciones/veeam/HeroVeeam.vue";
import Certificados from "@/components/certificaciones/veeam/Certificados.vue";
import QuePuedesEsperar from "@/components/certificaciones/veeam/QuePuedesEsperar.vue";
import RequisitosVeeam from "@/components/certificaciones/veeam/RequisitosVeeam.vue";
import InscribirteVeeam from "@/components/certificaciones/veeam/InscribirteVeeam.vue";

export default {
  components: {
    HeroVeeam,
    Certificados,
    QuePuedesEsperar,
    RequisitosVeeam,
    InscribirteVeeam,
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

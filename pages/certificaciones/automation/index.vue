<template>
  <HeroAuto></HeroAuto>
  <ProcesoAa></ProcesoAa>
  <DescripcionAa></DescripcionAa>
  <RequisitosAuto></RequisitosAuto>
  <EventoFinal></EventoFinal>
  <InscribeteHoyAuto></InscribeteHoyAuto>
</template>

<script>
import HeroAuto from "@/components/certificaciones/automotion/HeroAuto.vue";
import ProcesoAa from "@/components/certificaciones/automotion/ProcesoAa.vue";
import DescripcionAa from "@/components/certificaciones/automotion/DescripcionAa.vue";
import RequisitosAuto from "~/components/certificaciones/automotion/RequisitosAuto.vue";
import EventoFinal from "~/components/certificaciones/automotion/EventoFinal.vue";
import InscribeteHoyAuto from "~/components/certificaciones/automotion/InscribeteHoyAuto.vue";


export default {
  components: {
    InscribeteHoyAuto,
    EventoFinal,
    RequisitosAuto,
    DescripcionAa,
    HeroAuto,
    ProcesoAa
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

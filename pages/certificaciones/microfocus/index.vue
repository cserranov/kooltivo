<template>
  <HeroMicro></HeroMicro>
  <div class="container">
    <Preparando></Preparando>
    <Descripcion></Descripcion>
    <RequisitosMicro></RequisitosMicro>

  </div>
  <AcercaMicro></AcercaMicro>
  <div class="container">
    <InscribeteHoy></InscribeteHoy>
  </div>
</template>
<style scoped>
.container {
  padding: 0% 5%;
}
</style>
<script>
import HeroMicro from "@/components/certificaciones/microfocus/HeroMicro.vue";
import Preparando from "~/components/certificaciones/microfocus/Preparando.vue";
import Descripcion from "~/components/certificaciones/microfocus/Descripcion.vue";
import RequisitosMicro from "~/components/certificaciones/microfocus/RequisitosMicro.vue";
import AcercaMicro from "~/components/certificaciones/microfocus/AcercaMicro.vue";
import InscribeteHoy from "~/components/certificaciones/microfocus/InscribeteHoy.vue";

export default {
  components: {
    InscribeteHoy,
    AcercaMicro,
    RequisitosMicro,
    Descripcion,
    Preparando,
    HeroMicro,
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

<template>
  <Hero_Apadrinamiento></Hero_Apadrinamiento>
  <BienvenidosApadrinamiento></BienvenidosApadrinamiento>
  <NarizPerrito_Apadrinamiento></NarizPerrito_Apadrinamiento>
  <Conviertete_Apadrinamiento></Conviertete_Apadrinamiento>
  <QueIncluye_Apadrinamiento></QueIncluye_Apadrinamiento>
  <!--  <BodyContactanos></BodyContactanos>-->
     <HagamosEstoJuntos_Apadrinamiento></HagamosEstoJuntos_Apadrinamiento>
</template>
<script>
import Hero_Apadrinamiento from "@/components/apadrinamiento/Hero_Apadrinamiento.vue";
import NarizPerrito_Apadrinamiento from "@/components/apadrinamiento/NarizPerrito_Apadrinamiento.vue";
import Conviertete_Apadrinamiento from "@/components/apadrinamiento/Conviertete_Apadrinamiento.vue";
import QueIncluye_Apadrinamiento from "@/components/apadrinamiento/QueIncluye_Apadrinamiento.vue";
import BienvenidosApadrinamiento from "~/components/apadrinamiento/BienvenidosApadrinamiento.vue";
import HagamosEstoJuntos_Apadrinamiento from "@/components/apadrinamiento/HagamosEstoJuntos_Apadrinamiento.vue";
// import BodyContactanos from "@/components/contactanos/BodyContactanos.vue";
export default {
  components: {
    BienvenidosApadrinamiento,
    Hero_Apadrinamiento,
    NarizPerrito_Apadrinamiento,
    Conviertete_Apadrinamiento,
    QueIncluye_Apadrinamiento,
    HagamosEstoJuntos_Apadrinamiento,
    // BodyContactanos
  },
};
</script>

<template>
  <Hero_Segunda></Hero_Segunda>
  <Bienvenidos></Bienvenidos>
  <ParallaxIan_segunda></ParallaxIan_segunda>
  <Options></Options>
  <ElCuidado></ElCuidado>
  <UneteSegunda></UneteSegunda>
</template>
<script>

import Hero_Segunda from "~/components/segunda_oportunidad/Hero_Segunda.vue";
import Bienvenidos from "~/components/segunda_oportunidad/Bienvenidos.vue";
import ParallaxIan_segunda from "~/components/segunda_oportunidad/ParallaxIan_segunda.vue";
import ElCuidado from "~/components/segunda_oportunidad/ElCuidado.vue";
import UneteSegunda from "~/components/segunda_oportunidad/UneteSegunda.vue";
import Options from "~/components/segunda_oportunidad/Options.vue";

export default {
  components: {
    Options,
    UneteSegunda,
    ElCuidado,
    ParallaxIan_segunda,
    Bienvenidos,
    Hero_Segunda,


  },
};
</script>

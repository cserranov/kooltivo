<template>
  <Hero_Tecnologica></Hero_Tecnologica>
  <QuePromovemosTec_Tecnologica class="circulo"></QuePromovemosTec_Tecnologica>
</template>
<script>
import Hero_Tecnologica from "@/components/axes/technologic_education/Hero_Tecnologica.vue";
import QuePromovemosTec_Tecnologica from "@/components/axes/technologic_education/QuePromovemosTec_Tecnologica.vue";

export default {
  components: {
    Hero_Tecnologica,
    QuePromovemosTec_Tecnologica,
  },
};
</script>
<style>
.circulo {
  margin-bottom: -1%;
}

@media (max-width: 600px) {
  .circulo {
    margin-bottom: -3%;
  }
}
</style>

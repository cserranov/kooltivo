<template>
  <Hero_Equidad></Hero_Equidad>
  <QueOfrecemos_Equidad></QueOfrecemos_Equidad>
  <videoGenero></videoGenero>
  <Map_Equidad></Map_Equidad>
  <Recuerda_Equidad class="circulo"></Recuerda_Equidad>
  <videoGenero_1></videoGenero_1>

  <!-- <About_2></About_2>
  
    <Ouraxes></Ouraxes>
  
    <Hero1></Hero1>
    <About_3></About_3>
    <WhatDoWeDo></WhatDoWeDo>
    <WhatDoWeDo_2></WhatDoWeDo_2>
  
   -->
  <!-- <JoinUs></JoinUs> -->
</template>
<script>
import Hero_Equidad from "@/components/axes/gender_equality/Hero_Equidad.vue";
import QueOfrecemos_Equidad from "@/components/axes/gender_equality/QueOfrecemos_Equidad.vue";
import Recuerda_Equidad from "@/components/axes/gender_equality/Recuerda_Equidad.vue";
import Map_Equidad from "@/components/axes/gender_equality/Map_Equidad.vue";
import videoGenero from "@/components/axes/gender_equality/videoGenero.vue";
import videoGenero_1 from "@/components/axes/gender_equality/videoGenero_1.vue";

export default {
  components: {
    Hero_Equidad,
    QueOfrecemos_Equidad,
    Recuerda_Equidad,
    Map_Equidad,
    videoGenero,
    videoGenero_1,
  },
};
</script>
<style>
.circulo {
  margin-bottom: -8px;
}

@media (max-width: 600px) {
  .circulo {
    margin-bottom: -10px;
  }
}
</style>

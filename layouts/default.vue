<template>
  <div>
    <Sidebar style="z-index: 1"></Sidebar>
    <div>
      <Menu></Menu>
      <NuxtPage />
      <Footer></Footer>
    </div>
  </div>
</template>
<script>
import Sidebar from "@/components/layout/Sidebar.vue";
import Menu from "@/components/layout/Menu.vue";
import Footer from "@/components/layout/Footer.vue";

export default {
  components: {
    Sidebar,
    Menu,
    Footer,
  },
};
</script>

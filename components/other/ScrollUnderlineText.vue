<template>
    <div class="scroll-container">
      <div class="subline-text">
        {{ text }}
        <div class="subline" :style="{ width: sublineWidth }"></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      text: String
    },
    data() {
      return {
        sublineWidth: '0%'
      };
    },
    mounted() {
      window.addEventListener('scroll', this.updateSublineWidth);
    },
    beforeDestroy() {
      window.removeEventListener('scroll', this.updateSublineWidth);
    },
    methods: {
      updateSublineWidth() {
        const scrollTop = window.scrollY || window.pageYOffset;
        const scrollHeight = document.documentElement.scrollHeight - document.documentElement.clientHeight;
        const scrollPercentage = (scrollTop / scrollHeight) * 100;
        this.sublineWidth = scrollPercentage + '%';
      }
    }
  };
  </script>
  
  <style scoped>
  .scroll-container {
    height: 300px;
    overflow: auto;
  }
  
  .subline-text {
    font-size: 18px;
    line-height: 1.5;
    padding: 20px;
    position: relative;
  }
  
  .subline {
    position: absolute;
    bottom: 0;
    left: 0;
    height: 2px;
    background-color: red; /* Cambia el color del subrayado según tus preferencias */
    transition: width 0.5s; /* Agrega una transición para suavizar el efecto */
  }
  </style>
  
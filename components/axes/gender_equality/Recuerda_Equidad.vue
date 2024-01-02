<template>
  <div class="container-main">
    <div style="width: 100%; height: 100%; position: relative; ">
      <img
          src="@/assets/img/equidadDeGenero/genero.png"
          alt=""
          style="width: 100%; height: 100%"
      />
      <div class="container-text">
        <p>
          ¡Conoce los <span style="color: #ffac00">centros</span> de ayuda de
          por <span style="color: #ffac00">estado y ciudad</span>!
        </p>
        <div>
          <v-btn
              class="rounded-btn"
              variant="outlined"
              @click="pdf()"
          >
            Conoce el listado
          </v-btn>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  methods: {
    pdf() {
      const url =
          "https://drive.google.com/file/d/1_LyVqXn39uI6kW3LKz7Jzl5QfDp4UbwR/view?usp=sharing";
      const link = document.createElement("a");
      link.href = url;
      link.download = "Catálogo_Violencia.pdf"; // Cambia "Nombre_del_archivo.pdf" al nombre deseado del archivo
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    },
  },
};
</script>

<style scoped>
.rounded-btn {
  border-radius: 2vw;
  padding: 1.5vw;
  margin-top: 5%;
  font-weight: bold;
  font-size: 1.3vw;
  border: 1px solid #03668c;
  color: white;
  background-color: #03668c;
}

.rounded-btn:hover {
  background-color: #ffac00;
  border: 1px solid #ffac00;
  color: white;
}

.rounded-btn.v-btn--density-default {
  height: auto;
}

.container-text {
  position: absolute;
  top: 35%;
  right: 8%;
  font-size: 2vw;
  font-weight: bold;
  width: 33%;
  text-align: center;
  height: 35%;
}

.container-main {
  width: 100%;

}

</style>

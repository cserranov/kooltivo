<template>
  <div class="container-main desktop">
    <v-row no-gutters style="width: 100%; height: 100%">
      <v-col
        cols="12"
        sm="12"
        style="width: 100%; height: 100%; position: relative"
      >
        <img
          src="@/assets/img/Pag_kooltivo-19.png"
          alt=""
          style="width: 60%; height: 100%; position: absolute; right: 0%"
        />

        <div class="text-title">
          <p>¿Qué Ofrecemos?</p>
        </div>
        <div class="text">
          <p>
            Ofrecemos cursos, capacitaciones y certificaciones que favorecen al
            progreso social. Reconocemos que el desarrollo comunitario depende
            en gran medida del acceso a las oportunidades, autoestima, respeto y
            cuidado a los individuos y todas las formas de vida.
          </p>
          <br />
          <p>
            Por ello, facilitamos opciones educativas y laborales capaces de
            mejorar el día a día de las personas, buscando obtener frutos en la
            sociedad.
          </p>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="mobil" style="width: 100%; position: relative">
    <div style="padding: 8%">
      <img src="@/assets/img/Pag_kooltivo-19.png" alt="" style="width: 100%" />
    </div>
    <div
      style="
        background-color: rgba(0, 0, 0, 0.7);
        color: white;
        border-radius: 25px;
        padding: 2% 15%;
        text-align: justify;
        position: absolute;
        bottom: 12%;
      "
    >
      <div>
        <p class="text-mobil-title" style="text-align: center">
          ¿Qué Ofrecemos?
        </p>
        <p class="text-mobil">
          Ofrecemos cursos, capacitaciones y certificaciones que favorecen al
          progreso social. Reconocemos que el desarrollo comunitario depende en
          gran medida del acceso a las oportunidades, autoestima, respeto y
          cuidado a los individuos y todas las formas de vida.
        </p>

        <p class="text-mobil">
          Por ello, facilitamos opciones educativas y laborales capaces de
          mejorar el día a día de las personas, buscando obtener frutos en la
          sociedad.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-main {
  width: 100%;
  height: 115vh;

  padding: 2% 5% 5% 5%;
}
.text-title {
  position: absolute;
  left: 0%;
  bottom: 65%;
  width: 40%;
  height: 20%;
  font-size: 50px;
  text-align: justify;
  font-weight: bold;
  display: flex;
  justify-content: center;
  align-items: center;
}
.text {
  position: absolute;
  left: 0%;
  bottom: 0%;
  width: 60%;
  height: 55%;
  border-radius: 60px;
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
  padding: 5%;
  font-size: 25px;
  text-align: justify;
}
.desktop {
  display: block;
}
.mobil {
  display: none;
}
@media (max-width: 1440px) {
  .container-main {
    height: 100vh;
  }
  .text {
    border-radius: 60px;
    padding: 5%;
    font-size: 20px;
  }
}
@media (max-width: 1024px) {
  .container-main {
    height: 75vh;
  }
  .text-title {
    position: absolute;
    left: 0%;
    bottom: 65%;
    width: 40%;
    height: 20%;
    font-size: 35px;
    text-align: justify;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .text {
    border-radius: 40px;
    padding: 3%;
    font-size: 18px;
  }
}
@media (max-width: 768px) {
  .container-main {
    height: 55vh;
  }
  .text-title {
    position: absolute;
    left: 0%;
    bottom: 65%;
    width: 40%;
    height: 20%;
    font-size: 28px;
    text-align: justify;
    font-weight: bold;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .text {
    border-radius: 40px;
    padding: 3%;
    font-size: 12px;
  }
}
@media (max-width: 600px) {
  .text-mobil {
    border-radius: 40px;
    padding: 1%;
    font-size: 9px;
  }
  .text-mobil-title {
    font-size: 12px;
  }
  .desktop {
    display: none;
  }
  .mobil {
    display: block;
  }
}
@media (max-width: 425px) {
  .text-mobil {
    border-radius: 40px;
    padding: 1%;
    font-size: 9px;
  }
}
@media (max-width: 375px) {
  .text-mobil {
    font-size: 9px;
  }
}
@media (max-width: 320px) {
  .text-mobil {
    font-size: 7px;
  }
}
</style>

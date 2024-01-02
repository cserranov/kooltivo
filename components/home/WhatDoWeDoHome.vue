<template>
  <div class="container-main desktop">
    <v-row no-gutters style="width: 100%; height: 100%">
      <v-col
        cols="12"
        sm="12"
        style="width: 100%; height: 100%; position: relative"
      >
        <img
          src="@/assets/img/Pag_kooltivo-18.png"
          alt=""
          style="width: 60%; height: 100%"
        />
        <div class="text">
          <p>
            En Kooltivo ofrecemos programas de capacitación tecnológica, así
            como de educación financiera y cultural con la finalidad de
            empoderar a las personas, brindándoles habilidades y conocimientos
            relevantes para nuestro presente y futuro, y abogando por un mundo
            más justo, inclusivo y sostenible.
          </p>
        </div>
        <div class="text-title">
          <p>¿Qué Hacemos?</p>
        </div>
      </v-col>
    </v-row>
  </div>

  <div class="mobil" style="width: 100%; margin-top: 5%; position: relative">
    <div style="padding: 8%">
      <img src="@/assets/img/Pag_kooltivo-18.png" alt="" style="width: 100%" />
    </div>
    <div class="text-text">
      <p class="text-mobil-title">¿Qué Hacemos?</p>
      <p class="text-mobil">
        En Kooltivo ofrecemos programas de capacitación tecnologica, así como de
        educación financiera y cultural con la finalidad de empoderar a las
        personas, brindándoles habilidades y conocimientos relevantes para
        nuestro presente y futuro, y abogando por un mundo más justo, inclusivo
        y sostenible.
      </p>
    </div>
  </div>
</template>

<!-- <template>
  <v-row no-gutters>
    <v-col cols="7">
      <div class="container-img">
        <img src="@/assets/img/Pag_kooltivo-18.png" alt="" class="img" />
      </div>
    </v-col>
    <v-col cols="5">
      <v-row no-gutters>
        <v-col cols="12" xs="6">
          <div class="container-text">¿Qué Hacemos?</div>
        </v-col>
        <v-col cols="12">
          <div class="container-float">
            <div style="text-align: justify">
              <p class="text">
                En Kooltivo ofrecemos programas de capacitación tecnologica,así
                como de educación financiera y cultural con la finalidad de
                empoderar a las personas, brindándoles habilidades y
                conocimientos relevantes para nuestro presente y futuro, y
                abogando por un mundo más justo, inclusivo y sostenible.
              </p>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template> -->

<style scoped>
.container-main {
  width: 100%;
  height: 115vh;
  padding: 5% 5% 2% 5%;
}
.text-title {
  position: absolute;
  right: 0%;
  bottom: 65%;
  width: 40%;
  height: 20%;
  color: black;
  font-size: 50px;
  text-align: justify;

  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: bold;
}
.text {
  position: absolute;
  right: 0%;
  bottom: 0%;
  width: 60%;
  height: 55%;
  border-radius: 60px;
  background-color: rgba(0, 0, 0, 0.7);
  color: white;
  padding: 8%;
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
  .text-title {
    position: absolute;
    right: 0%;
    bottom: 65%;
    width: 40%;
    height: 20%;
    color: black;
    font-size: 50px;
    text-align: justify;

    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
  }
  .text {
    border-radius: 60px;

    padding: 8%;
    font-size: 20px;
  }
}
@media (max-width: 1024px) {
  .container-main {
    height: 75vh;
  }
  .text-title {
    position: absolute;
    right: 0%;
    bottom: 65%;
    width: 40%;
    height: 20%;
    color: black;
    font-size: 40px;
    text-align: justify;

    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
  }
  .text {
    border-radius: 40px;
    padding: 7%;
    font-size: 18px;
  }
}
@media (max-width: 768px) {
  .container-main {
    height: 55vh;
  }
  .text-title {
    position: absolute;
    right: 0%;
    bottom: 65%;
    width: 40%;
    height: 20%;
    color: black;
    font-size: 30px;
    text-align: justify;

    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
  }
  .text {
    border-radius: 40px;
    padding: 7%;
    font-size: 13px;
  }
}
@media (max-width: 600px) {
  .text-text {
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    border-radius: 20px;
    padding: 3% 15%;
    text-align: justify;
    position: absolute;
    bottom: 12%;
  }
  .text-mobil-title {
    font-size: 15px;
    text-align: center;
  }
  .text-mobil {
    border-radius: 20px;
    padding: 1%;
    font-size: 10px;
  }
  .desktop {
    display: none;
  }
  .mobil {
    display: block;
  }
}
@media (max-width: 375px) {
  .text-mobil-title {
    font-size: 13px;
    text-align: center;
  }
  .text-mobil {
    border-radius: 20px;
    padding: 1%;
    font-size: 8px;
  }
  .desktop {
    display: none;
  }
  .mobil {
    display: block;
  }
}
@media (max-width: 360px) {
  .text-mobil-title {
    font-size: 13px;
    text-align: center;
  }
  .text-mobil {
    border-radius: 20px;
    padding: 1%;
    font-size: 8px;
  }
  .desktop {
    display: none;
  }
  .mobil {
    display: block;
  }
}
@media (max-width: 320px) {
  .text-mobil-title {
    font-size: 13px;
    text-align: center;
  }
  .text-mobil {
    border-radius: 20px;
    padding: 1%;
    font-size: 8px;
  }
  .desktop {
    display: none;
  }
  .mobil {
    display: block;
  }
}
</style>

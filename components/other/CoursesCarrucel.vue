<template>
  <v-container class="container-component">
    <v-row no-gutters>
      <v-col cols="12">
        <div class="container-title">
          <h2 class="title">Cursos</h2>
          <p class="text">Programas de apoyo para la vida KOOL</p>
        </div>
      </v-col>
      <v-col cols="12">
        <v-row no-gutters>
          <v-col cols="3">
            <div class="container-img">
              <div class="contenedor">
                <img
                  class="img"
                  src="../assets/img/Pagkooltivo2-14.png"
                  alt=""
                />
                <div class="capa"></div>
              </div>
              <p class="text-img">EDUCACIÓN TECNOLOGICA</p>
              <img
                class="img-star"
                src="../assets/img/Pagkooltivo2-27.png"
                alt=""
              />
            </div>
          </v-col>

          <v-col cols="3">
            <div class="container-img">
              <div class="contenedor">
                <img
                  class="img"
                  src="../assets/img/Pagkooltivo2-14.png"
                  alt=""
                />
                <div class="capa"></div>
              </div>
              <p class="text-img">EDUCACIÓN TECNOLOGICA</p>
              <img
                class="img-star"
                src="../assets/img/Pagkooltivo2-27.png"
                alt=""
              />
            </div>
          </v-col>
          <v-col cols="3">
            <div class="container-img">
              <div class="contenedor">
                <img
                  class="img"
                  src="../assets/img/Pagkooltivo2-14.png"
                  alt=""
                />
                <div class="capa"></div>
              </div>
              <p class="text-img">EQUIDAD DE GÉNERO</p>
              <img
                class="img-star"
                src="../assets/img/Pagkooltivo2-27.png"
                alt=""
              />
            </div>
          </v-col>
          <v-col cols="3">
            <div class="container-img">
              <div class="contenedor">
                <img
                  class="img"
                  src="../assets/img/Pagkooltivo2-14.png"
                  alt=""
                />
                <div class="capa"></div>
              </div>
              <p class="text-img">CUIDADO ANIMAL</p>
              <img
                class="img-star"
                src="../assets/img/Pagkooltivo2-27.png"
                alt=""
              />
            </div>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.container-title {
  padding: 30px 30px 10px 50px;
}
.title {
  font-size: 50px;
  font-weight: bold;
}
.text {
  font-size: 30px;
}
.container-img {
  padding: 5px;
  text-align: center;
  position: relative; /* Establece el posicionamiento relativo en el contenedor */
  display: inline-block; /* Para que el contenedor se ajuste al tamaño de la imagen */
}

.text-img {
  font-size: 25px;
  margin-top: 50px;
}

.img {
  width: 100%;
}
.img-star {
  width: 60%;
}
.contenedor {
  position: relative;
  display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
}

.contenedor:hover .capa {
  background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
}
@media (max-width: 1920px) {
  .container-title {
    padding: 50px 30px 30px 100px;
  }
  .title {
    font-size: 50px;
    font-weight: bold;
  }
  .text {
    font-size: 20px;
  }
  .container-img {
    padding: 75px;
    text-align: center;
  }

  .text-img {
    font-size: 15px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 30px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}
@media (max-width: 1440px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 35px;
    font-weight: bold;
  }
  .text {
    font-size: 20px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 15px;
    margin-top: 20px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}
@media (max-width: 1024px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 25px;
    font-weight: bold;
  }
  .text {
    font-size: 15px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 13px;
    margin-top: 10px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}
@media (max-width: 768px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 20px;
    font-weight: bold;
  }
  .text {
    font-size: 14px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 10px;
    margin-top: 10px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}

@media (max-width: 425px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 16px;
    font-weight: bold;
  }
  .text {
    font-size: 10px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 7px;
    margin-top: 10px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}

@media (max-width: 375px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 15px;
    font-weight: bold;
  }
  .text {
    font-size: 10px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 7px;
    margin-top: 10px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}

@media (max-width: 322px) {
  .container-title {
    padding: 30px 30px 10px 15px;
  }
  .title {
    font-size: 15px;
    font-weight: bold;
  }
  .text {
    font-size: 10px;
  }
  .container-img {
    padding: 5px;
    text-align: center;
  }

  .text-img {
    font-size: 7px;
    margin-top: 10px;
  }

  .img {
    width: 100%;
  }
  .img-star {
    width: 60%;
  }
  .contenedor {
    position: relative;
    display: inline-block; /* O la propiedad que corresponda al diseño de tu página */
  }

  .capa {
    border-radius: 10px;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    pointer-events: none;
    transition: background-color 0.3s; /* Transición suave en el cambio de color */
  }

  .contenedor:hover .capa {
    background-color: rgba(0, 0, 0, 0); /* Capa transparente en hover */
  }
}
</style>

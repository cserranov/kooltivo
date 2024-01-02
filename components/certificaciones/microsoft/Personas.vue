<template>
  <div class="container-main" style="padding: 0% 5%">
    <div style="position: relative">
      <img
        src="@/assets/img/elementos_microsoft/personas.png"
        alt=""
        style="width: 100%"
      />
      <div class="container-text">
        <p class="title">Descripción:</p>
        <p class="text-1">
          Con estos cursos podrás adquirir, habilidades esenciales en tecnología
          Microsoft y avanzar en tu carrera profesional. Nuestra misión en
          promover el empoderamiento digital y el acceso a la educación de
          calidad para todos, y estos cursos son parte fundamental, básica y
          necesaria de ese compromiso.
        </p>
      </div>
      <div
        style="
          position: absolute;
          bottom: 1%;

          height: 8%;
          padding: 2% 5%;
          width: 100%;
          display: flex;
          justify-content: start;
          align-items: center;
        "
      >
        <p class="text-2">
          <span style="font-weight: bold">Plataforma</span>: Todos los cursos se
          llevarán a cabo de manera virtual a través de la plataforma de
          Kooltivo.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-text {
  position: absolute;
  top: 1%;

  height: 15%;
  padding: 1% 5%;
  width: 100%;
}
.title {
  font-size: 35px;
  font-weight: bold;
  margin-bottom: 1%;
}
.text-1 {
  font-size: 30px;
}
.text-2 {
  font-size: 30px;
}
@media (max-width: 1440px) {
  .title {
    font-size: 30px;
  }
  .text-1 {
    font-size: 25px;
  }
  .text-2 {
    font-size: 25px;
  }
}
@media (max-width: 1024px) {
  .title {
    font-size: 25px;
  }
  .text-1 {
    font-size: 18px;
  }
  .text-2 {
    font-size: 18px;
  }
}
@media (max-width: 768px) {
  .title {
    font-size: 20px;
  }
  .text-1 {
    font-size: 13px;
  }
  .text-2 {
    font-size: 13px;
  }
}
@media (max-width: 425px) {
  .title {
    font-size: 13px;
  }
  .text-1 {
    font-size: 7px;
  }
  .text-2 {
    font-size: 7px;
  }
}
@media (max-width: 375px) {
  .title {
    font-size: 10px;
  }
  .text-1 {
    font-size: 7px;
  }
  .text-2 {
    font-size: 7px;
  }
}
@media (max-width: 320px) {
  .container-text {
    position: absolute;
    top: 1%;

    height: 15%;
    padding: 0% 5%;
    width: 100%;
  }
  .title {
    font-size: 9px;
  }
  .text-1 {
    font-size: 6px;
  }
  .text-2 {
    font-size: 6px;
  }
}
</style>

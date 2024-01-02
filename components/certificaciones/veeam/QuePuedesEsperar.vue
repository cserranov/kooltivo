<template>
  <!--  <div class="container-main desktop">-->
  <!--    <img-->
  <!--        src="@/assets/img/veeam/imagen1.png"-->
  <!--        alt=""-->
  <!--        style="width: 100%;"-->
  <!--    />-->
  <!--    <div-->
  <!--        class="container-text-main"-->
  <!--    >-->
  <!--      <p style="margin-bottom: 2%; font-weight: bold">¿Qué puedes esperar?</p>-->
  <!--      <p style="margin-bottom: 2%">-->
  <!--        Imagina esto, un mundo donde dominas la protección de datos en todas sus-->
  <!--        formas. En estos cursos de certificación de Veeam, aprenderás las-->
  <!--        habilidades esenciales para diseñar, implementar y gestionar soluciones-->
  <!--        de protección de datos como un verdadero profesional.-->
  <!--      </p>-->
  <!--      <p style="margin-bottom: 2%">-->
  <!--        Los programas de capacitación de Veeam Sales Professional (VMSP) 2023 y-->
  <!--        Veeam Technical Sales Professional (VMTSP) están diseñados para ayudarte-->
  <!--        a obtener un entrenamiento en el portafolio de esta gran tecnología.-->
  <!--        VMSP y VMTSP 2023 son cursos fáciles de completar que elevarán tu-->
  <!--        estatus como asesor confiable para clientes, ampliarán tu conocimiento-->
  <!--        de la industria y te permitirán mantenerte al tanto de las tendencias-->
  <!--        tecnológicas en evolución.-->
  <!--      </p>-->
  <!--      <p style="margin-bottom: 2%; font-weight: bold">-->
  <!--        ¿Quieres aprender a respaldar y recuperar datos críticos? ¡Entonces este-->
  <!--        curso está hecho para ti!-->
  <!--      </p>-->
  <!--    </div>-->

  <!--  </div>-->

  <div class="container-main desktop">

    <img src="@/assets/img/veeam/dos.png" alt="" style="width: 100%; height: 100%" />
    <div class="container-text-main">
      <p style="margin-bottom: 2%; font-weight: bold">¿Qué puedes esperar?</p>
      <p style="margin-bottom: 2%">
        Imagina esto, un mundo donde dominas la protección de datos en todas sus
        formas. En estos cursos de certificación de Veeam, aprenderás las
        habilidades esenciales para diseñar, implementar y gestionar soluciones
        de protección de datos como un verdadero profesional.
      </p>
      <p style="margin-bottom: 2%">
        Los programas de capacitación de Veeam Sales Professional (VMSP) 2023 y
        Veeam Technical Sales Professional (VMTSP) están diseñados para ayudarte
        a obtener un entrenamiento en el portafolio de esta gran tecnología.
        VMSP y VMTSP 2023 son cursos fáciles de completar que elevarán tu
        estatus como asesor confiable para clientes, ampliarán tu conocimiento
        de la industria y te permitirán mantenerte al tanto de las tendencias
        tecnológicas en evolución.
      </p>
      <p style="margin-bottom: 2%; font-weight: bold">
        ¿Quieres aprender a respaldar y recuperar datos críticos? ¡Entonces este
        curso está hecho para ti!
      </p>
      <div style="text-align: center; margin-top: 5%;" class="btn-route">
        <img src="@/assets/img/btn-registro.png" alt="" style="width: 25%" @click="registro()" />
      </div>
    </div>
    <div class="text-izq-sup-destacado">
      <p style="margin-bottom: 2%; font-weight: bold">
        Lo destacado del curso:
      </p>
      <p style="margin-bottom: 2%;">
      <ul style="padding-left: 5%;">
        <li>Aprenderás de expertos
          en la industria que han
          estado en la vanguardia de
          protección de datos.
        </li>
        <li>Sumérgete en casos de
          estudio del mundo real y
          escenarios desafiantes que
          te prepararán para
          situaciones del mundo
          laboral.
        </li>
        <li>Obtén acceso a recursos
          exclusivos de Veeam
        </li>
      </ul>
      </p>
    </div>
    <div class="plataforma">
      <p style="margin-bottom: 2%">
        <span style="font-weight: bold">Plataforma</span>: Todos los módulos
        se llevarán a cabo de manera
        virtual a través del portal de
        Veeam.
      </p>

    </div>
    <div class="certificacion">
      <p style="margin-bottom: 5%; font-weight:  bold;" class="title">
        Certificación
      </p>
      <p style="margin-bottom: 5%;">
        Al finalizar con éxito los módulos
        de cada certificado, recibirás un
        diploma avalado por Veeam y
        Fundación Kooltivo.
      </p>
      <p style="margin-bottom: 5%;color: blue;">
        ¡Los cursos son totalmente
        gratuitos!
      </p>
      <p style="margin-bottom: 5%; font-weight: bold;" class="title">
        Temas que se
        abordarán:
      </p>
      <p>
        A partir de esta serie de cursos
        aprenderás a crear soluciones
        de copias de seguridad,
        recuperación y gestión de datos
        con una única plataforma para
        entornos cloud, virtuales, físicos,
        Software as a Service y
        Kubernetes+ (contenedores).
      </p>
      <div style="text-align: center; margin-top: 5%;" class="btn-route">
        <img src="@/assets/img/btn-registro.png" alt="" style="width: 40%" @click="registro()" />
      </div>
    </div>
  </div>

  <div class="container-main mobil">
    <img src="@/assets/img/veeam_movil/chica.png" alt="" style="width: 100%;" />
    <div class="container-text-main-mobil">
      <p style="margin-bottom: 2%; font-weight: bold">¿Qué puedes esperar?</p>
      <p style="margin-bottom: 2%">
        Imagina esto, un mundo donde dominas la protección de datos en todas sus
        formas. En estos cursos de certificación de Veeam, aprenderás las
        habilidades esenciales para diseñar, implementar y gestionar soluciones
        de protección de datos como un verdadero profesional.
      </p>
      <p style="margin-bottom: 2%">
        Los programas de capacitación de Veeam Sales Professional (VMSP) 2023 y
        Veeam Technical Sales Professional (VMTSP) están diseñados para ayudarte
        a obtener un entrenamiento en el portafolio de esta gran tecnología.
        VMSP y VMTSP 2023 son cursos fáciles de completar que elevarán tu
        estatus como asesor confiable para clientes, ampliarán tu conocimiento
        de la industria y te permitirán mantenerte al tanto de las tendencias
        tecnológicas en evolución.
      </p>
      <p style="margin-bottom: 2%; font-weight: bold">
        ¿Quieres aprender a respaldar y recuperar datos críticos? ¡Entonces este
        curso está hecho para ti!
      </p>
    </div>
    <div style="text-align: center; margin-top: 10%" class="btn-route">
      <img src="@/assets/img/btn-registro.png" alt="" style="width: 35%" @click="registro()" />
    </div>
    <div style="margin-top: 5%; text-align: center"><img src="@/assets/img/puntos.png" style="width: 30%"></div>
    <div class="text-izq-sup-destacado-mobil">
      <p style="margin-bottom: 2%; font-weight: bold">
        Lo destacado del curso:
      </p>
      <p style="margin-bottom: 2%;">
      <ul style="padding-left: 5%;">
        <li>Aprenderás de expertos
          en la industria que han
          estado en la vanguardia de
          protección de datos.
        </li>
        <li>Sumérgete en casos de
          estudio del mundo real y
          escenarios desafiantes que
          te prepararán para
          situaciones del mundo
          laboral.
        </li>
        <li>Obtén acceso a recursos
          exclusivos de Veeam
        </li>
      </ul>
      </p>
    </div>
    <div style="padding: 0% 15%">
      <div class="plataforma-mobil">
        <p style="margin-bottom: 2%; text-align: center">
          <span style="font-weight: bold">Plataforma</span>:
          <br>
          Todos los módulos
          se llevarán a cabo de manera
          virtual a través del portal de
          Veeam.
        </p>

      </div>
    </div>
    <div style="padding: 10%">
      <img src="@/assets/img/veeam_movil/chica2.png" style="width: 100%">
    </div>
    <div style="background-color: gainsboro; padding: 5% 10%">
      <p class="title">Certificación</p>
      <div style="border-radius: 10px; background-color: white; padding: 5%; font-size: 15px">
        <p style="margin-bottom: 5%;">
          Al finalizar con éxito los módulos
          de cada certificado, recibirás un
          diploma avalado por Veeam y
          Fundación Kooltivo.
        </p>
        <p style="margin-bottom: 5%;color: blue;">
          ¡Los cursos son totalmente
          gratuitos!
        </p>
        <p class="title">
          Temas que se
          abordarán:
        </p>
        <p>
          A partir de esta serie de cursos
          aprenderás a crear soluciones
          de copias de seguridad,
          recuperación y gestión de datos
          con una única plataforma para
          entornos cloud, virtuales, físicos,
          Software as a Service y
          Kubernetes+ (contenedores).
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    registro() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
    scrollToElement(elemento) {
      // Obten el elemento con el ID "elementoDestino"
      const elementoDestino = document.getElementById(elemento);

      // Verifica si el elemento existe
      if (elementoDestino) {
        // Utiliza el método scrollIntoView para desplazarte al elemento
        elementoDestino.scrollIntoView({ behavior: "smooth" }); // Puedes ajustar el comportamiento de desplazamiento según tus preferencias
      }
    },
  },
};
</script>

<style scoped>
.btn-route:hover {
  transform: scale(1.1);
}

.desktop {
  display: block;
}

.mobil {
  display: none;
}

.container-main {
  width: 100%;
  position: relative;

}

.container-text-main {
  position: absolute;
  top: 5%;
  font-size: 1.7vw;
  width: 50%;
  left: 5%;
  padding: 0% 0%;

}

.text-izq-sup-destacado {
  position: absolute;
  top: 59%;
  font-size: 1.5vw;
  width: 30%;

  left: 7%;
  padding: 4%;
  text-align: justify;
}

.plataforma {
  position: absolute;
  top: 87%;
  font-size: 1.5vw;
  width: 23%;

  left: 11%;
  color: white;
  text-align: justify;
}

.certificacion {
  position: absolute;
  top: 59%;
  font-size: 1.5vw;
  width: 31%;

  left: 66%;
  padding: 2%;
  text-align: justify;
}

.title {
  font-size: 2vw
}

@media (max-width: 1440px) {
  .container-main {
    width: 100%;
    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;
    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }

}

@media (max-width: 1320px) {
  .container-main {
    width: 100%;

    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;

    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }


}

@media (max-width: 1000px) {
  .container-main {
    width: 100%;

    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;

    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }


}

@media (max-width: 1024px) {
  .container-main {
    width: 100%;

    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;

    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }


}

@media (max-width: 817px) {
  .container-main {
    width: 100%;

    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;

    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }


}

@media (max-width: 768px) {
  .container-main {
    width: 100%;

    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 0%;

    width: 50%;

    left: 5%;
    height: 85%;
    padding: 8% 0%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;

    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;

    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;

    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }


}

@media (max-width: 600px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    width: 100%;

    height: 300vh;
  }

  .container-text-main-mobil {
    background-color: gainsboro;
    font-size: 15px;

    border-radius: 20px;
    padding: 5% 10%;
    text-align: justify;
  }

  .text-izq-sup-destacado-mobil {

    font-size: 15px;



    padding: 10%;
    text-align: justify;
  }

  .plataforma-mobil {
    padding: 3%;
    font-size: 15px;
    background: linear-gradient(to right, #84c5c9, #0561a8);
    border-radius: 10px;
    color: white;
    text-align: justify;
  }


  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5%
  }
}

@media (max-width: 430px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    width: 100%;

    height: 280vh;
  }

  .container-text-main-mobil {
    background-color: gainsboro;
    font-size: 15px;

    border-radius: 20px;
    padding: 5% 10%;
    text-align: justify;
  }

  .text-izq-sup-destacado-mobil {

    font-size: 15px;



    padding: 10%;
    text-align: justify;
  }

  .plataforma-mobil {
    padding: 3%;
    font-size: 15px;
    background: linear-gradient(to right, #84c5c9, #0561a8);
    border-radius: 10px;
    color: white;
    text-align: justify;
  }


  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5%
  }
}

@media (max-width: 414px) {
  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }

  .container-main {
    width: 100%;

    height: 280vh;
  }

  .container-text-main-mobil {
    background-color: gainsboro;
    font-size: 15px;

    border-radius: 20px;
    padding: 5% 10%;
    text-align: justify;
  }

  .text-izq-sup-destacado-mobil {

    font-size: 15px;



    padding: 10%;
    text-align: justify;
  }

  .plataforma-mobil {
    padding: 3%;
    font-size: 15px;
    background: linear-gradient(to right, #84c5c9, #0561a8);
    border-radius: 10px;
    color: white;
    text-align: justify;
  }


  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5%
  }
}

@media (max-width: 393px) {
  .container-main {
    width: 100%;
    height: 295vh;
    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 6%;
    font-size: 7px;
    width: 50%;

    left: 5%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;
    font-size: 6px;
    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }

  .title {
    font-size: 8px
  }
}

@media (max-width: 375px) {
  .container-main {
    width: 100%;
    height: 330vh;
    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 6%;
    font-size: 7px;
    width: 50%;

    left: 5%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;
    font-size: 6px;
    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }

  .title {
    font-size: 8px
  }
}

@media (max-width: 360px) {
  .container-main {
    width: 100%;
    height: 310vh;
    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 6%;
    font-size: 7px;
    width: 50%;

    left: 5%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;
    font-size: 6px;
    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;
    font-size: 6px;
    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }

  .title {
    font-size: 8px
  }
}

@media (max-width: 320px) {
  .container-main {
    width: 100%;
    height: 50vh;
    position: relative;

  }

  .container-text-main {
    position: absolute;
    top: 6%;
    font-size: 6px;
    width: 50%;

    left: 5%;
  }

  .text-izq-sup-destacado {
    position: absolute;
    top: 59%;
    font-size: 5px;
    width: 30%;

    left: 7%;
    padding: 4%;
    text-align: justify;
  }

  .plataforma {
    position: absolute;
    top: 87%;
    font-size: 5px;
    width: 23%;

    left: 11%;
    color: white;
    text-align: justify;
  }

  .certificacion {
    position: absolute;
    top: 59%;
    font-size: 5px;
    width: 31%;

    left: 66%;
    padding: 2%;
    text-align: justify;
  }

  .title {
    font-size: 7px
  }
}
</style>

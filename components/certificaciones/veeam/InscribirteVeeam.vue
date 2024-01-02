<template>
  <div class="container-main">
    <img src="@/assets/img/veeam/chica.png" alt="" style="width: 100%; height: 100%" />
    <div style="
              position: absolute;
              top: 18%;
              width: 45%;
              height: 81%;
              right: 10%;
              padding: 4% 1% 5%;
            ">
      <span class="title"> Cómo inscribirse</span>
      <br />
      <ul style="list-style-type: none; margin-bottom: 5%" class="text">
        <li>
          1.Visita nuestro sitio web:
          <a href="https://www.kooltivo.org/">https://www.kooltivo.org/</a>
        </li>
        <li>2.Selecciona el curso de certificación de Veeam.</li>
        <li>3.Completa el formulario de inscripción en linea.</li>
        <li>
          4.Recibirás un correo electrónico de confirmación con detalles sobre
          cómo acceder a los cursos.
        </li>
        <li>
          5.Con la información recibida en el correo, llena un segundo registro
          en el portal de Veeam.
        </li>
        <li>
          6.Prepárate para un emocionante viaje hacia el dominio de la
          protección de datos.
        </li>
        <br />
        <span style="font-weight: bold">Prepárate para Convertirte en un Experto en Protección de Datos</span>
        <br />
        <p>
          La protección de datos es esencial en la era digital, y con esta
          certificación, estarás equipado para enfrentar los desafíos actuales y
          futuros en la gestión de datos. En Fundación Kooltivo, estamos
          comprometidos a impulsar tu éxito en la protección de datos. ¡Te
          esperamos en el curso de certificación de Veeam!
        </p>
        <br />
        <p>
          Para cualquier consulta o para obtener más información, no dudes en
          ponerte en contacto con nosotros a través de
          <a href="mailto:contacto@kooltivo.org">contacto@kooltivo.org</a>
        </p>
      </ul>
      <div style="text-align: center" class="btn-route">
        <img src="@/assets/img/btn-registro.png" alt="" style="width: 30%" @click="registro()" />
      </div>
    </div>
  </div>
</template>



<style scoped>
.btn-route {
  transition: all 0.3s ease;
  /* Agregar una transición suave */
}

.btn-route:hover {
  transform: scale(1.1);
}

.container-main {
  padding: 5% 7%;
  width: 100%;
  height: auto;
  position: relative;
}

.title {
  font-weight: bold;
  font-size: 1.8vw;
}

.text {
  font-size: 1.3vw;
}
</style>
<script>
export default {
  methods: {
    registro() {
      window.open("http://54.209.58.195/#/sign-in", "_blank");
    },
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>

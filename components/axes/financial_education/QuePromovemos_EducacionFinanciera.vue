<template>
  <v-row no-gutters class="justify-center align-center container-main">
    <v-col cols="12" class="text-center" style="width: 100%; height: 100%">
      <div class="container" style="width: 100%; height: 100%">
        <div class="container-todo" style="width: 100%; height: 100%">
          <p class="title">¿Qué Promovemos?</p>
          <p class="text">
            Conscientes de que el manejo adecuado de recursos económicos es
            vital para el crecimiento personal y comunitario, realizamos
            talleres y asesorías para enseñarte a cómo administrar tus finanzas
            de manera responsable y efectiva.
          </p>

          <div class="container-img">
            <img class="img" src="@/assets/img/puntos.png" alt=""/>
          </div>
        </div>
      </div>
    </v-col>
  </v-row>
</template>

<style scoped>
.container-main {
  width: 100%;
  margin-top: 5%;
}

.container {
  padding: 5% 10%;
}

.container-todo {
  border-radius: 2vw;
  padding: 3%;
  box-shadow: 10px 10px 5px #888888; /* Sombra hacia la derecha y abajo */
  border: solid rgb(46, 45, 45) 1px;
}

.title {
  font-size: 2.5vw;
  font-weight: bold;
}

.text {
  font-size: 1.8vw;
  text-align: center;
}

.container-img {
  margin-top: 2%;
}

.img {
  width: 10%;
}

</style>

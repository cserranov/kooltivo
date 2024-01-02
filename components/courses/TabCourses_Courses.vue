<template>
  <div style="display: flex; margin-top: 5%">
    <div class="container-title-linea">
      <p class="title">CERTIFICACIONES</p>
    </div>
    <div class="container-linea">
      <img src="@/assets/img/linea_gris_ejes.png" alt="" style="width: 100%" />
    </div>
  </div>
  <div class="container">
    <div class="container-title desktop">
      <v-tabs v-model="tab">
        <v-tab
          style="flex: 1"
          value="one"
          :class="{ 'tab-1': tab === 'one', 'tab-2': tab !== 'one' }"
          @click="tab = 'one'"
          id="space-tabs"
          >VEEAM
        </v-tab>
        <v-tab
          style="flex: 1"
          value="two"
          :class="{ 'tab-1': tab === 'two', 'tab-2': tab !== 'two' }"
          @click="tab = 'two'"
          id="space-tabs"
          >AUTOMATION ANYWHERE
        </v-tab>
        <v-tab
          style="flex: 1"
          value="four"
          :class="{ 'tab-1': tab === 'four', 'tab-2': tab !== 'four' }"
          @click="tab = 'four'"
          >MICRO FOCUS
        </v-tab>
      </v-tabs>
      <div>
        <v-window v-model="tab">
          <v-window-item value="one">
            <div class="container-courses">
              <p>
                <span class="title-course" style="text-transform: uppercase"
                  >Veeam
                  <br />
                  Domina la Protección y Resiliencia de Datos como un
                  Experto</span
                >
                <br />
                <br />
                <span class="subtitle-course" style="text-transform: uppercase"
                  >Respaldo de datos (Data Cloud Managenent)</span
                >
                <br />
                <br />
                <span class="content">
                  <span style="font-weight: bold">Descripción</span>: Con esta
                  serie de cursos, tus habilidades en protección de datos se
                  transformarán en superpoderes digitales. La fundación Kooltivo
                  está entusiasmada en presentarte una experiencia de
                  aprendizaje única que te llevará al siguiente nivel en la
                  gestión de datos y la seguridad digital.
                  <br />
                  <br />
                  <span style="font-weight: bold">Fecha de inicio</span>:
                  Siempre disponible <br /><br />
                  <span style="font-weight: bold">Duración</span>: Un mes cada
                  uno. Estos cursos tienen un formato on-demand*
                  <br />
                  <br />
                  <span style="font-weight: bold">Plataforma</span>: Todos los
                  módulos se llevarán a cabo de manera virtual a través del
                  portal de Veeam
                  <br />
                  <br />
                  <span style="font-weight: bold">Certificación</span>: Al
                  finalizar con éxito los módulos de cada certificado, recibirás
                  un diploma avalado por Veeam y Fundación Kooltivo
                  <br />
                  <br />
                  <span style="font-weight: bold">Requisitos</span>:
                  <br />
                  <ul style="padding: 0% 2%">
                    <li>Inglés intermedio</li>
                    <li>
                      Orientado a alumnos de ingeniería, tecnología, sistemas o
                      afines
                    </li>
                    <li>Conocimiento básico sobre virtualización</li>
                  </ul>
                </span>
              </p>
              <p class="final">
                ¡Quiero ser un experto en protección de datos!
              </p>
              <div style="text-align: center; margin-top: 5%">
                <button @click="navigateTo('/certificaciones/veeam')">
                  <img
                    src="@/assets/img/cursos/veeam.png"
                    alt=""
                    style="width: 30%"
                  />
                </button>
              </div>
            </div>
            <div class="tiempo" style="text-align: center; position: relative">
              <p>
                Puedes hacerlos a tu tiempo. Tienes un mes para completarlos
              </p>
              <img
                src="@/assets/img/cursos/amarilla.png"
                alt=""
                class="linea"
              />
            </div>
          </v-window-item>
          <v-window-item value="two">
            <div class="container-courses">
              <p>
                <span class="title-course" style="text-transform: uppercase"
                  >Automation Anywhere
                  <br />
                  Transforma Tareas Rutinarias en Eficiencia
                </span>
                <br />
                <br />
                <span class="subtitle-course" style="text-transform: uppercase"
                  >Procesos de Automatización
                </span>
                <br />
                <br />
                <span class="content">
                  <span style="font-weight: bold">Descripción</span>: La
                  automatización de procesos robóticos (RPA) es el futuro de la
                  eficiencia operativa en el mundo empresarial. Si deseas
                  aprender a identificar y automatizar procesos repetitivos, ¡Te
                  damos la bienvenida al Curso de Automation Anywhere!
                  <br />
                  <br />
                  Este curso te proporcionará las habilidades necesarias para
                  dominar esta herramienta y aprovechar su potencial para
                  optimizar operaciones diversas.
                  <br />
                  <br />
                  <span style="font-weight: bold">Fecha de inicio</span>: 23 de
                  octubre de 2023
                  <br />
                  <br />
                  <span style="font-weight: bold">Duración</span>: 6 semanas (2
                  semanas para tomar los cursos online en formato on-demand*; 1
                  semana de entrenamiento en formato híbrido; una sesión
                  práctica presencial y 3 semanas para completar proyecto
                  individual de beneficio comunitario)
                  <br />
                  <br />
                  <span style="font-weight: bold">Plataforma</span>: Los cursos
                  on-demand se llevarán a cabo de manera virtual a través del
                  portal de Automation Anywhere
                  <br />
                  <br />
                  <span style="font-weight: bold">Requisitos</span>:
                  <br />
                  <ul style="padding: 0% 2%">
                    <li>Inglés intermedio o avanzado.</li>
                    <li>
                      Preferiblemente, estudiantes en los últimos semestres o
                      egresados de ingeniería, informática, contabilidad o
                      administración; así como profesionales del área
                      tecnológica.
                    </li>
                  </ul>
                  <br />
                  <br />
                  <span style="font-weight: bold">Además</span>:
                  <br />
                  <ul style="padding: 0% 2%">
                    <li>
                      <span style="font-weight: bold">Sesión práctica</span>
                      para aplicar lo que aprendas en tu proyecto específico.
                    </li>
                    <li>
                      Al terminar, tendrás la oportunidad de participar en un
                      <span style="font-weight: bold">evento especial</span> con
                      distinguidos expertos del ámbito empresarial.
                    </li>
                    <li>
                      Recibirás un
                      <span style="font-weight: bold">certificado</span> por
                      parte de Kooltivo y Automation Anywhere con el cual podrás
                      avalar el haber completado estos cursos y el nuevo
                      aprendizaje adquirido.
                    </li>
                  </ul>
                </span>
              </p>
              <p class="final">¡Quiero destacar en automatización!</p>
              <div style="text-align: center; margin-top: 5%">
                <button @click="navigateTo('/certificaciones/automation')">
                  <img
                    src="@/assets/img/cursos/auto.png"
                    alt=""
                    style="width: 30%"
                  />
                </button>
              </div>
            </div>

            <div class="tiempo" style="text-align: center; position: relative">
              <p>
                *Puedes hacerlos a tu tiempo. Tienes 3 semanas para completarlos
              </p>
              <img
                src="@/assets/img/cursos/amarilla.png"
                alt=""
                class="linea"
              />
            </div>
          </v-window-item>

          <v-window-item value="four">
            <div class="container-courses">
              <p>
                <span class="title-course" style="text-transform: uppercase"
                  >Micro Focus
                  <br />
                  Potenciando tu Expertise en Tecnología y Seguridad</span
                >
                <br />
                <br />
                <span class="subtitle-course" style="text-transform: uppercase"
                  >Preparando a las Empresas para la Transformación Digital
                </span>
                <br />
                <br />
                <span class="content">
                  <span style="font-weight: bold">Descripción</span>: La
                  transformación digital es el motor que impulsa a las empresas
                  hacia el futuro. En este emocionante viaje hacia la innovación
                  y la eficiencia, te invitamos a participar en los cursos de
                  MicroFocus. Estas oportunidades de aprendizaje te prepararán
                  para liderar la revolución digital y destacar en tu carrera.
                  <br />
                  <br />
                  <span style="font-weight: bold"
                    >Cuentas con tres opciones</span
                  >:
                  <br />
                  1. Configuración de activos de Tecnologías de la Información
                  (TI).
                  <br />
                  2. Automatización, integración y organización de cualquier
                  proceso de TI.
                  <br />
                  3. Evalucación de errores, seguimiento, validación,
                  automatización y gestión de las actividades de seguridad del
                  software.
                  <br />
                  <br />
                  <span style="font-weight: bold">Fecha de inicio</span>:
                  Siempre disponible. <br /><br />
                  <span style="font-weight: bold">Duración</span>: Un mes cada
                  uno. Estos cursos tienen un formato on-demand*.
                  <br />
                  <br />
                  <span style="font-weight: bold">Plataforma</span>: Todos los
                  cursos se llevarán a cabo de manera virtual a través del
                  portal de Micro Focus.
                  <br />
                  <br />
                  <span style="font-weight: bold">Requisitos</span>:
                  <br />
                  <ul style="padding: 0% 2%">
                    <li>
                      Perfil Ideal: Personas con conocimiento de programación,
                      tecnología, sistemas, o experiencia en la industria;
                      estudiantes o graduados de ingenierías o licenciaturas
                      relacionadas con la tecnología; así como profesionales en
                      áreas relacionadas con sistemas y tecnología.
                    </li>
                    <li>Nivel de Inglés intermedio.</li>
                    <li>
                      Experiencia en el uso de herramientas de productividad
                      como Excel.
                    </li>
                    <li>
                      Familiaridad con al menos un lenguaje de programación.
                    </li>
                    <li>
                      Conocimiento del argot tecnológico y la capacidad de
                      comprender y comunicarse eficazmente en términos técnicos.
                    </li>
                  </ul>
                  <br />
                  <br />
                  <span style="font-weight: bold">Además</span>... <br />Todos
                  los Al finalizar cada módulo deberás presentar un examen de
                  conocimientos. Una vez aprobados recibirás una certificación
                  por parte de Micro Focus y Fundación Kooltivo que respalda tus
                  conocimientos y experiencia.
                </span>
              </p>
              <p class="final">
                ¡Quiero prepararme para liderar la transformación digital!
              </p>
              <div style="text-align: center; margin-top: 5%">
                <button @click="navigateTo('/certificaciones/microfocus')">
                  <img
                    src="@/assets/img/cursos/micro.png"
                    alt=""
                    style="width: 30%"
                  />
                </button>
              </div>
            </div>

            <div class="tiempo" style="text-align: center; position: relative">
              <p>
                Puedes hacerlos a tu tiempo. Tienes un mes para completar cada
                uno de los módulos
              </p>
              <img
                src="@/assets/img/cursos/amarilla.png"
                alt=""
                class="linea"
              />
            </div>
          </v-window-item>
        </v-window>
      </div>
    </div>

    <div class="container-title mobil">
      <div style="margin-bottom: 5%">
        <div
          style="display: flex; justify-content: center; align-items: center"
        >
          <div
            style="
              width: 60%;
              height: 70px;
              display: flex;
              justify-content: center;
              align-items: center;
              border-radius: 20px;
              background-image: linear-gradient(to right, #318ae0, #3eb9f4);
              color: white;
              font-size: 15px;
              font-weight: bold;
            "
            @click="cambio_veeam()"
          >
            <p>Veeam</p>
          </div>
        </div>
        <div v-if="veeam">
          <div class="container-courses">
            <p>
              <span class="title-course" style="text-transform: uppercase"
                >Veeam
              </span>
              <br />
              <br />
              <span
                style="text-transform: uppercase; font-weight: bold"
                class="letra-mobil"
              >
                Domina la Protección
                <br />
                y Resiliencia de Datos
                <br />
                como un Experto</span
              >

              <br />
              <br />
              <span class="subtitle-course" style="text-transform: uppercase"
                >Respaldo de datos (Data Cloud Managenent)</span
              >
              <br />
              <br />
              <span class="content">
                <span style="font-weight: bold">Descripción</span>: Con esta
                serie de cursos, tus habilidades en protección de datos se
                transformarán en superpoderes digitales. La fundación Kooltivo
                está entusiasmada en presentarte una experiencia de aprendizaje
                única que te llevará al siguiente nivel en la gestión de datos y
                la seguridad digital.
                <br />
                <br />
                <span style="font-weight: bold">Fecha de inicio</span>: Siempre
                disponible. <br /><br />
                <span style="font-weight: bold">Duración</span>: Un mes cada
                uno. Estos cursos tienen un formato on-demand*.
                <br />
                <br />
                <span style="font-weight: bold">Plataforma</span>: Todos los
                módulos se llevarán a cabo de manera virtual a través del portal
                de Veeam.
                <br />
                <br />
                <span style="font-weight: bold">Certificación</span>: Al
                finalizar con éxito los módulos de cada certificado, recibirás
                un diploma avalado por Veeam y Fundación Kooltivo.
                <br />
                <br />
                <span style="font-weight: bold">Requisitos</span>:
                <br />
                <ul style="padding: 0% 2%">
                  <li>Inglés intermedio.</li>
                  <li>
                    Orientado a alumnos de ingeniería, tecnología, sistemas o
                    afines.
                  </li>
                  <li>Conocimiento básico sobre virtualización.</li>
                </ul>
              </span>
            </p>
            <p class="final">¡Quiero ser un experto en protección de datos!</p>
            <div style="text-align: center; margin-top: 5%">
              <button @click="navigateTo('/certificaciones/veeam')">
                <img
                  src="@/assets/img/cursos/veeam.png"
                  alt=""
                  style="width: 40%"
                />
              </button>
            </div>
          </div>
          <div class="tiempo" style="text-align: center; position: relative">
            <p>
              Puedes hacerlos a tu tiempo.
              <br />
              Tienes un mes para completarlos
            </p>
            <img src="@/assets/img/cursos/amarilla.png" alt="" class="linea" />
          </div>
        </div>
      </div>

      <div style="margin-bottom: 5%">
        <div
          style="display: flex; justify-content: center; align-items: center"
        >
          <div
            style="
              width: 60%;
              height: 70px;
              display: flex;
              justify-content: center;
              align-items: center;
              border-radius: 20px;
              background-image: linear-gradient(to right, #318ae0, #3eb9f4);
              color: white;
              font-size: 15px;
              font-weight: bold;
            "
            @click="cambio_auto()"
          >
            <p>Automation Anywhere</p>
          </div>
        </div>
        <div v-if="auto">
          <div class="container-courses">
            <p>
              <span class="title-course" style="text-transform: uppercase"
                >Automation Anywhere
              </span>

              <br />
              <br />
              <span
                style="
                  text-transform: uppercase;

                  font-weight: bold;
                "
                class="letra-mobil"
              >
                Transforma Tareas
                <br />
                Rutinarias en Eficiencia</span
              >
              <br />
              <br />
              <span class="subtitle-course" style="text-transform: uppercase"
                >Procesos de Automatización
              </span>
              <br />
              <br />
              <span class="content">
                <span style="font-weight: bold">Descripción</span>: La
                automatización de procesos robóticos (RPA) es el futuro de la
                eficiencia operativa en el mundo empresarial. Si deseas aprender
                a identificar y automatizar procesos repetitivos, ¡Te damos la
                bienvenida al Curso de Automation Anywhere!.
                <br />
                <br />
                Este curso te proporcionará las habilidades necesarias para
                dominar esta herramienta y aprovechar su potencial para
                optimizar operaciones diversas.
                <br />
                <br />
                <span style="font-weight: bold">Fecha de inicio</span>: 23 de
                octubre de 2023.
                <br />
                <br />
                <span style="font-weight: bold">Duración</span>: 6 semanas (2
                semanas para tomar los cursos online en formato on-demand*; 1
                semana de entrenamiento en formato híbrido; una sesión práctica
                presencial y 3 semanas para completar proyecto individual de
                beneficio comunitario).
                <br />
                <br />
                <span style="font-weight: bold">Plataforma</span>: Los cursos
                on-demand se llevarán a cabo de manera virtual a través del
                portal de Automation Anywhere.
                <br />
                <br />
                <span style="font-weight: bold">Requisitos</span>:
                <br />
                <ul style="padding: 0% 2%">
                  <li>Inglés intermedio o avanzado.</li>
                  <li>
                    Preferiblemente, estudiantes en los últimos semestres o
                    egresados de ingeniería, informática, contabilidad o
                    administración; así como profesionales del área tecnológica.
                  </li>
                </ul>
                <br />
                <br />
                <span style="font-weight: bold">Además</span>:
                <br />
                <ul style="padding: 0% 2%">
                  <li>
                    <span style="font-weight: bold">Sesión práctica</span>
                    para aplicar lo que aprendas en tu proyecto específico.
                  </li>
                  <li>
                    Al terminar, tendrás la oportunidad de participar en un
                    <span style="font-weight: bold">evento especial</span> con
                    distinguidos expertos del ámbito empresarial.
                  </li>
                  <li>
                    Recibirás un
                    <span style="font-weight: bold">certificado</span> por parte
                    de Kooltivo y Automation Anywhere con el cual podrás avalar
                    el haber completado estos cursos y el nuevo aprendizaje
                    adquirido.
                  </li>
                </ul>
              </span>
            </p>
            <p class="final">¡Quiero destacar en automatización!</p>
            <div style="text-align: center; margin-top: 5%">
              <button @click="navigateTo('/certificaciones/automation')">
                <img
                  src="@/assets/img/cursos/auto.png"
                  alt=""
                  style="width: 40%"
                />
              </button>
            </div>
          </div>
          <div class="tiempo" style="text-align: center; position: relative">
            <p>
              *Puedes hacerlos a tu tiempo.
              <br />
              Tienes 3 semanas para completarlos
            </p>
            <img src="@/assets/img/cursos/amarilla.png" alt="" class="linea" />
          </div>
        </div>
      </div>



      <div style="margin-bottom: 5%">
        <div
          style="display: flex; justify-content: center; align-items: center"
        >
          <div
            style="
              width: 60%;
              height: 70px;
              display: flex;
              justify-content: center;
              align-items: center;
              border-radius: 20px;
              background-image: linear-gradient(to right, #318ae0, #3eb9f4);
              color: white;
              font-size: 15px;
              font-weight: bold;
            "
            @click="cambio_micro()"
          >
            <p>Micro Focus</p>
          </div>
        </div>
        <div v-if="micro">
          <div class="container-courses">
            <p>
              <span class="title-course" style="text-transform: uppercase"
                >Micro Focus
              </span>
              <br />
              <br />
              <span
                style="text-transform: uppercase; font-weight: bold"
                class="letra-mobil"
              >
                Potenciando tu Expertise
                <br />
                en Tecnología y Seguridad</span
              >
              <br />
              <br />
              <span class="subtitle-course" style="text-transform: uppercase"
                >Preparando a las Empresas para la Transformación Digital
              </span>
              <br />
              <br />
              <span class="content">
                <span style="font-weight: bold">Descripción</span>: La
                transformación digital es el motor que impulsa a las empresas
                hacia el futuro. En este emocionante viaje hacia la innovación y
                la eficiencia, te invitamos a participar en los cursos de
                MicroFocus. Estas oportunidades de aprendizaje te prepararán
                para liderar la revolución digital y destacar en tu carrera.
                <br />
                <br />
                <span style="font-weight: bold">Cuentas con tres opciones</span
                >:
                <br />
                1. Configuración de activos de Tecnologías de la Información
                (TI).
                <br />
                2. Automatización, integración y organización de cualquier
                proceso de TI.
                <br />
                3. Evalucación de errores, seguimiento, validación,
                automatización y gestión de las actividades de seguridad del
                software.
                <br />
                <br />
                <span style="font-weight: bold">Fecha de inicio</span>: Siempre
                disponible. <br /><br />
                <span style="font-weight: bold">Duración</span>: Un mes cada
                uno. Estos cursos tienen un formato on-demand*.
                <br />
                <br />
                <span style="font-weight: bold">Plataforma</span>: Todos los
                cursos se llevarán a cabo de manera virtual a través del portal
                de Micro Focus.
                <br />
                <br />
                <span style="font-weight: bold">Requisitos</span>:
                <br />
                <ul style="padding: 0% 2%">
                  <li>
                    Perfil Ideal: Personas con conocimiento de programación,
                    tecnología, sistemas, o experiencia en la industria;
                    estudiantes o graduados de ingenierías o licenciaturas
                    relacionadas con la tecnología; así como profesionales en
                    áreas relacionadas con sistemas y tecnología.
                  </li>
                  <li>Nivel de Inglés intermedio.</li>
                  <li>
                    Experiencia en el uso de herramientas de productividad como
                    Excel.
                  </li>
                  <li>
                    Familiaridad con al menos un lenguaje de programación.
                  </li>
                  <li>
                    Conocimiento del argot tecnológico y la capacidad de
                    comprender y comunicarse eficazmente en términos técnicos.
                  </li>
                </ul>
                <br />
                <br />
                <span style="font-weight: bold">Además</span>... <br />Todos los
                Al finalizar cada módulo deberás presentar un examen de
                conocimientos. Una vez aprobados recibirás una certificación por
                parte de Micro Focus y Fundación Kooltivo que respalda tus
                conocimientos y experiencia.
              </span>
            </p>
            <p class="final">
              ¡Quiero prepararme para liderar la transformación digital!
            </p>
            <div style="text-align: center; margin-top: 5%">
              <button @click="navigateTo('/certificaciones/microfocus')">
                <img
                  src="@/assets/img/cursos/micro.png"
                  alt=""
                  style="width: 40%"
                />
              </button>
            </div>
          </div>
          <div class="tiempo" style="text-align: center; position: relative">
            <p>
              Puedes hacerlos a tu tiempo.
              <br />
              Tienes un mes para completar cada módulos
            </p>
            <img src="@/assets/img/cursos/amarilla.png" alt="" class="linea" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    tab: "one", // Establece la pestaña predeterminada
    veeam: false,
    microsoft: false,
    micro: false,
    auto: false,
  }),
  methods: {
    cambio_microsoft() {
      this.microsoft = !this.microsoft;
    },
    cambio_micro() {
      this.micro = !this.micro;
    },
    cambio_veeam() {
      this.veeam = !this.veeam;
    },
    cambio_auto() {
      this.auto = !this.auto;
    },
    navigateTo(path) {
      this.$router.push(path);
    },
  },
};
</script>

<style scoped>
.container-title-linea {
  width: 23%;
  padding-left: 5%;
  display: flex;
  align-items: center;
}

.container-linea {
  width: 77%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.desktop {
  display: block;
}

.mobil {
  display: none;
}

.container {
  padding: 5% 5% 3%;
}

.container-title {
  padding: 0px 50px;
  text-align: start;
  /* margin-bottom: 50px; */
}

.title {
  font-size: 30px;
  color: #8a8a8a;
  font-weight: 600;
}

.tab-1 {
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  background-image: linear-gradient(to right, #318ae0, #3eb9f4);
  color: white;
  font-size: 1.2vw;
}

.tab-2 {
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
  color: black;
  font-size: 1.2vw;
}

.container-courses {
  background-color: #eeecec;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 50px;
  padding: 50px;
  text-align: justify;
}

.title-course {
  font-size: 35px;
  font-weight: bold;
  text-align: start;
}

.subtitle-course {
  font-size: 30px;
  color: #318ae0;
}

.content {
  font-size: 25px;
}

.final {
  margin-top: 100px;
  font-size: 25px;
  text-align: center;
}

.tiempo {
  margin-top: 50px;
  font-size: 20px;
}

.linea {
  width: 35%;
  position: absolute;
  top: 40%;
  left: 33%;
}

#space-tabs {
  /* margin-right: px; */
  padding: 0px 30px;
}

@media (max-width: 1440px) {
  .container-title-linea {
    width: 30%;
    padding-left: 7%;
    display: flex;
    align-items: center;
  }

  .container-linea {
    width: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 30px;
  }



  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;

  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 50px;
  }

  .title-course {
    font-size: 25px;
  }

  .subtitle-course {
    font-size: 30px;
  }

  .content {
    font-size: 25px;
  }

  .final {
    margin-top: 100px;
    font-size: 25px;
    text-align: center;
  }

  .tiempo {
    margin-top: 50px;
    font-size: 20px;

    height: 50px;
  }

  .linea {
    width: 52%;
    position: absolute;
    top: 40%;
    left: 24%;
  }

  #space-tabs {
    /* margin-right: px; */

    padding: 0px 40px;
  }
}

@media (max-width: 1024px) {
  .container-title-linea {
    width: 30%;
    padding-left: 7%;
    display: flex;
    align-items: center;
  }

  .container-linea {
    width: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 25px;
  }




  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 28px;
  }

  .subtitle-course {
    font-size: 27px;
  }

  .content {
    font-size: 25px;
  }

  .final {
    margin-top: 10%;
    font-size: 25px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 20px;
  }

  #space-tabs {
    padding: 0px 30px;
  }
}

@media (max-width: 768px) {
  .container-title-linea {
    width: 40%;

    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea {
    width: 60%;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5% 5% 0%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 25px;
  }



  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;

  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 23px;
  }

  .subtitle-course {
    font-size: 20px;
  }

  .content {
    font-size: 18px;
  }

  .final {
    margin-top: 10%;
    font-size: 20px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 20px;
  }

  #space-tabs {
    padding: 0px 20px;
  }
}

@media (max-width: 600px) {
  .letra-mobil {
    font-size: 15px;
  }

  .desktop {
    display: none;
  }

  .mobil {
    display: block;
  }
}

@media (max-width: 425px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 18px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 20px;
  }

  .subtitle-course {
    font-size: 18px;
  }

  .content {
    font-size: 15px;
  }

  .final {
    margin-top: 10%;
    font-size: 18px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 12px;
  }

  .linea {
    width: 100%;
    position: absolute;
    top: 80%;
    left: 0%;
  }

  #space-tabs {
    padding: 0px 5px;
  }
}

@media (max-width: 375px) {
  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 15px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 17px;
  }

  .subtitle-course {
    font-size: 15px;
  }

  .content {
    font-size: 15px;
  }

  .final {
    margin-top: 10%;
    font-size: 15px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 15px;
  }

  #space-tabs {
    padding: 0px 40px;
  }
}

@media (max-width: 360px) {
  .letra-mobil {
    font-size: 14px;
  }
}

@media (max-width: 322px) {
  .container-title-linea {
    width: 50%;

    padding-left: 5%;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  .container-linea {
    width: 50%;

    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    padding: 5%;
  }

  .container-title {
    padding: 0% 2%;
    text-align: start;
    margin-bottom: 5%;
  }

  .title {
    font-size: 15px;
  }

  .tab-1 {
    font-size: 13px;
  }

  .tab-2 {
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
    color: black;
    font-size: 13px;
  }

  .container-courses {
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    padding: 5%;
  }

  .title-course {
    font-size: 15px;
  }

  .subtitle-course {
    font-size: 14px;
  }

  .content {
    font-size: 13px;
  }

  .final {
    margin-top: 10%;
    font-size: 15px;
    text-align: center;
  }

  .tiempo {
    margin-top: 8%;
    font-size: 15px;
  }

  #space-tabs {
    padding: 0px 40px;
  }
}
</style>

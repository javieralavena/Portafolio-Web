<template>
  <v-container fluid>
    <v-row no-gutters class="row">

      <v-col lg="6" class="col">

        <v-img contain lazy-src="https://picsum.photos/id/11/10/6" max-height="250" max-width="220" class=" foto-perfil"
          src="@/assets/1647356939400.jpg"></v-img>

        <v-card class="rectangulo text-center " max-width="480">
          <h1 class="nombre">Javiera Troncoso</h1>
          <h3 class="py-6 px-5">DESARROLLADORA WEB FRONT-END TRAINEE / INGENIERA CIVIL INDUSTRIAL</h3>
        </v-card>

        <div class="iconos d-flex justify-center ">
          <a href="https://www.linkedin.com/in/javieratroncosoaravena/" target="_blank"
            class="text-decoration-none ps-5">
            <v-icon large color="indigo">
              mdi-linkedin
            </v-icon>
          </a>

          <a href="https://github.com/javieralavena" target="_blank" class="text-decoration-none ps-5">
            <v-icon large color="black">
              mdi-github
            </v-icon>
          </a>

          <a href="https://www.instagram.com/javieralavena/" target="_blank" class="text-decoration-none ps-5">
            <v-icon large color="pink">
              mdi-instagram
            </v-icon>
          </a>

          <a href="mailto:javierabta97@gmail.com?" target="_blank" class="text-decoration-none ps-5">
            <v-icon large color="red">
              mdi-gmail
            </v-icon>
          </a>
        </div>

      </v-col>

      <v-col lg="6" class="col">

        <v-card class="card ms-5" max-width="100%" outlined>
          <v-list-item>
            <v-list-item-content>
              <h2 class=" mb-4">
                Sobre Mí 🤭
              </h2>
              <p class="text-justify">
                Hola, soy desarrolladora web Front-End Trainee e Ingeniera Civil Industrial, con conocimiento
                principalmente en <span>JavaScript</span>, <span>Sass</span> y <span>Vue js</span>.</p>
              <p class="text-justify">Me considero una persona que tiene facilidad para aprender cosas nuevas y
                comprometida con sus responsabilidades, lo que me ha hecho desarrollar la autogestión. Además, el haber
                estudiado una carrera me permitió
                desarrollar competencias tales como el trabajo en equipo, el pensamiento lógico y la resolución de
                problemas.</p>
              <p class="text-justify"> Me gusta mucho lo visual, que las cosas sean estéticamente atractivas y
                funcionales,
                por lo que quiero
                dedicarme a desarrollar páginas webs y aplicaciones con estas características, y que le faciliten la
                vida a las personas.
              </p>
            </v-list-item-content>
          </v-list-item>
        </v-card>

      </v-col>

    </v-row>
    <v-divider color="deep-purple accent-1" inset class="mr-16"></v-divider>
    <v-row>

      <v-col>

        <h1 class="nombre text-center pt-4"> ✨Mis Proyectos✨</h1>

        <v-slide-group v-model="model" class="pa-4" active-class="success" show-arrows>
          <v-slide-item v-slot="{ active, toggle }">
            <v-card :color="active ? undefined : 'grey lighten-1'" class="ma-4" max-width="344" @click="toggle">
              <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px"></v-img>

              <v-card-title>
                Top western road trips
              </v-card-title>

              <v-card-subtitle>
                1,000 miles of wonder
              </v-card-subtitle>
            </v-card>

          </v-slide-item>

          <v-slide-item v-slot="{ active, toggle }">
            <v-card :color="active ? undefined : 'grey lighten-1'" class="ma-4" max-width="344" @click="toggle">
              <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px"></v-img>

              <v-card-title>
                Top western road trips
              </v-card-title>

              <v-card-subtitle>
                1,000 miles of wonder
              </v-card-subtitle>
            </v-card>

          </v-slide-item>

          <v-slide-item v-slot="{ active, toggle }">
            <v-card :color="active ? undefined : 'grey lighten-1'" class="ma-4" max-width="344" @click="toggle">
              <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px"></v-img>

              <v-card-title>
                Top western road trips
              </v-card-title>

              <v-card-subtitle>
                1,000 miles of wonder
              </v-card-subtitle>
            </v-card>

          </v-slide-item>

          <v-slide-item v-slot="{ active, toggle }">
            <v-card :color="active ? undefined : 'grey lighten-1'" class="ma-4" max-width="344" @click="toggle">
              <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="200px"></v-img>

              <v-card-title>
                Top western road trips
              </v-card-title>

              <v-card-subtitle>
                1,000 miles of wonder
              </v-card-subtitle>
            </v-card>

          </v-slide-item>
        </v-slide-group>

      </v-col>
    </v-row>

  </v-container>



</template>

<script>
export default {
  name: 'view-home',
  // props: {},
  data: function () {
    return {}
  },
  // computed: {},
  methods: {
    // -- UI Modification
    // -- Data fetching
    // -- Data handling and transformations
    // -- Validations and Error handling
    // -- Other functions
    // -- Vuex mappings
  },
  // watch: {},
  // components: {},
  // mixins: [],
  // filters: {},
  // -- Lifecycle Methods
  // -- End Lifecycle Methods
}
</script>

<style scoped>
/*
    breakpoints
    xs: < 600px
    sm : 600px > < 960px
    md: 960px > < 1264px*
    lg: 1264px > < 1904px*
    xl : > 1904px*
*/

* {
  box-sizing: border-box;
  font-family: 'Merriweather', serif;
}

.row {
  margin-left: 70px;
  margin-right: 70px;
}

.col {
  height: 500px;
}

.foto-perfil {
  border-radius: 5%;
  z-index: 1;
  position: relative;
  top: 90px;
}

.rectangulo {
  background: radial-gradient(circle at top left, #af9dcc, #ffb5a6);
  position: relative;
  z-index: 0;
  left: 80px;
  top: -190px;
  padding-top: 30px;
  padding-left: 145px;
}

.nombre {
  font-size: 60px;
  line-height: normal;
}

.iconos {
  position: relative;
  top: -170px;
}

.card {
  margin-top: 60px;
  border-color: #af9dcc;
}

p {
  line-height: 1.5;
}

span {
  color: #8f80a7;
  font-weight: bold;
}
</style>

<template>
  <v-container fluid>
    <v-row no-gutters class="row">

      <v-col cols="12" lg="6">

        <CardImg></CardImg>
        <RedesContacto></RedesContacto>

      </v-col>

      <v-col cols="12" lg="6" class="col">

        <v-card class="card ms-5 mb-5" max-width="100%" outlined>
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
import CardImg from '@/components/CardImg.vue'
import RedesContacto from '@/components/RedesContacto.vue'
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
  components: {
    CardImg,
    RedesContacto
  },
  // mixins: [],
  // filters: {},
  // -- Lifecycle Methods
  // -- End Lifecycle Methods
}
</script>

<style scoped>
* {
  box-sizing: border-box;
  font-family: 'Merriweather', serif;
}

.cardm {
  margin-top: 60px;
  border-color: #af9dcc;
  margin-right: 70px;
}

p {
  line-height: 1.5;
}

span {
  color: #8f80a7;
  font-weight: bold;
}
</style>

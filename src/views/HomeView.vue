<template>
  <v-container fluid>
    <v-row no-gutters class="row">

      <v-col cols="12" lg="6">

        <CardImg></CardImg>
        <RedesContacto></RedesContacto>

      </v-col>

      <v-col cols="12" lg="6">

      <AboutMe class="d-none d-lg-flex"></AboutMe>

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
import AboutMe from '@/components/AboutMe.vue'
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
    RedesContacto,
    AboutMe
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
</style>

<template>
  <v-container fluid>
    <v-row no-gutters class="row">

      <v-col cols="12" lg="6">

        <CardImg></CardImg>
        <RedesContacto></RedesContacto>

      </v-col>

      <v-col cols="12" lg="6">

        <AboutMe class="d-none d-lg-flex"></AboutMe>
        <Desplegable class="d-lg-none d-xl-none"></Desplegable>

      </v-col>

    </v-row>

    <v-divider color="deep-purple accent-1" class="mx-md-16 mx-sm-16 mx-lg-16 mx-xl-16"></v-divider>

    <v-row>

      <Herramientas></Herramientas>

    </v-row>

    <v-divider color="deep-purple accent-1" class="mx-md-16 mx-sm-16 mx-lg-16 mx-xl-16"></v-divider>

    <v-row>

      <Proyectos></Proyectos>

    </v-row>

  </v-container>

</template>

<script>
import CardImg from '@/components/CardImg.vue'
import RedesContacto from '@/components/RedesContacto.vue'
import AboutMe from '@/components/AboutMe.vue'
import Desplegable from '@/components/AboutMeDesplegable.vue'
import Herramientas from '@/components/Herramientas.vue'
import Proyectos from '@/components/Proyectos.vue'
export default {
  name: 'view-home',
  // props: {},
  data: function () {
    return {}
  },
  methods: {
  },

  components: {
    CardImg,
    RedesContacto,
    AboutMe,
    Desplegable,
    Herramientas,
    Proyectos
  },
}
</script>

<style scoped>
* {
  box-sizing: border-box;
  font-family: 'Merriweather', serif;
}
</style>

<template>


    <v-col cols="12">

        <h1 class="nombre text-center py-10"> ✨Mis Proyectos✨</h1>

        <v-row class="mx-md-16 mx-sm-16 mx-lg-16 mx-xl-16 mb-5">

            <v-col cols="12" lg="4" md="6">
                <v-card class="mx-auto" max-width="344">

                    <v-img contain src="@/assets/alfaweb.png"  height="180px"></v-img>

                    <a href="https://javieralavena.github.io/alfaweb/" target="_blank" class="text-decoration-none">
                        <v-card-title class="font-weight-bold pb-0">
                            Alfa Web
                        </v-card-title>
                    </a>

                    <v-card-text class="pt-2 text-justify">
                        Website realizado con Vue js, Vue Router, Vuex, Vuetify y Herramientas de Firebase como Cloud Firestore y Authentication.
                    </v-card-text>

                </v-card>
            </v-col>

            <v-col cols="12" lg="4" md="6">
                <v-card class="mx-auto" max-width="344">

                    <v-img src="@/assets/GamesOpinion.png"  height="200px"></v-img>

                    <a href="https://javieralavena.github.io/Games-Opinion-Site/" target="_blank" class="text-decoration-none">
                        <v-card-title class="font-weight-bold pb-0">
                            Games Opinion Site
                        </v-card-title>
                    </a>

                    <v-card-text class="pt-2 text-justify">
                        Website realizado con Vue js, Vue Router y Vuex.</v-card-text>

                </v-card>
            </v-col>

            <v-col cols="12" lg="4" md="6">
                <v-card class="mx-auto" max-width="344">

                    <v-img src="@/assets/bojack.png"  height="200px"></v-img>

                    <a href="https://javieralavena.github.io/Bojack/" target="_blank" class="text-decoration-none">
                        <v-card-title class="font-weight-bold pb-0">
                            Bojack Horseman Site
                        </v-card-title>
                    </a>

                    <v-card-text class="pt-2 text-justify">
                        Website realizado con Vue js, Vue Router, Vuex y Vuetify.</v-card-text>

                </v-card>
            </v-col>

        </v-row>

    </v-col>
</template>

<script>
export default {
    name: 'component-proyectos',
    // props: {},
    data: function () {
        return {}
    },
    // computed: {},
    methods: {

    },

}
</script>

<style scoped>

</style>
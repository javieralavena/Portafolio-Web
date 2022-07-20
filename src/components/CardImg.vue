<template>
    <v-card class="card d-flex flex-column flex-sm-row flex-md-column flex-lg-row  mx-sm-15 mt-16">
        <v-img lazy-src="https://picsum.photos/id/11/10/6"
            class="img rounded-xl mt-n16 mt-sm-0 ml-sm-n16 mt-md-n16 mt-lg-0 align-self-center" width="160" height="160"
            src="@/assets/1647356939400.jpg"></v-img>
        <div class="text-center">
            <h1 class="pt-5 px-5">Javiera Troncoso</h1>
            <h3 class="py-5 px-5">DESARROLLADORA WEB FRONT-END TRAINEE / INGENIERA CIVIL INDUSTRIAL</h3>
        </div>
    </v-card>
</template>

<script>
export default {
    name: 'component-img',
    // props: {},
    data: function () {
        return {}
    },
    methods: {
    },
}
</script>

<style scoped>
.card {
    background: radial-gradient(circle at top left, #af9dcc, #ffb5a6);
}

h1 {
    font-size: 2.5rem;
    line-height: normal;
}

h3 {
    font-size: 1.17rem;
    line-height: normal;
}

@media (min-width: 600px) {

    .card {
        margin-left: 120px !important;
    }

    h1 {
        font-size: 3rem;
        line-height: normal;
    }

}

@media (min-width: 760px) {

    .card {
        margin-left: 120px !important;
    }

    h1 {
        font-size: 4rem;
        line-height: normal;
    }
}

@media (min-width: 960px) {

    .card {
        margin-left: 64px !important;
    }
}

@media (min-width: 1264px) {

    .card {
        margin-left: 120px !important;
    }

    h3 {
    font-size: 1.3rem;
    line-height: normal;
}
}
</style>
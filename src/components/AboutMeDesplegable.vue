<template>
    <v-expansion-panels class=" mx-md-16 mx-sm-16 mb-5 desplegable" focusable>
        <v-expansion-panel >
            <v-expansion-panel-header color="#ffb5a6"><h2 class="text-center" >
                    Sobre Mí 🤭
                </h2></v-expansion-panel-header>
            <v-expansion-panel-content class="mt-5">
                <p class="text-justify">
                    Hola, soy desarrolladora web Front-End Trainee e Ingeniera Civil Industrial, con conocimiento
                    principalmente en <span>JavaScript</span>, <span>Sass</span> y <span>Vue js</span>.</p>
                <p class="text-justify">Me considero una persona que tiene facilidad para aprender cosas nuevas y
                    comprometida con sus responsabilidades, lo que me ha hecho desarrollar la autogestión. Además, el
                    haber
                    estudiado una carrera me permitió
                    desarrollar competencias tales como el trabajo en equipo, el pensamiento lógico y la resolución de
                    problemas.</p>
                <p class="text-justify"> Me gusta mucho lo visual, que las cosas sean estéticamente atractivas y
                    funcionales,
                    por lo que quiero
                    dedicarme a desarrollar páginas webs y aplicaciones con estas características, y que le faciliten la
                    vida a las personas.
                </p>
            </v-expansion-panel-content>
        </v-expansion-panel>
    </v-expansion-panels>
</template>

<script>
export default {
    name: 'component-desplegable',
    // props: {},
    data: function () {
        return {}
    },
    methods: {
    },
}
</script>

<style scoped>
.desplegable{
    width:auto;
}

p {
    line-height: 1.5;
}

span {
    color: #8f80a7;
    font-weight: bold;
}
</style>
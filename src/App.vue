<template>
    <main class="columns is-gapless is-multiline">
        <div class="column is-one-quarter">
            <BarraLateral></BarraLateral>
        </div>
        <div class="column is-three-quarter">
            <Formulario></Formulario>
        </div>
    </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import Formulario from './components/Formulario.vue';

export default defineComponent({
    components: {
        BarraLateral,
        Formulario
    },
    name: 'App',
});
</script>

<style>

</style>

<template>
  <main class="columns is-gapless is-multiline">
    <div class="columns is-on-quarter">
    </div>
    <div class="columns is-three-quarter">
      <BarraLateral/>
    </div>
    <div>
      <FormularioHome/>
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BarraLateral from './components/BarraLateral.vue';
import FormularioHome from './components/Formulario.vue';

export default defineComponent({
    name: "App",
    components: {
    BarraLateral, 
    FormularioHome 
  }
})

</script>

<style src="../public/global.css">

</style>

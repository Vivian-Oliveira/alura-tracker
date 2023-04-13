<template>
  <header>
    <h1>
      <img src="https://cdn-icons-png.flaticon.com/512/4245/4245777.png" alt="logo" />
    </h1>
  </header>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name: 'BarraLateral'
    })
</script>

<style scoped>
header {
  padding: 1rem;
  width: 100%;
  height: 20vh;
}
img {
    width: 200px;
}
@media only screen and (max-width: 400px) {
  header {
    padding: 2.5rem;
    height: auto;
  }
}</style>

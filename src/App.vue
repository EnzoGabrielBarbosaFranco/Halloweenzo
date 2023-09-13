<script setup>
import Cabecalho from './components/Cabecalho.vue';
import Home from './components/Home.vue';
import Categorias from './components/Categorias.vue';
import DocesOuTravessuras from './components/DocesOuTravessuras.vue';
import SeInscreva from './components/SeInscreva.vue';
import Rodape from './components/Rodape.vue';
</script>

<template>
  <div class="container overflow-x-hidden">
    <Cabecalho/>
    <Home/>
    <Categorias/>
    <DocesOuTravessuras/>
    <SeInscreva/>
    <Rodape/>
  </div>
</template>

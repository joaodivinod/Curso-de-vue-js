<template>
  <div id="app">
  <h1>Guia Clientes</h1>
    <cliente></cliente>


  </div>
</template>

<script>

import cliente from "@/components/cliente";
// import produto from "@/components/produto";

export default {
  name: 'App',
  components:{
    cliente,
    // produto
  }

}
</script>

<style>
#app {

}
</style>

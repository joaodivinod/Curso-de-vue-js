<template>
  <div id="app">
  <h1>Guia Clientes</h1>
  <cliente></cliente>
  <cliente></cliente>
  <cliente></cliente>

  </div>
</template>

<script>

import cliente from "./components/cliente";

export default {
  name: 'App',
  components:{
    cliente
  }

}
</script>

<style>
#app {

}
</style>

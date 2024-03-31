<!-- App.vue -->

<template>
  <div id="app">
      <MenuPrincipal />
      <MenuLateral />
      <ContenidoCentral />
      <PieDePagina />
      <router-view />
  </div>
</template>

<script>
import MenuPrincipal from './components/Menu.vue';
import MenuLateral from './components/Aside.vue';
//import ContenidoCentral from './components/Integrantes.vue';
import PieDePagina from './components/Footer.vue';
export default {
  name: 'App',
  components: {
      MenuPrincipal,
      MenuLateral,
      PieDePagina
  }
}
</script>

<style>
/* Estilos globales de la aplicación */
</style>
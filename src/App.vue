<template>
  <div class="app">
    <menu-nav/>
    <conteudo-principal/>
  </div>
</template>

<script>
import Nav from './assets/components/shared/nav/Nav.vue';
import ConteudoPrincipal from './assets/components/shared/Principal/Conteudo-Principal.vue';

export default {
  components: {
    'menu-nav': Nav,
    'conteudo-principal': ConteudoPrincipal
  }
}
</script>

<style >
  
  body {
    margin: 0;
  }

  .app {
    overflow: hidden;
    width: 100vw;
    height: 100vh;
    background-image: url('./arcane-background.svg');
    background-size: cover;
  }

</style>

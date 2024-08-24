<template>
  <Navbar />
  <router-view/>
  <Footer />
</template>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';
  import Pedidos from './views/Pedidos.vue';

  export default {
    name: 'App',
    components: {
      Navbar,
      Footer
    }
  }
</script>

<style>

</style>

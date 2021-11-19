<template>
  <div id="app">
    <Header/>
    <!-- <Prenota/> -->
    <Servizi/>
    <Footer/>
  </div>
</template>

<script>
import Servizi from './components/Servizi.vue'
/* import Prenota from './components/Prenota.vue' */
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Servizi,
  /*   Prenota, */
    Header,
    Footer,
  }
}
</script>

<style lang="scss">

@import '@/style/general.scss';
</style>

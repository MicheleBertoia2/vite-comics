
<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Actions from './components/Actions.vue';
import Footer from './components/Footer.vue';

export default {
  components : {
    Header,
    Main,
    Actions,
    Footer
  }
  
}
</script>

<template>

  <Header/>

  <Main/>

  <Actions/>

  <Footer/>
  
</template>

<style lang="scss">
  @use './scss/main.scss'
</style>
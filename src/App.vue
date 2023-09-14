<script>
import Main from './components/Main.vue';
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';
export default {
  name:'App',
  components: {
    Main,
    Header,
    Footer
  }
}
</script>

<template>

  <Header />
  <Main />
  <Footer />

</template>


<style lang="scss">
//versione 1 - inclusione via app.vue
// @use './assets/scss/main.scss' as *;
</style>

<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
    <Footer2 />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Footer2 from './components/Footer2.vue'



export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
    Footer2
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
 
}
</style>

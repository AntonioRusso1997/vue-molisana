<template>
  <div id="app">
    <!-- Header -->
    <Header />
    <Products />
    <Footer />

    <!-- Main -->


    <!-- Footer -->


  </div>
</template>

<script>
import Header from './components/Header.vue'
import Products from './components/Products.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Products,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

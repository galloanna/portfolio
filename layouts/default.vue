<template>
  <div>
    <Header />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from './partials/header';
import Nav from './partials/nav';
import Footer from './partials/footer';
export default {
  components: {
    Header, Nav, Footer
  }
}
</script>

<style>

</style>

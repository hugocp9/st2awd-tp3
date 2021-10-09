<template>
  <div id="app">
    <Header />
    <homepage />
    <Footer />
  </div>
</template>

<script>

import homepage from "./pages/HomePage.vue";
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: 'App',
  components: {
      homepage,
      Header,
      Footer

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #2c3e50;
  margin-top: 20px;

}
</style>

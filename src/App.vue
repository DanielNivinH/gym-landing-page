<template>
  <Header />
  <Homepage />
  <Footer />
</template>
<script>
import Homepage from "./pages/HomePage.vue";
import Header from "./components/layout/Header.vue";
import Footer from "./components/layout/Footer.vue";
export default {
  name: "App",
  components: {
    Homepage,
    Header,
    Footer,
  },
};
</script>
<style lang="stylus">
#app
  display flex
  flex-direction column
  height 100%
  background-color #000000
</style>

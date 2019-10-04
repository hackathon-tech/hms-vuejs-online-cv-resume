<template>
  <div id="app">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
// require('@/assets/css/bootstrap-3.3.7.min.scss');
// require('@/assets/css/stylesheets/_bootstrap.scss');
// require('@/assets/css/font-awesome-4.7.min.scss');
// require('@/assets/css/magnific-popup.css');
// require('assets/css/animate.scss');
// <!-- // Custom Style -->

require('@/assets/css/style.scss');

import Header from "@/shared/Header.vue";
import Footer from "@/shared/Footer.vue";

@Component({
  components: {
    Header,
    Footer
  }
})
export default class Home extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>

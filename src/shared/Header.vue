<template>
  <!-- // Header Start here // -->
  <header>
    <!-- // Menu Bars Start -->
    <div class="menu-bars">
      <span></span>
      <span></span>
      <span></span>
      <span></span>
    </div>
    <!-- // Menu Bars Ends -->

    <!-- // Nav Start here // -->
    <Nav />
    <!-- // Nav Ends here // -->

    <!-- // Start Hero Area here // -->
    <Hero fName="Maleeha" lName="Saleem" title="Web Designer &amp; Developer" />
    <!-- // Ends Hero Area here // -->
  </header>
  <!-- // Header Ends here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
import Hero from "@/shared/Hero.vue";
import Nav from "@/shared/Nav.vue";

@Component({
  name: "Info",
  components: {
    Hero,
    Nav
  },
  data() {
    return {
    };
  }
})
export default class Header extends Vue {
}
</script>


<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
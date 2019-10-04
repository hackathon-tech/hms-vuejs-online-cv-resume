<template>
  <nav class="navigation">
    <div class="navigation-inner">
      <ul class="main-menu nav navbar-nav">
        <li class="active smooth-scroll">
          <!-- // <a href="#home">Home</a> -->
          <router-link to="/bout">Home</router-link>
        </li>
        <li class="smooth-scroll">
          <a href="#about">About</a>
        </li>
        <li class="smooth-scroll">
          <a href="#experiences">Experience</a>
        </li>
        <li class="smooth-scroll">
          <a href="#services">Service</a>
        </li>
        <li class="smooth-scroll">
          <a href="#portfolio">Portfolio</a>
        </li>
        <li class="smooth-scroll">
          <a href="#testimonial">Testimonial</a>
        </li>
        <li class="smooth-scroll">
          <a href="#blog">blog</a>
        </li>
        <li class="smooth-scroll">
          <a href="#contact">contact</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  name: "Nav",
  components: {},
  data() {
    return {};
  }
})
export default class Header extends Vue {
}
</script>


<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
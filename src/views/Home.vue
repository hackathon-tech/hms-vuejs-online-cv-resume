<template>
  <div class="home">
    <AboutMe />
    
    <Figures />

    <Services />
    <Experience />
    <Portfolio />
    <Testimonials />
    <Blog />
    <Partner />
    <GetInTouch />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import AboutMe from "@/components/AboutMe.vue"; // @ is an alias to /src
import Figures from "@/components/Figures.vue";
import Blog from "@/components/Blog.vue";
import Services from "@/components/Services.vue";

import Experience from "@/components/Experience.vue";
import Portfolio from "@/components/Portfolio.vue";
import Partner from "@/components/Partner.vue";
import GetInTouch from "@/components/GetInTouch.vue";
import Testimonials from "@/components/Testimonials.vue";


@Component({
  components: {
    AboutMe,
    Figures,
    Services,
    Experience,
    Testimonials,
    Portfolio,
    Blog,
    Partner,
    GetInTouch
  }
})
export default class Home extends Vue {}
</script>

<template>
  <!-- // Start Experience here // -->
  <section class="section-padding" id="experiences">
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-md-offset-2">
          <div class="section-header">
            <h2 class="section-title">
              My
              <span>Experience</span>
            </h2>
            <p>
              Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical
              Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor.
            </p>
          </div>
        </div>
      </div>
      <!-- // Experiences Slides Start here // -->
      <carousel
        class="experiences-sllides"
        :autoplay="true"
        :items="3"
        :margin="20"
        autoplayHoverPause="true"
        :dots="true"
        :responsive="{0:{items:1,nav:false},550:{items:2,nav:false},850:{items:3,nav:false}}"
      >
        <div class="experiences-single-box">
          <h3>Oct 2016 - Present</h3>
          <h5>
            Anchor
            <span>Co-founder, Front-end Designer</span>
          </h5>
          <p>
            Lorem ipsum, dolor sit amet consectetu Lorem ipsum, dolor
            sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="experiences-single-box">
          <h3>Jul 2014 - Oct 2015</h3>
          <h5>
            European Winter
            <span>CEO &amp; Creative Director</span>
          </h5>
          <p>
            Lorem ipsum, dolor sit amet consectetu Lorem ipsum, dolor
            sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="experiences-single-box">
          <h3>Oct 2016 - Present</h3>
          <h5>
            Creative Dot
            <span>Senior Visual Designer</span>
          </h5>
          <p>
            Lorem ipsum, dolor sit amet consectetu Lorem ipsum, dolor
            sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="experiences-single-box">
          <h3>Oct 2016 - Present</h3>
          <h5>
            Anchor
            <span>Co-founder, Front-end Designer</span>
          </h5>
          <p>
            Lorem ipsum, dolor sit amet consectetu Lorem ipsum, dolor
            sit amet consectetur adipisicing elit.
          </p>
        </div>
        <div class="experiences-single-box">
          <h3>Oct 2016 - Present</h3>
          <h5>
            Creative Dot
            <span>Senior Visual Designer</span>
          </h5>
          <p>
            Lorem ipsum, dolor sit amet consectetu Lorem ipsum, dolor
            sit amet consectetur adipisicing elit.
          </p>
        </div>
      </carousel>
      <!-- // Experiences Slides Ends here // -->
    </div>
  </section>
  <!-- // Ends Experience here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
import carousel from "vue-owl-carousel";
// const carousel = require('vue-owl-carousel');

@Component
@Component({
  components: {
    carousel
  }
})
export default class Experience extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>

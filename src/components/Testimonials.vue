<template>
  <!-- // Start Testimonial here // -->
  <section class="section-padding" id="testimonial">
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-md-offset-2">
          <div class="section-header">
            <h2 class="section-title">
              What
              <span>client say?</span>
            </h2>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
              aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
              sit amet consectetur adipisicing elit.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <carousel
            class="testimonial-slides"
            :autoplay="true"
            :items="1"
            :margin="20"
            :nav="false"
            autoplayHoverPause="true"
            :dots="false"
          >
            <div class="testimonial-single-item text-center">
              <img src="assets/img/testimonial/1.jpg" alt="testimonial" class="client-img" />
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                sit amet consectetur adipisicing elit.
              </p>
              <h5>
                Ayoub khan
                <span>Developer</span>
              </h5>
            </div>
            <div class="testimonial-single-item text-center">
              <img src="assets/img/testimonial/2.jpg" alt="testimonial" class="client-img" />
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                sit amet consectetur adipisicing elit.
              </p>
              <h5>
                Nazir
                <span>Developer</span>
              </h5>
            </div>
            <div class="testimonial-single-item text-center">
              <img src="assets/img/testimonial/3.jpg" alt="testimonial" class="client-img" />
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                sit amet consectetur adipisicing elit.
              </p>
              <h5>
                Shahms
                <span>Developer</span>
              </h5>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- // Ends Testimonial here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";
const carousel = require("vue-owl-carousel");

@Component({
  name: "Nav",
  components: {
    carousel
  },
  data() {
    return {};
  }
})
export default class Testimonials extends Vue {
  @Prop() private fName!: string;
  @Prop() private lName!: string;
  @Prop() private title!: string;
}
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
</style>

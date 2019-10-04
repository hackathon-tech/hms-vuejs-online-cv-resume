<template>
  <!-- // Start Media Partnar here // -->
  <div class="section-padding" id="branding">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <!-- // Start brand-slides here -->
          <carousel
            class="brand-slides"
            :autoplay="true"
            :responsive="{0:{items:1,nav:true, },400:{items:2,nav:true, },600:{items:4,nav:false, },800:{items:5,nav:false, }}"
            :margin="20"
            :nav="false"
            :dots="false"
          >
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand1.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand2.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand3.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand4.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand5.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
            <div class="brand-single-item">
              <p>
                <img src="assets/img/brand/brand6.png" alt="Brand Logo" />
                <span>My Partner</span>
              </p>
            </div>
          </carousel>
          <!-- // Brand-slides ends here -->
        </div>
      </div>
    </div>
  </div>
  <!-- // Ends Media Partnar here // -->
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
const carousel = require('vue-owl-carousel');

@Component({
  components: {
    carousel
  }
})
export default class Partner extends Vue {}
// export default {
//   name: "Partner",
//   data() {
//     return {};
//   },
//   computed: {},
//   mounted() {},
//   methods: {}
// };
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
</style>
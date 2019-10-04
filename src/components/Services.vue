<template>
  <!-- // Start Work here // -->
  <section
    class="section-padding"
    id="services"
    style="background-image: url(assets/img/work-bg.jpg);"
  >
    <div class="container">
      <div class="row">
        <div class="col-md-7">
          <div class="section-header">
            <h2 class="section-title">
              what
              <span>i do?</span>
            </h2>
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores, quae nobis odio saepe cumque fugit amet ipsa, consectetur quas commodi rem quos error dignissimos modi nam facilis recusandae, reiciendis libero?
            </p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-5 col-md-offset-1">
          <div class="work-box">
            <div class="work-box-single-item">
              <div class="work-icon">
                <i class="fa fa-laptop"></i>
              </div>
              <h5>Web Design</h5>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                  aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                  sit amet consectetur adipisicing elit.
              </p>
            </div>
            <div class="work-box-single-item">
              <div class="work-icon">
                <i class="fa fa-laptop"></i>
              </div>
              <h5>Dashboard Design</h5>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                  aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                  sit amet consectetur adipisicing elit.
              </p>
            </div>
            <div class="work-box-single-item">
              <div class="work-icon">
                <i class="fa fa-laptop"></i>
              </div>
              <h5>Web Design</h5>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis, minima molestias! Hic illum
                  aliquam, dolorem repellat quod, aut magni perferendis placeat quo a vel nisi. Lorem ipsum, dolor
                  sit amet consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- // Ends Work here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Services extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>

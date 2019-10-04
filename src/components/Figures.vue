<template>
  <!-- // Start Counter here // -->
  <div class="section-padding" id="counter">
    <div class="container">
      <div class="row">
        <div class="col-sm-3 col-xs-6">
          <!-- // Counter Single Box -->
          <div class="counter-box">
            <div class="counter-icons">
              <i class="fa fa-users"></i>
              <p>Happy Client</p>
            </div>
            <span class="counter-item">460</span>
          </div>
          <!-- // Counter Single Box -->
        </div>
        <div class="col-sm-3 col-xs-6">
          <!-- // Counter Single Box -->
          <div class="counter-box">
            <div class="counter-icons">
              <i class="fa fa-handshake-o"></i>
              <p>Project Completed</p>
            </div>
            <span class="counter-item">55</span>
          </div>
          <!-- // Counter Single Box -->
        </div>
        <div class="col-sm-3 col-xs-6">
          <!-- // Counter Single Box -->
          <div class="counter-box">
            <div class="counter-icons">
              <i class="fa fa-life-ring"></i>
              <p>Support</p>
            </div>
            <span class="counter-item">555</span>
          </div>
          <!-- // Counter Single Box -->
        </div>
        <div class="col-sm-3 col-xs-6">
          <!-- // Counter Single Box -->
          <div class="counter-box">
            <div class="counter-icons">
              <i class="fa fa-trophy"></i>
              <p>Award</p>
            </div>
            <span class="counter-item">4</span>
          </div>
          <!-- // Counter Single Box -->
        </div>
      </div>
    </div>
  </div>
  <!-- // Ends Counter here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Figures extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>

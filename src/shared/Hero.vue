<template>
  <!-- // Start Hero Area here // -->
  <div class="hero-area" style="background-image: url(assets/img/profile-img.png);">
    <div class="hms-table">
      <div class="hms-table-cell">
        <div class="container">
          <!-- // Hero Content Start -->
          <div class="hero-content">
            <h5>Hello</h5>
            <h1>
              <span>I’m</span>
              <br />
              {{fName}}
              <br />
              {{lName}}
              <br />
            </h1>
            <p>{{title}}</p>
            <a href="index-2.html" class="hms-btn">View Profile</a>
            <a href="index-2.html" class="hms-btn">Download</a>
          </div>
          <!-- // Hero Content Ends -->

          <!-- // Social Area Start here // -->
          <div class="social-area">
            <a href="https://web.facebook.com/AyoubKhan558">
              <i class="fa fa-facebook"></i>
            </a>
            <a href="https://twitter.com/AyoubKhan558">
              <i class="fa fa-twitter"></i>
            </a>
            <a href="https://github.com/ayoubkhan558">
              <i class="fa fa-github"></i>
            </a>
            <a href="https://linkedin.com/in/ayoubkhan558/">
              <i class="fa fa-linkedin"></i>
            </a>
            <a href="https://stackoverflow.com/users/9207553/mohammad-ayoub-khan">
              <i class="fa fa-stack-overflow"></i>
            </a>
          </div>
          <!-- // Social Area Ends here // -->
        </div>
      </div>
    </div>
  </div>
  <!-- // Ends Hero Area here // -->
</template>


<script lang="ts">
// export default {
import { Component, Vue, Prop } from "vue-property-decorator";

@Component({
  name: "Hero",
  data() {
    return {
    };
  },
  computed: {},
  mounted() {},
  methods: {}
})
// };
export default class AboutMe extends Vue {
  @Prop() private fName!: string;
  @Prop() private lName!: string;
  @Prop() private title!: string;
}
</script>

// <!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped></style>
<template>
  <!-- // Start Footer here // -->
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-md-12 text-center">
          <div class="footer-social">
            <ul>
              <li>
                <a href="https://twitter.com/ayoubkhan558">
                  <i class="fa fa-lg fa-twitter"></i>
                </a>
              </li>
              <li>
                <a href="https://www.facebook.com/ayoubkhan558/">
                  <i class="fa fa-lg fa-facebook"></i>
                </a>
              </li>
              <li>
                <a href="https://dribbble.com/ayoubkhan558">
                  <i class="fa fa-lg fa-dribbble"></i>
                </a>
              </li>
              <li>
                <a href="https://www.instagram.com/ayoubkhan558/">
                  <i class="fa fa-lg fa-instagram"></i>
                </a>
              </li>
            </ul>
          </div>

          <div class="copyright">
            &copy; Copyright
            <a href target="_blank">HMS</a> 2020 All Right Reserved. Design by
            <a
              href="https://imayoub.netlify.com"
              target="_blank"
            >M Ayoub Khan</a>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- // Ends Footer here // -->
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Footer extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer-social {
  ul {
    list-style: none;
    padding-left: 0;
    li {
      display: inline-block;
      a {
        padding: 5px;
        display: inline-block;
      }
    }
  }
}
</style>

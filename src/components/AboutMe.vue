<template>
  <!-- // Start About here // -->
  <section class="section-padding" id="about">
    <div class="container">
      <div class="row">
        <div class="col-sm-8 col-sm-offset-2">
          <div class="section-header">
            <h2 class="section-title">
              About
              <span>me</span>
            </h2>
            <p>
              Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical
              Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor.
            </p>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4 col-sm-4">
          <Info />
        </div>
        <div class="col-md-4 col-sm-4">
          <Skills1 />
        </div>
        <div class="col-md-4 col-sm-4">
          <Skills2 />
        </div>
      </div>
    </div>
  </section>
  <!-- // Ends About here // -->
</template>

<script lang="ts">
// export default {
import { Component, Vue } from "vue-property-decorator";
import Info from "@/components/Info.vue";
import Skills1 from "@/components/Skills1.vue";
import Skills2 from "@/components/Skills2.vue";

@Component({
  name: "AboutMe",
  components: {
    Info,
    Skills1,
    Skills2
  },
  data() {
    return {
      abc: "Maliha"
    };
  },
  computed: {},
  mounted() {},
  methods: {}
})
// };
export default class AboutMe extends Vue {}
</script>

// <!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped></style>
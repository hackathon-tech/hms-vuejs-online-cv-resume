<template>
  <div class="about-single-item">
    <div class="skill-area">
      <h3 class="section-title">Software &amp; Tools</h3>
      <div class="progress-wraper">
        <div v-for="skill in skills" v-bind:key="skill.id" class="single-progress-bar">
          <h5 class="progress-title">{{ skill.name }}</h5>
          <div class="progress">
            <div
              class="progress-bar wow"
              data-wow-duration="1.5s"
              role="progressbar"
              aria-valuemin="0"
              aria-valuemax="100"
              v-bind:style="{ width: skill.percentage + '%' }"
              v-bind:[aria-valuenow]="skill.percentage"
            >
              <span>{{skill.percentage}}%</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "Skills2",
  data() {
    return {
      skills: [
        { id: 1, name: "Adobe Dream Viewer", percentage: "80" },
        { id: 2, name: "Sass", percentage: "75" },
        { id: 3, name: "Xampp", percentage: "80" },
        { id: 4, name: "VS Code", percentage: "80" },
        { id: 5, name: "Adobe Photoshop", percentage: "95" }
      ]
    };
  },
  computed: {},
  mounted() {},
  methods: {}
};
</script>

<!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
</style>
<template>
  <div class="about-single-item">

    <div class="skill-area">
      <h3 class="section-title">Language Skills</h3>
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
              v-bind:[aria-valuenow]="skill.percentage"
              v-bind:style="{ width: skill.percentage + '%' }"
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
  name: "Skills1",
  data() {
    return {
      skills: [
        { id: 1, name: "HTML5", percentage: "90" },
        { id: 2, name: "CSS3", percentage: "95" },
        { id: 3, name: "Javascript", percentage: "80" },
        { id: 4, name: "JQuery", percentage: "88" },
        { id: 5, name: "ReactJS", percentage: "85" }
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
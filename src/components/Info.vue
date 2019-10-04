<template>
  <div class="about-single-item">
    <h3 class="section-title">Personal information</h3>
    <ul class="personal-info">
      <li>
        <span>Name</span> Maleeha Saleem
      </li>
      <li>
        <span>Birthday</span>18th October 1996
      </li>
      <li>
        <span>Address</span>Farid Town, Sahiwal, 27000
      </li>
      <li>
        <span>Email</span>
        <a href="mailto:ayoubkhan558@hotmail.com">malihasaleem58@gmail.com</a>
      </li>
      <li>
        <span>Telephone</span>+ 92 334 00 00 000
      </li>
      <li>
        <span>Mobile</span>+ 92 346 98 34 211
      </li>
      <li>
        <span>Marital status</span>Single
      </li>
    </ul>
    <img class="signature" src="assets/img/signature.png" alt="author signature" />
  </div>
</template>


<script lang="ts">
export default {
  name: "Info",
  data() {
    return {};
  },
  computed: {},
  mounted() {},
  methods: {}
};
</script>

// <!-- // Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
ul.personal-info {
  text-align: left;
}
</style>
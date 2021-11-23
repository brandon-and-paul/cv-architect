<template>
  <div class="resume-card">
    <PersonalDetails />
    <Block />
  </div>
</template>

<script>
import Block from "./Block";
import PersonalDetails from "./PersonalDetails";

export default {
  components: {
    Block,
    PersonalDetails,
  },
  mounted() {
    console.log(30);
  }
};
</script>

<style>
  .resume-card {
    width: 46em;
    height: 850px;
    box-shadow: 0px 4px 8px 2px rgba(0, 0, 0, 0.3);
  }
</style>

<template>
  <Block />
  <PersonalDetails />
  <div>CV Architect</div>
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
</style>

<template>
  <div>Hello World</div>
</template>

<script>
import Resume from "./components/Resume";
import Form from "./components/Form";

export default {
  component: { Resume, Form },
  props: [],
  data() {},
  mounted() {},
  methods: {},
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;500;700&display=swap');

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Fira Code', monospace;
}

body {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

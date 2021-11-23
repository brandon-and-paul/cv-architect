<template>
<div class="skill-set">
  <h4>skills</h4>
  <div v-for="skills in skills" class="skills">
    <p>{{skills}}</p>
  </div>
  </div>
  <Entry />
</template>

<script>
import Entry from "./Entry";

export default {
components: { Entry },
data() { 
return {
  skills: ['html','javascript','css','react.js','vue.js','PHP','lavarel']
}
},
}

</script>

<style>
 .skill-set{
   width: 40%;
   height: max-content;
   display: flex;
   flex-direction: row;
   padding: 2em;


 }
</style>

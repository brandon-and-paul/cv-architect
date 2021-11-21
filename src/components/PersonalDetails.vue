<template>
<div class="personal-details-card">  
  <div class="personal-photo">
    {{Photo}}
  </div>
  <div class="personal-details">
    <div class="Name"><p>&#128100 {{Name}}</p></div>
    <div class="Address"><p>&#127969 {{Address}}</p></div>
    <div class="Telephone"><p>&#128222 {{Telephone}}</p></div>
    <div class="Email"><p>&#128231 {{Email}}</p></div>
    <div class="Country"><p>&#127758 {{Country}}</p></div>
  </div>
  <Entry />
</div>
</template>

<script>
import Entry from "./Entry";

export default { 
  component: { Entry },
  props: ['Name', 'Address', 'Telephone','Email','Photo','Country'],
  data(){
    return {
    Name: "Mason Houghman",
    Address: "CA 5055",
    Telephone: "+233 20 030 2212",
    Email: "mason.houghman@gmail.com",
    Photo:"photo",
    Country:"USA",
    }
  },
    
  mounted() {},
  methods: {},
};
</script>

<style>
.personal-details-card{
  display: flex;
  flex-direction: row;
  width: 46em;
  height: max-content;
  background-color: #f79256ff;
}
.personal-photo{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 20%;
  height: max-height;
  background-color: rgb(193, 195, 201);
}
.personal-details{
  padding: 20px;
  margin-left: 30px;
}
</style>

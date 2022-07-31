<template>
  <div id="app">
    <CardProfile/>
    
  </div>

</template>

<script>

import CardProfile from "./components/CardProfile.vue"
export default {
  name: "App",
  components: {
    CardProfile
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300:400:700&display=swap");
#app {
  font-family: "Roboto" , sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
  margin-top: 60px;
  background-color:#121212 ;
}
body{
  background-color:#121212 ;
}
</style>

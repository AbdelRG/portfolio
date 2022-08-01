<template>
  <div class="navbarContainer">
    <p class ="sectionTitle" v-on:click="getActive('AboutMe')">About</p>
    <p class ="sectionTitle" v-on:click="getActive('Resume')">Resume</p>
    <p class ="sectionTitle" v-on:click="getActive('Portfolio')">Portfolio</p>
  </div>
</template>

<script>
export default {
   data(){
    return{
      activeShow:'AboutMe'
    }
  },
  props:{
    getActive:Function
  }
}
</script>

<style lang="scss">
.navbarContainer{
  display: flex;
  justify-content: space-around;
  background-color:#2a2a2b ;
  border-radius: 0px 15px 0px 15px ;
  width: 400px;
  height: 60px;
   border-bottom: solid #383838 0.1em;
   border-left:solid #383838 0.1em ;
  .sectionTitle{
    color: white;
    cursor: pointer;
    &:hover{
      opacity: 0.7;
    }
  }
}

</style>
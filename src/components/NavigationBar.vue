<template>
  <div class="navbarContainer">
    <p class ="sectionTitle">About</p>
    <p class ="sectionTitle">Resume</p>
    <p class ="sectionTitle">Portfolio</p>
  </div>
</template>

<script>
export default {

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
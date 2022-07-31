<template>
  <div class="contentSectionContainer">
    <div class="contentSectionHeader">
    <h2 class="contentSectionHeaderTitle">About Me</h2>   
     <NavigationBar/>
     </div>
  </div>
</template>

<script>
import NavigationBar from "./NavigationBar.vue"
export default {
    components: {
    NavigationBar
  },
}
</script>

<style lang="scss">
.contentSectionContainer{
    width: 800px;
    height: 1000px;
    background-color: #1e1e1f;
    border: solid #383838 0.1em;
    border-radius:15px ;
    margin-left: 150px ;
    .contentSectionHeader{
        display: flex;
        justify-content: space-between;
        .contentSectionHeaderTitle{
            color: white;
            margin-left:30px;
            padding-bottom: 10px;
            border-bottom: solid #ffcc66 3px;
            border-bottom-left-radius: 0px;
        }
    }
    
}
</style>
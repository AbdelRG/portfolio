<template>
  <div class="portfolioListContainer">
    <a class="projectLink" href="https://github.com/AbdelRG/AbdelrahimGourari_2_13082021">
    <div class="projectContainer">
     
        <img class="projectPic" src="../assets/html5-css3.png">
        
        <p class="projectTitle">Projet integration html/css </p>
     
    </div>
    </a>
    <a class="projectLink" href="https://github.com/AbdelRG/AbdelrahimGourari_3_29102021">
    <div class="projectContainer">
     
        <img class="projectPic" src="../assets/html5-css3.png">
        
        <p class="projectTitle">Projet integration html/scss et animation </p>
     
    </div>
    </a>
    <a class="projectLink" href="https://github.com/AbdelRG/Projet-5">
    <div class="projectContainer">
     
        <img class="projectPic" src="../assets/javascript.png">
        
        <p class="projectTitle">Site E-commerce en javascript (Front) </p>
     
    </div>
    </a>
     <a class="projectLink" href="https://github.com/AbdelRG/Projet-6">
    <div class="projectContainer">
     
        <img class="projectPic" src="../assets/node-js-new.png">
        
        <p class="projectTitle"> API sécurisée pour une application d'avis gastronomiques (Back) </p>
     
    </div>
    </a>
    <a class="projectLink" href="https://github.com/AbdelRG/P7">
    <div class="projectContainer">
     
        <img class="projectPic" src="../assets/1631110818-logo-react-js.png">
        
        <p class="projectTitle"> Projet FullStack réseau social d'entreprise (Front:react) (Back:nodejs) </p>
     
    </div>
    </a>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">

.portfolioListContainer{
    display: flex;
    margin-top: 70px;
    flex-wrap: wrap;
    margin-left: 50px ;
    .projectLink{
        text-decoration: none;
        .projectContainer{
            display: flex;
            flex-direction: column;
            height: 180px;
            width: 300px;
            background-color:#2a2a2b ;
            margin-left:30px;
            border-radius:15px ;
            align-items: center;
            margin-top: 20px ;
            border: solid #383838 0.1em;
            .projectPic{
                height: 100px;
                width: 150px;
                object-fit: contain;
            }
            .projectTitle{
                color:#a57f46;
            }

            
        }
    }
}

</style>
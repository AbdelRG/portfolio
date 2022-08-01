<template>
  <div class="aboutMeContainer">
    <div class="aboutMeTextContainer">
    <p class="aboutMeText">
I'm Creative Director and UI/UX Designer from Sydney, Australia, working in web development and print media. I enjoy turning complex problems into simple, beautiful and intuitive designs.<br>

    </p>
    <p class="aboutMeText">My job is to build your website so that it is functional and user-friendly but at the same time attractive. Moreover, I add personal touch to your product and make sure that is eye-catching and easy to use. My aim is to bring across your message and identity in the most creative way. I created web design for many famous brand companies.
    </p>
    </div>
    <h2 class="activitiesTitle">Ce que je fait</h2>
    <div class="activitiesContainer">
        <div class="activityContainer">
         <font-awesome-icon class="activityIcon" icon="fa-solid fa-window-maximize" />
         <div class ="activityInfo">
            <p class="activityTitle">Front-End</p>
            <p class="activityDescription">Développement Front End</p>
         </div>
        </div>
        <div class="activityContainer">
         <font-awesome-icon class="activityIcon" icon="fa-solid fa-server" />
         <div class ="activityInfo">
            <p class="activityTitle">Back-End</p>
            <p class="activityDescription">Développement Back End</p>
         </div>
        </div>
    </div>
    <h2 class="activitiesTitle">Technologies</h2>
    <div class ="technologiesContainer">
        <div class="technologyContainer">
             <img class="technoLogo" src="../assets/html5-css3.png">
        </div>
         <div class="technologyContainer">
             <img class="technoLogo" src="../assets/javascript.png">
        </div>
         <div class="technologyContainer">
             <img class="technoLogo" src="../assets/node-js-new.png">
        </div>
         <div class="technologyContainer">
             <img class="technoLogo" src="../assets/1631110818-logo-react-js.png">
        </div>
    </div>
  </div>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faWindowMaximize,faServer} from "@fortawesome/free-solid-svg-icons";
library.add(faWindowMaximize,faServer);

export default {

}
</script>

<style lang="scss">
.aboutMeContainer{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    .aboutMeTextContainer{
    .aboutMeText{
        color: #ffd068;
         margin-left:30px;
          margin-right:30px;
    }
    }
    .activitiesTitle{
        color: white;
        margin-left: 30px;
    }
    .activitiesContainer{
        display: flex;
        
        .activityContainer{
            height: 140px;
            width: 350px;
            background: linear-gradient(#433d2d ,#202021);
            border-top: solid  #ceb25c 0.5px  ;
            margin-left:30px;
            border-radius:15px ;
            display: flex;
            justify-content: center;
            align-items: center;
            .activityIcon{
                color:#a57f46;
                font-size:50px;
                margin-right:10px;
            }
            .activityInfo{
                display: flex;
                flex-direction: column;
                align-items: flex-start;
                .activityTitle{
                    color: white;
                    margin-bottom: 10px;
                }
                .activityDescription{
                    color: grey;
                    margin-top:0px;
                }
            }
        }
    }
    .technologiesContainer{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
        .technologyContainer{
             height: 140px;
            width: 250px;
            background: linear-gradient(#433d2d ,#202021);
            border-top: solid  #ceb25c 0.5px  ;
            margin-left:30px;
            border-radius:15px ;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 20px;
            transition: all 500ms ease-out;
            opacity: 1;
            &:hover {
              opacity: 0.7;
              
               }
            .technoLogo{
                height: 100px;
                width: 150px;
                object-fit: contain;
                
            }
        }
    }
}



</style>
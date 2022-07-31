<template>
  <div class="cardProfilContainer">
    <div class="profileInfoContainer">
        <img class="profileInfoPic" src="../assets/photo-1624996752380-8ec242e0f85d.avif">
        <p class="profileInfoName" >Gourari Abdelrahim</p>
        <p class="profileInfoJob">Développeur full stack</p>
    </div>
    <div class="contactInfoContainer">
        <div class="contactInfo">
            <div class="iconContainer">
            <font-awesome-icon class="contactIcon" icon="fa-solid fa-envelope" />
            </div>
            <div class="contactContent">
            <p class ="contentTitle">Email</p>
            <p class="contactContent">gourariabdelrahim@gmail.com</p>
            </div>
            </div>
            <div class="contactInfo">
            <div class="iconContainer">
            <font-awesome-icon class="contactIcon" icon="fa-solid fa-mobile-screen" />
            </div>
            <div class="contactContent">
            <p class ="contentTitle">Phone</p>
            <p class="contactContent">0652666765</p>
            </div>
            </div>
            <div class="contactInfo">
            <div class="iconContainer">
            <font-awesome-icon  class="contactIcon" icon="fa-solid fa-calendar-days" />
            </div>
            <div class="contactContent">
            <p class ="contentTitle">Date de naissance</p>
            <p class="contactContent">12/12/1996</p>
            </div>
            </div>
            <div class="contactInfo">
            <div class="iconContainer">
            <font-awesome-icon class="contactIcon" icon="fa-solid fa-location-dot" />
            </div>
            <div class="contactContent">
            <p class ="contentTitle">Localisation</p>
            <p class="contactContent">Colombes (92700)</p>
            </div>
            </div>
     
    </div>
    <div class="socialnetworkInfoContainer">
        <font-awesome-icon class="socialIcon" icon="fa-brands fa-twitter" />
        <font-awesome-icon class="socialIcon" icon="fa-brands fa-facebook-f" />
        <font-awesome-icon class="socialIcon" icon="fa-brands fa-instagram" />
    </div>
  </div>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faEnvelope,faMobileScreen ,faCalendarDays,faLocationDot} from "@fortawesome/free-solid-svg-icons";
import { faTwitter ,faFacebookF,faInstagram } from '@fortawesome/free-brands-svg-icons'
library.add(faEnvelope,faMobileScreen,faCalendarDays,faLocationDot,faTwitter,faFacebookF,faInstagram);
export default {

}
</script>


<style lang="scss">
.cardProfilContainer{
    display: flex;
    width: 300px;
    flex-direction: column;
    background-color: #1e1e1f;
    border: solid #383838 0.1em;
    height: 730px;
    margin-left: 50px ;
    border-radius:15px ;
    .profileInfoContainer{
        margin-top: 50px ;
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-left: 30px;
        margin-right: 30px ;
        border-bottom: solid #383838 0.4px;
        padding-bottom: 20px;
        
    .profileInfoPic{
        width: 150px;
        height: 150px;
        border-radius:15px ;
        object-fit: cover;
    }
    .profileInfoName{
        color: white;
        font-weight: bolder;
       font-size:  22px;
    }
    .profileInfoJob{
        color: white;
        font-size: 12px;
        background-color: #2a2a2b;
        width: 50%;
        height: 30px;
        padding: 5px ;
        text-align:center; 
        vertical-align: middle;
        border-radius:10px ;
        display: flex;
        align-items: center;
        margin-top:0px ;

        
    }
    }
    .contactInfoContainer{
           display: flex;
           flex-direction: column;
           align-items: flex-start;
           margin-top: 15px ;
           margin-right:30px ;
           margin-left:25px ;
         
        .contactInfo{
          display: flex;
          align-items: center;
          margin-top: 10px;
          .iconContainer{
            width: 45px;
            height: 45px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(#433d2d ,#202021);
            border-top: solid  #ceb25c 0.5px  ;
            margin-right: 15px;
            
            border-radius:10px ;
          .contactIcon{
            
            color:#a57f46;
          }
          }
          .contactContent{
            display: flex;
            flex-direction: column;
            align-items: baseline;
            .contentTitle{
                color:grey;
                font-size: 14px;
                margin-bottom:5px ;
            }
            .contactContent{
                margin-top:0px;
                color: white;
                font-size: 12px;
            }
          }
        }
    }
    .socialnetworkInfoContainer{
         display: flex;
         margin-top: 30px ;
         justify-content: center;
        .socialIcon{
            color: gray;
            margin-right: 15px;

        }

    }

}

</style>
<template>
  <div class="resumeContainer">
      <div class="educationContainer">
        <div class="educationHead">
          <div class="iconContainer">
            <font-awesome-icon class="resumeIcon" icon="fa-solid fa-book-open" />
          </div>
          <p class="educationTitle">Diplomes et Formation</p>
        </div>
         <ul class="educationList">
          <li class="educationListElement">
            <span class="liSpan"><font-awesome-icon class="listIcon" icon="fa-solid fa-circle-dot" /></span>
            <div class="contentContainer">
              <p class="contentTitle">Développeur Web</p>
              <p class="date">2021-2022</p>
              <p class="contentDescription">Openclassrooms Colombes</p>
              
            </div>
            </li>
             <li class="educationListElement">
            <span class="liSpan"><font-awesome-icon class="listIcon" icon="fa-solid fa-circle-dot" /></span>
            <div class="contentContainer">
              <p class="contentTitle">Licence mathématiques informatique</p>
              <p class="date">2017-2019</p>
              <p class="contentDescription"> Université Joseph Fourier Valence</p>
            </div>
            </li>
            <li class="educationListElement">
            <span class="liSpan"><font-awesome-icon class="listIcon" icon="fa-solid fa-circle-dot" /></span>
            <div class="contentContainer">
              <p class="contentTitle">Baccalauréat Scientifique</p>
              <p class="date">2016-2017</p>
              <p class="contentDescription"> Lycée guy de maupassant Colombes</p>
            </div>
            </li>
         </ul>
      </div>

      <div class="educationContainer">
        <div class="educationHead">
          <div class="iconContainer">
            <font-awesome-icon class="resumeIcon" icon="fa-solid fa-suitcase" />
          </div>
          <p class="educationTitle">Expériences professionnelles</p>
        </div>
         <ul class="educationList">
          <li class="educationListElement">
            <span class="liSpan"><font-awesome-icon class="listIcon" icon="fa-solid fa-circle-dot" /></span>
            <div class="contentContainer">
              <p class="contentTitle">Développeur Web</p>
              <p class="date">2021-2022</p>
              <p class="contentDescription">Hackstars</p>
              
            </div>
            </li>
             
         </ul>
      </div>
  </div>
</template>

<script>
import { library } from "@fortawesome/fontawesome-svg-core";
import { faBookOpen ,faCircleDot ,faSuitcase} from "@fortawesome/free-solid-svg-icons";

library.add(faBookOpen,faCircleDot,faSuitcase);
export default {

}
</script>

<style lang="scss">

.resumeContainer{
  display: flex;
  flex-direction: column;
  margin-top:50px;
  margin-left:30px;
  .educationContainer{
    margin-top: 20px ;
    display: flex;
    flex-direction: column;
    .educationHead{
      display: flex;
      .educationTitle{
        color: white;
      }
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
          .resumeIcon{
            
            color:#a57f46;
          }
      }
    }
    .educationList{
      list-style: none ;
      padding: 0;
          .educationListElement{
            width: 350px;
            display: flex;
            align-items: baseline;
            margin-top:10px ;
            .listIcon{
               color: #ceb25c;
               font-size: 12px;
               margin-right: 20px;
               padding-left: 15px ;
            }
            .contentContainer{
              display: flex;
              flex-direction: column;
              align-items: flex-start;
              
              .contentTitle{
                color: white;
                
                display: inline;
                text-align: center;
                margin-bottom: 0px;
              }
              .date{
                color: #ceb25c;
                margin-bottom:0px;
              }
              .contentDescription{
                color: grey;
              }
            }
          }
    }
  }
}

</style>
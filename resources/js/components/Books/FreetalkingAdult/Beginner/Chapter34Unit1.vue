<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://marketplace.canva.com/MADGv8UrE_A/7/screen/canva-aerial-view-photography-of-city-MADGv8UrE_A.jpg" class="cover-photo">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
      >
        <h1 style="background-color: rgba(13, 13, 13, 0.7);
        width: 100%;
        padding-top : 10px;
        padding-left : 10px;
        padding-bottom: 10px;">My City</h1>
      </v-layout>
    </v-img>


          <h3 style="background-color: #a7d7c5;   padding-top : 10px;  padding-left : 10px; padding-bottom: 10px;">Reading Practice <br><span class = "korean">( 선생님의 안내에 따라 문장을 읽어 주세요 )</span></h3>
               <div style="padding : 16px;">

<p>The place I live in is a young city. In fact, it is considered a "baby" because it has not been a city for even a year yet! Because we have many facilities, establishments and a good economy, the government awarded us the status of a city! Our hospital is located along Valencia St, beside San Martin's University. Behind it stands a Buddhist Temple. However, my family goes to a Christian Church located along Privet Drive. Across it is a bakery which sells the best egg pies I have ever tasted. Beside the bakery is a boutique that sells our town's handicrafts such as shell lamps and wooden statues.
</p>

<h3 style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px;margin-top: 10px; background-color: #a7d7c5;">Vocabulary Review</h3>

<div style="padding : 16px;">



<li style="list-style-type: none;"><u>Facility(n)</u> -  something designed to give service <span class = "korean">시설[기관], 기능[특징], 시설, 재능</span>
</li>

<li style="list-style-type: none;"><u>Establishment(n)</u> -  a business, institution, or organization <span class = "korean">기관, 시설, 기득권층, 지배층, 설립, 수립, 확립</span>
</li>

<li style="list-style-type: none;"><u>Economy(n)</u> -   the production and use of resources of a community <span class = "korean">경기; 경제</span>
</li>

<li style="list-style-type: none;"><u>Status(n)</u> -  rank or condition <span class = "korean">신분[자격], 지위, 높은 지위, 중요도, 상황, 특정 사건을 알리다</span>
</li>

<li style="list-style-type: none;"><u>Boutique(n)</u> - a small store selling special goods <span class = "korean">부티크, 양품점(값비싼 옷이나 선물류를 파는 작은 가게)</span>
</li>

<p>Fill in the blanks using the words above.
</p>

<ol style="margin: 12px;">
  <li>Our neighborhood has _________ like a swimming pool, a gym, a sauna and a basketball court!
  </li>

  <li>The commercial __________ in the capital earn much.
  </li>

  <li>Someday I will open a fashion ___________!
  </li>

  <li>What is your secret for having a good health __________?
  </li>

  <li>If people have jobs, the __________ better.
  </li>

</ol>

</div>

<h3  style="padding-top: 7px;  margin-left: -18px; margin-right: -18px;  padding-bottom: 10px;  padding-top: 10px; padding-left: 10px; background-color: #a7d7c5; ">Comprehension</h3>

<div style="padding : 16px;">

<ol style="margin: 12px;">
<li>Why did he call his city a “baby”?
</li>

<li>Why was the place given the status of a city?
</li>

<li>Where is the hospital located?
</li>

<li>Where is the Buddhist temple?
</li>

<li>Where is his family’s church located?
</li>

<li>Where is the bakery? The boutique?
</li>
</ol>

</div>

<h3  style="padding-top: 7px;  margin-left: -18px; margin-right: -18px;  padding-bottom: 10px;  padding-top: 10px; padding-left: 10px; background-color: #a7d7c5; ">Translation</h3>

<div style="padding : 16px;" class = "korean">

  <p>내가 사는 곳은 젊은 도시야. 사실, 그곳은 아직 도시가 된지 1년조차 되지 않았기 때문에 "아기"로 여겨지고 있답니다! 우리는 많은 시설과 시설, 그리고 좋은 경제를 가지고 있기 때문에, 정부는 우리에게 도시의 지위를 주었다! 우리 병원은 발렌시아 가를 따라 산마틴 대학 옆에 있다. 그 뒤에는 절이 서 있다. 하지만 우리 가족은 프리벳 드라이브를 따라 위치한 기독교 교회에 다닌다. 건너편에는 내가 먹어본 가장 맛있는 에그파이를 파는 빵집이 있다. 빵집 옆에는 조개등과 나무조각상 등 우리 마을의 수공예품을 파는 부티크가 있다.
  </p>

</div>



 </div>



       </v-layout>
     </v-container>
</div>
</template>

<script>
export default {

  props: ['fontSize'],

  data(){

    return{
       


    }

  },


  beforeMount(){


  },

  methods:{


  },

  watch:{

    fontSize(current, old){

      console.log(current, 'current')
      console.log(old, 'previous')


    }
  }
}
</script>

<style lang="css">

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}

body{

  font-size: 16px;
}

</style>

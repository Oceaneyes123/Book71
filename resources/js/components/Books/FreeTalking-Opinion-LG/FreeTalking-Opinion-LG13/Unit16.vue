<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/mobile-phone-cases-mockup-product-showcase_53876-96025.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Has the spread of smartphones had a negative influence on Korean culture?
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class = "line-top-lg">
  </div>
  <h3  class = "lower-header-lg white--text">Topic</h3>

  <div style = "padding : 16px; line-height: 1.6;">

    <table class = "standard-table">

    <tr>
      <td class = "uppertable" ><b>David :</b></td>
      <td class = "lowertable" >Smartphones have had a negative influence on Korean culture. Childrentoday communicate more through text messages and are losing social skills. Likewise, many people play too many games on their smartphones and it has caused them to do poorly at work and at school. Many people even check their smartphones during mealtimes and just before they go to sleep. Smartphones are changing Korean society in a bad way.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Smartphones have done wonderful things for Korean culture. Companies like Samsung are able to make lots of money selling smartphones and this gives jobs to many Korean people. In addition, smartphones give people the ability to find the right answers to questions immediately. For example, smartphones make translating between English and Korean very easy. This lets people learn new things more quickly. There is nothing wrong with playing games and smartphones prevent people from getting bored.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>communicate</b> 의사소통을 하다
        </p>
        <p>
          <b>social skill</b> 사교 기술
        </p>
        <p>
          <b>immediately</b> 즉시
        </p>
        <p>
          <b>prevent A from</b> ~ing A가 ~하는 것을 막다
        </p>
        <p>
          <b>get bored</b> 지루해지다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >스마트 폰은 한국 문화에 부정적인 영향을 미칩니다. 아이들은 오늘날 문자 메시지로 더 많이 의사소통을 하고 사교 기술을 잃고 있습니다. 이와 같이, 많은 사람들은 그들의 스마트 폰으로 너무 많은 게임을 하고 직장과 학교에서 제대로 활동하지 못하도록 합니다. 많은 사람들은 식사시간 동안과 그들이 잠자러 가기 바로 전까지도 그들의 스마트 폰을 확인합니다. 스마트 폰은 한국 사회를 형편 없는 방식으로 변화시키고 있습니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >스마트 폰은 한국 문화에 놀라운 일을 해내고 있습니다. 삼성과 같은 회사들은 스마트 폰을 팔아서 많은 돈을 벌고 이것 때문에 많은 한국 사람들이 일자리를 얻습니다. 게다가, 스마트 폰은 사람들에게 즉시 질문에 대한 올바른 정답을 찾을 수 있는 능력을 줍니다. 예를 들면, 스마트 폰은 영어와 한국어의 번역을 매우 쉽게 만들어 줍니다. 이것으로 사람들은 새로운 것을 더 빨리 배울 수 있습니다. 게임을 하는 것은 전혀 잘못되지 않았고 스마트 폰은 사람들이 지루해지는 것을 예방합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do Koreans spend a lot of time on their smartphones?</li>
          <li>Does using a smartphone have a good or bad impact on people?</li>
          <li>In your perspective, what age should children be permitted to use a smartphone?</li>
        </ol>

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
      showTitle:false


    }

  },

mounted(){
  this.showTitle=true
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

<style scoped lang="css">

</style>

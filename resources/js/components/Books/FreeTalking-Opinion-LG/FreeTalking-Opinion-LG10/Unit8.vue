<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/senior-couple-say-hi-look-camera_1150-7825.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Wait, How Old Am I?
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
      <td class = "lowertable" >For thousands of years now, South Korea has been using the East Asian age reckoning system, in which newborns are considered to be age one at birth, instead of zero. According to 10 Magazine, the East Asian age reckoning system originated in China thousands of years ago, but ironically, it’s been decades since China and even North Korea have abandoned this outdated system; instead of opting for the international age system-the preferred structure for most other nations. Today, our globalized world has allowed more people from around the world to experience living abroad than ever before. Thousands of foreigners come to visit or temporarily live here, but South Korea’s age system has created nothing but mass confusion amongst its visitors. In Korean culture, age is necessary in determining one’s status over other individuals. This guides how people should speak to and treat others in society. For this very reason, age standards should be changed to reduce difficulties and eliminate misunderstandings for foreigners.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Globalization has officially set in. The acceleration of world commerce and global communications have spiked at an unprecedented level. From the integration of English education to a Starbucks on every street corner, it seems Korea has fully embraced the western lifestyle. So, it should come as no surprise that Korean society should change their age system to the international standard. Then again, where do we draw the line? At what point does Korea just become another territory of the West? The East Asian age reckoning has been a part of Korean culture for thousands of years. Citizens refer to and identify themselves by their birth year, often establishing a bond with those the same age. Jin Lee of 10 Magazine stated, “Age is necessary in determining the nature and language of subsequent social interactions,” because of the role it plays between older and younger generations.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>reckoning</b> 계산, 추정
        </p>
        <p>
          <b>temporarily</b> 일시적으로
        </p>
        <p>
          <b>outdated</b> ~에게 문의하다, ~을 나타내다
        </p>
        <p>
          <b>refer to</b> 애정
        </p>
        <p>
          <b>subsequent</b> 그 다음의, 차후의
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >수천 년 동안, 한국은 새로 아이가 태어나면 0세 대신 1세로 여기는 동아시아의 나이 계산 시스템을 사용해 왔다. 10매거진에 따르면, 동아시아의 나이 계산 시스템은 중국에서 수천 년 전에 시작되었지만, 아이러니하게도, 중국과 심지어 북한조차 이 케케묵은 시스템을 폐기한 지 수십 년이 지났다, 대부분의 다른 나라에서 선호하는 체계인 국제적인 나이 계산 시스템을 선택하며. 현재, 우리의 세계화된 세계는 전세계 더 많은 사람들이 다른 어느 때보다 해외에서 사는 경험을 하게 하고 있다. 수천 명의 외국인들은 방문이나 일시적으로 살기 위해 이곳에 오지만, 한국의 나이 시스템은 그 방문객들 사이에서 오직 큰 혼란만 일으키고 있다. 한국의 문화에서, 나이는 다른 사람들에 대한 지위를 결정할 때 필요하다. 이것은 어떻게 사람들이 사회에서 말을 하고 다른 사람을 대우해야 하는지를 설명해준다. 바로 이러한 이유 때문에, 나이의 기준은 외국인에게 어려움을 줄이고, 오해를 줄이게 바뀌어야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >세계화는 공식적으로 시작되었다. 세계의 무역과 국제적으로 통신의 가속화가 전례 없는 수준으로 급증했다. 영어 교육의 통합부터 길모퉁이에 있는 스타벅스까지, 한국은 완전히 서양의 생활양식을 수용한 듯 보인다. 그래서, 한국사회가 그 나이 시스템을 국제적인 기준에 맞춰 바꿔야 한다는 것은 전혀 놀랄 일이 아니다. 그렇다면 다시, 우리는 어디에 선을 그어야 하는가? 한국은 어느 시점에 서양의 또 다른 영토가 되었는가? 동아시아의 나이 계산법은 수천 년간 한국문화의 일부가 되었다. 시민들은 출생 년으로 그들 스스로 밝히고, 종종 같은 나이로 유대감을 형성한다. 10 Magazine의 진 리는 구세대와 신세대간 그것이 수행하는 역할 때문에 “나이는 그 후 사회적 상호작용의 본질과 언어를 결정하는 데 있어서 필요하다”라고 썼다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you get confused when you are asked about your age?</li>
          <li>Do you think using the international age system would be easier?</li>
          <li>Which do you think would be more advantageous? East Asian age system or the international age system?</li>
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

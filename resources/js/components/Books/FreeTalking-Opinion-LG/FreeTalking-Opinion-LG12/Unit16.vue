<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/hand-handle-commuting-public-transportation_53876-30278.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Buses Versus Subways
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
      <td class = "lowertable" >Buses are superior to the subway. Not only are they cleaner, but they are also less crowded. In New York, many subway stations haven’t been updated in decades, so they show obvious signs of decay. It’s also pretty common to see rats scurrying up and down the stations. According to Business Insider, cleaning crews are supposed to visit every station in New York City once every three weeks to pick up trash. However, “97 percent of stations receive fewer cleanings than they’re supposed to, and 88 percent of stations received half or fewer than the number of recommended cleanings.” Business Insider added, “It’s often easy to find both a seat and an appropriate amount of personal space outside of rush hour [in a bus]. Some newer buses even have charging ports, which can help prevent your phone from dying in the middle of the afternoon or late at night.” So, why not ride the bus for a change? You’ll see that buses are definitely better. </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Subways are better hands down! First of all, it’s true that subway trains can become extremely crowded during commute hours. However, the same is true for buses in Korea. Although the bus itself is quite roomy, there aren’t enough seats. Plus, because Korean bus drivers tend to be quite abrasive with their driving, it can get pretty chaotic inside a full bus. Holding still on a bus is similar to a balancing act. However, since subway trains move smoothly and in one direction, it’s easier to stand still. In addition, according to the Korea Tourism Organization, the subway is “probably the most favored public transportation by both Koreans and international visitors.” The Seoul Metropolitan Subway is extremely convenient and easy to use. The lines are marked by different colors, making it a breeze to transfer to other lines and get to your destination. Chang Yi, a transportation expert, said, “As a Seoulite and as someone working for the city government, I think it’s world-class.”</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>superior</b> 우수한[우세한 우월한]
        </p>
        <p>
          <b>obvious</b> 명백한
        </p>
        <p>
          <b>decay</b> 부식
        </p>
        <p>
          <b>scurry</b> 종걸음을 치다, 총총[허둥지둥] 가다
        </p>
        <p>
          <b>hands down</b> 수월하게, 명백히
        </p>
        <p>
          <b>commute</b> 통근
        </p>
        <p>
          <b>roomy</b> 널찍한
        </p>
        <p>
          <b>abrasive</b> 거친
        </p>
        <p>
          <b>chaotic</b> 혼돈[혼란] 상태인
        </p>
        <p>
          <b>convenient</b> 편리한, 간편한
        </p>
        <p>
          <b>breeze</b> 쉬운 일
        </p>
        <p>
          <b>Seoulite</b> 서울 사람[시민]
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >버스는 지하철보다 우월하다. 버스는 더 깨끗할 뿐만 아니라 덜 붐빈다. 뉴욕에서는 수십 년 동안 많은 지하철 역들이 새 단장하지 않았기 때문에 명백한 쇠퇴의 징후를 보인다. 정거장을 오르락내리락 하는 쥐들을 보는 것 또한 꽤나 흔한 일이다. 비즈니스 인사이더(Business Insider)에 따르면 청소부들은 쓰레기를 줍기 위해 3주에 한번씩 뉴욕의 모든 역들을 찾아 다녀야 한다. 하지만, “97 퍼센트의 역들이 받아야 하는 청소보다 더 적은 양의 청소를 받으며, 또 88 퍼센트의 역들이 권장 청소 횟수보다 절반 혹은 그보다 적은 청소를 받았다.” 비즈니스 인사이더는 이어서, “보통 출퇴근 시간 외에 [버스 안에서] 앉을 자리와 적당한 정도의 개인 공간을 찾는 것은 쉬운 일이다. 일부 신형 버스에는 충전 포트까지 있어, 오후나 밤늦은 동안 전화기가 꺼지는 것을 방지할 수 있도록 돕는다”고 덧붙였다. 그러니, 변화를 위해 버스를 타보는 것은 어떨까? 버스가 확실히 낫다는 것을 알게 될 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >말할 것도 없이 지하철이 더 낫다! 무엇보다, 지하철이 출퇴근 시간 동안 극도로 혼잡 해 질 수 있다는 것은 사실이다. 하지만, 이는 한국의 버스도 마찬가지다. 버스 자체가 꽤 넓기는 하지만, 좌석이 충분하지 않다. 게다가, 한국의 버스 운전사들은 운전이 다소 거친 경향이 있기 때문에, 만원 버스 안은 상당히 혼란스러워 질 수 있다. 버스에서 가만히 서 있는 것은 균형 잡기와 비슷하다. 하지만, 지하철은 한 방향으로 순조롭게 움직이기 때문에, 가만히 서 있기에 더 쉽다. 더불어, 한국관광공사에 따르면, 지하철은 “한국인과 외국인 방문객 모두에게 가장 인기 있는 대중 교통”이라고 한다. 서울 지하철은 매우 편리하고 사용하기 용이하다. 노선마다 다른 색으로 표시되어 있어 다른 노선으로 갈아타고 목적지에 도착하는 것이 식은 죽 먹기이다. 교통 전문가인 이창씨는, “서울 시민으로서, 그리고 시정을 위해 일하는 사람으로서, 지하철은 세계적인 수준이라고 생각한다”고 말했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is public transportation still widely used in Korea?</li>
          <li>Is it safe to use public transportation in your country?</li>
          <li>Which mode of public transportation is more convenient, the bus or the subway?</li>
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

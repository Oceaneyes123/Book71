<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/3d-electric-car-parked_23-2148972406.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Electric Cars Better Than Regular Cars?
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
      <td class = "lowertable" >Electric cars are better than regular cars in almost every single way. First of all, they are cheaper to run and maintain. According to Ergon Energy, an Australian electric power company, the fuel to charge an electric car costs around a third less per kilometer compared to regular fuel. Furthermore, most electric cars have fewer moving parts than gas-powered cars. Therefore, there are fewer repairs and maintenance issues involved with an electric car. Most importantly, electric cars are better for the environment and for our health. They have zero exhaust emissions, which means less air pollution. You can even charge your electric vehicle through solar-powered or hydrogen-powered stations. Many electric cars are also made with eco-friendly materials. For instance, the Ford Focus Electric and the Nissan Leaf are built with recycled materials. The latter is made with recycled bottles, plastic bags, and even home appliances. Plus, better air quality means better health. What’s not to like? </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Many people are quick to believe that anything is cleaner than gas. However, that’s not really the case. Electric cars have been touted as environmentally friendly automobiles that will replace gas-powered ones. Unfortunately, Julian Marshall, a professor at the University of Minnesota, told the Associated Press, “It’s kind of hard to beat gasoline. A lot of the technologies that we think of as being clean are not better than gasoline.” Marshall’s study, published in the Proceedings of the National Academy of Sciences, revealed that electric cars that charge at coal-fired power stations are likely to cause about three times as many deaths as regular cars. Electric cars are only cleaner than regular cars if they are charged using clean power. Different countries depend on different sources of power, even if the cars are powered by electricity. For example, around 80 percent of China’s electricity is generated from coal. We still have a long way to go. The second speaker demonstrated that this isn’t simply a black-and-white issue. Although electric cars come with many benefits, fuel sources are important as well. Where do you stand? Do you believe electric cars are better than regular cars? Why or why not?</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>repair</b> 수리
        </p>
        <p>
          <b>maintenance</b> 유지
        </p>
        <p>
          <b>eco-friendly</b> 친환경적인
        </p>
        <p>
          <b>latter</b> (둘 중에서) 후자
        </p>
        <p>
          <b>appliance</b> (가정용) 기기
        </p>
        <p>
          <b>tout</b> 장점을 내세우다
        </p>
        <p>
          <b>automobile</b> 자동차
        </p>
        <p>
          <b>coal</b> 석탄
        </p>
        <p>
          <b>generate</b> 발생시키다, 만들어 내다
        </p>
        <p>
          <b>demonstrate</b> 입증하다
        </p>
        <p>
          <b>black-and-white</b> 흑백이 뚜렷한 (논리 등)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >전기자동차는 거의 모든 면에서 일반자동차보다 낫다. 먼저, 그것들은 달리고 유지하기에 더 싸다. 호주의 전력회사인 Ergon Energy에 따르면, 전기차를 충전하는 연료의 비용은 일반적인 연료와 비교하여 1킬로미터 당 약 1/3이 덜 든다. 게다가, 대부분의 전기자동차는 기름으로 달리는 자동차보다 더 적은 움직이는 부품을 가지고 있다. 그러므로, 전기자동차와 관련된 더 적은 수리와 유지 문제가 있다. 가장 중요한 것은, 전기차는 환경과 우리의 건강에 더 좋다. 그것들은 배기 가스를 전혀 배출하지 않고, 이것은 더 적은 대기 오염을 의미한다.. 당신은 심지어 당신의 전기자동차를 태양열 또는 수소를 원료로 하는 충전소를 통해 충전할 수 있다. 많은 전기자동차는 친환경 재료로도 만들어진다. 예를 들어, Ford Focus Electric과 Nissan Leaf는 재활용된 재료로 만들어진다. 후자는 재활용된 병, 비닐봉지, 그리고 심지어 가정용 전기제품으로 만들어진다. 게다가, 더 나은 공기질은 더 나은 건강을 의미한다. 안 좋아할게 뭐가 있는가?</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >많은 사람들은 아무것이나 가솔린보다 더 깨끗하다고 재빨리 믿어버린다.  그러나 실제로는 그렇지 않다. 전기자동차는 가솔린으로 동력을 공급하는 자동차를 대체할 환경 친화적인 자동차로서의 장점이 있다고 내세워졌다. 불행하게도, 미네소타 대학의 Julian Marshall 교수는 Associated Press에 “휘발유를 이기는 것은 약간 어렵습니다. 우리가 깨끗하다고 생각하는 많은 기술은 가솔린보다 더 낫지 않습니다”라고 말했다. 국립과학원회보에 게재된 Marshall의 연구는 석탄을 때는 화력 발전소에서 충천하는 전기자동차는 아마도 일반자동차보다 약 3배 많은 사망을 야기할 것 같다고 말했다. 만일 전기자동차가 깨끗한 전력을 사용하여 충전된다면 전기자동차는 일반자동차보다 더 깨끗할 뿐이다. 비록 그 자동차가 전기에 의해 전력을 공급받을지라도, 나라마다 다른 전력원에 의존한다. 예를 들어, 중국 전기의 약 80%는 석탄으로부터 만들어진다. 우리는 아직도 갈 길이 멀다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are the pros and cons of electric cars?</li>
          <li>Should the government encourage the use of electric vehicles to reduce pollution?</li>
          <li>Do you want to drive an electric car in the future? Why?</li>
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

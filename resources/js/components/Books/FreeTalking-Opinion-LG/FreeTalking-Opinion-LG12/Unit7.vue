<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/set-pecan-pistachios-almond-peanut-cashew-pine-nuts-lined-up-assorted-nuts-dried-fruits-mini-different-bowls_176474-2051.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Nuts Healthy?
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
      <td class = "lowertable" >Nuts are very good for you. In fact, they are a great source of many nutrients. An ounce, or 28 g, of mixed nuts contains 5 g of protein, 3 g of fiber, and significant amounts of vitamin E, magnesium, phosphorus, copper, manganese, and selenium. Although nuts are generally high in fat, they are low in carbohydrates, making them the perfect snack for those who are on a low carb diet. Furthermore, nuts are loaded with antioxidants, which, according to the journal Clinical Interventions in Aging, can combat oxidative stress by neutralizing unstable molecules that may cause cell damage and increase the risk of certain diseases. Various studies show that nuts, particularly walnuts and almonds, can protect cells from being damaged by oxidation. In addition, nuts have been proven to aid in weight loss. One study found that overweight women who ate almonds lost nearly three times as much weight compared to the control group. Thus, we should incorporate more nuts into our diet.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Nuts aren’t good for your health, and they’re definitely not good for the environment either. Many types of nuts are full of calories and fat. A cup of macadamia nuts, for instance, contains nearly 1,000 calories, and the same serving also has 102 g of fat. Peanuts are full of calories as well, and they are prone to contamination. Moldy, discolored peanuts may contain aflatoxins, which are poisonous carcinogens. Also, some people, even if they don’t have any food allergies, experience a phenomenon called pine nut syndrome 12 to 48 hours after eating these nuts. This makes everything they eat taste bitter and metallic. Plus, although they look similar to regular chestnuts, horse chestnuts contain a toxin that causes vomiting and even paralysis. And even though almonds are good for the body, they aren’t good for the environment. Growing a single almond requires around a gallon of water, negatively affecting the salmon population. Therefore, we must stay away from nuts.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>carbohydrate</b> 탄수화물
        </p>
        <p>
          <b>antioxidant</b> 항산화물질
        </p>
        <p>
          <b>neutralize</b> 중화시키다
        </p>
        <p>
          <b>oxidation</b> 산화
        </p>
        <p>
          <b>incorporate</b> 포함하다
        </p>
        <p>
          <b>prone</b> 하기[당하기] 쉬운
        </p>
        <p>
          <b>contamination</b> 오염, 오탁
        </p>
        <p>
          <b>carcinogen</b> 발암 물질
        </p>
        <p>
          <b>phenomenon</b> 현상
        </p>
        <p>
          <b>bitter</b> 맛이 쓴
        </p>
        <p>
          <b>paralysis</b> 마비
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >견과류는 당신에게 매우 좋다. 사실, 그것들은 많은 영양소들의 훌륭한 공급원이다. 1 온스 혹은 28g 의 섞은 견과류는 5g의 단백질과 3g의 섬유질 그리고 상당한 양의 비타민 E, 마그네슘, 인, 구리, 망간 그리고 셀레늄을 포함하고 있다. 비록 견과류가 보통 지방이 많이 함유되어 있지만 탄수화물이 낮기 때문에 저탄수화물 다이어트를 하는 이들에게는 완벽한 음식이 된다. 게다가 견과류는 항 산화물질로 가득 차 있는데 이 항 산화물질은 노화에 대한 임상연구 저널에 따르면 세포 손상과 특정 질병의 위험을 높일 수 있는 불안정한 분자들을 중화시키는 방식으로 산화스트레스와 싸울 수 있다고 한다. 다양한 연구들이 견과류들, 특히 호두와 아몬드가 세포들이 산화로 손상되는 것으로부터 보호할 수 있는 것을 보여준다. 게다가 견과류는 체중감량에도 도움이 된다고 증명되었다. 한 연구는 아몬드를 섭취한 과체중 여성들이 통제집단에 비해 거의 3배나 체중 감량을 한 것을 발견해냈다. 그러므로 우리는 우리의 식사에 더 많은 견과류를 포함시켜야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >견과류는 당신의 건강에 좋지 않고 분명히 환경에도 좋지 않다. 다양한 종류의 견과류는 칼로리와 지방으로 가득 차 있다. 예를 들어 한 컵의 마카다미아 넛은 거의 1000 칼로리를 포함하고 있으며 이 양은 또한 102g의 지방을 함유하고 있다. 땅콩은 또한 칼로리로 가득 차 있고 오염되기 쉽다. 곰팡이가 피고 변색된 땅콩들은 아플라톡신을 함유하고 있을 수 있는데, 이는 유독한 발암물질이다. 그리고 어떤 사람들은 비록 어떤 음식 알러지를 가지고 있지 않더라도 이 견과류를 섭취한 뒤 12시간에서 48시간까지 파인 넛 신드롬이라 불리는 현상을 겪게 된다. 이 현상은 그들이 먹는 모든 것의 맛이 쓰고 금속 맛이 나게 한다. 게다가 마로니에 열매는 비록 보통의 밤과 비슷하게 보이지만, 구토와 심지어 마비를 유발하는 독소를 함유하고 있다. 그리고 아몬드가 몸에 좋다고 하지만 그들은 환경에는 좋지 않다. 하나의 아몬드가 자라나는데 1갤런 정도의 물이 필요하고, 이것은 연어의 개체수에 악영향을 준다 그러므로 우리는 견과류를 멀리해야만 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is it healthy to eat nuts everyday? Why do you think so?</li>
          <li>What are the benefits of eating nuts?</li>
          <li>What are the risks of eating nuts most of the time?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/two-big-hermetic-packages-with-blank-labels-near-transparent-glass-with-raw-sampled-coffee-beans_346278-410.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Labels Be Introduced on Food?
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
      <td class = "lowertable" >Don’t you want to know what is in the food you eat? Consumers should be given all the information, so that they can choose whether or not to buy certain products. This is especially true about GMO. GMO is a plant or meat product that “has had its DNA artificially altered in a laboratory by genes from other plants, animals, viruses, or bacteria.” GMO has not been proven safe and the long-term health risks on humans haven't been sufficiently investigated. Although 61 countries, including the entire European Union and China, label genetically engineered foods, the United States and Canada do not require such labeling. However, a 2013 poll conducted by the New York Times found that 93 percent of respondents agreed that food that has been genetically modified should be labeled.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >In 2012, California introduced Proposition 37, a bill that would have required labeling of genetically engineered food. Many believed that if the proposition was accepted in California, it would increase the possibility that other states would introduce the same rules, which in turn, would make it more likely that the national government would become involved and take action. However, opponents of the proposition strongly argued that the bill would “increase annual state costs” (and therefore taxes) “to regulate the labeling of genetically engineered food.” In the end, Proposition 37 was rejected by voters: 51 percent to 48 percent.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>GMO</b> 유전자 변형 농산물(genetically modified organism)
        </p>
        <p>
          <b>artificially</b> 인위적으로, 부자연스럽게
        </p>
        <p>
          <b>altered</b> 바뀐
        </p>
        <p>
          <b>genetically engineered</b> 유전자 공학[조작]에 의해 생성된(GE)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >당신이 먹는 음식에 무엇이 들어 있는지 알고 싶지 않은가? 소비자들은 그들이 어떤 식품을 구매 할 것인지 선택할 수 있도록 모든 정보를 제공 받아야 한다. 유전자 조작 식품에 관해서는 특히 그러하다. 유전자 조작 식품이란 식물 혹은 고기가 실험실에서 다른 식물, 동물, 바이러스 혹은 박테리아의유전자에 의해 DNA 가 인위적으로 바뀐 것을 말한다. 유전자 조작 식품은 안전하다고 증명 된 적이 없고 장기적인 건강 위험도 충분히 조사된 바가 없다. 전체 유럽연합, 중국을 포함한 61개국들이 유전자 공학에 의해 생성된 음식에 식품 내용 표시를 하지만, 미국과 캐나다는 그러한 표시를 요구하지 않는다. 하지만, 뉴욕 타임즈에 의해 시행된 2013 조사에 따르면 93%의 응답자들이 유전자 조작 식품은 내용이 표시 돼야 한다는 것에 동의 했다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >2012년, 캘리포니아는 유전자 공학에 의해 생성 된 음식에 내용 표시를 요구하는 제안 37을 소개했다. 많은 사람들은 만약 그 제안이 캘리포니아에서 받아들여졌다면 다른 주들도 같은 규정을 도입 했을 것이고 결과적으로 중앙 정부가 이에 개입하고 결정하는 결과를 초래했을 것이다. 하지만, 이 제안의 반대자들은 그 법안이 “유전자 공학에 의해 생성된 음식을 규제하기 위해 주의 연간 비용 (이어서 증세를 부과)을 증가 시킬 것”이라며 강하게 반박했다. 결국, 제안 37은 51% : 48%로 투표자들에 의해 거부 됐다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>When you buy food from the grocery, do you usually read the label? Why or why not?</li>
          <li>Do you think that food labels are accurate?</li>
          <li>Do you think all food products should have labels?</li>
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

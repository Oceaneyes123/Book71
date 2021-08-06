<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/pickled-vegetables-with-white-background_23-2148606779.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is MSG Unhealthy?
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
      <td class = "lowertable" >More and more people are promoting the idea that MSG isn’t unhealthy, but it’s not entirely harmless. Many people experience something known as MSG symptom complex, which was called Chinese restaurant syndrome in the past. Common symptoms include headaches, sweating, nausea, and fatigue. In a study published in the Journal of Allergy and Clinical Immunology, over 36 percent of the participants reported having adverse reactions to MSG. According to researcher Jennifer Xiong, large doses of MSG might cause traces of glutamic acid to interact with neurons in the brain, making the brain swell. In another study, also in the Journal of Allergy and Clinical Immunology, 40 percent of the participants had allergic reactions after consuming high amounts of MSG. Furthermore, a 2008 study in the journal Obesity linked MSG intake with weight gain, stating, “The prevalence of being overweight was significantly higher in MSG users than nonusers.” Therefore, it’s best to avoid MSG.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >MSG is not bad for your health. Many people are simply misinformed. First of all, MSG is derived from glutamic acid, which is one of the most abundant amino acids found in nature. Glutamic acid is found in many foods, including tomatoes, grapes, cheese, as well as mushrooms, and the human body produces it, too. According to healthline.com, the average daily intake of MSG in the U.S. and the U.K. is a little less than 0.6 g, and in Korea and Japan, the average is around 1.5 g. Even though MSG is widely consumed in Asia, most complaints about this “Chinese restaurant syndrome” come from Western countries. Many affordable restaurants in these countries, especially the U.S., season their dishes generously with salt, which is associated with most of this syndrome’s symptoms. Thus, it’s actually the salt content that should be blamed, but stereotypes are hard to shake off. MSG is safe to consume, and it makes things taste better, too.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>nausea</b> 메스꺼움
        </p>
        <p>
          <b>fatigue</b> 피로
        </p>
        <p>
          <b>adverse</b> 부정적인
        </p>
        <p>
          <b>trace</b> 극미량, 조금
        </p>
        <p>
          <b>swell</b> 붓다
        </p>
        <p>
          <b>prevalence</b> 널리 퍼짐, 유행, 보급
        </p>
        <p>
          <b>misinformed</b> 잘못된 정보를 받고 있는
        </p>
        <p>
          <b>intake</b> 섭취(량)
        </p>
        <p>
          <b>season</b> (양념을) 넣다[치다]
        </p>
        <p>
          <b>generously</b> 아주 많이
        </p>
        <p>
          <b>stereotype</b> 고정 관념, 정형화된 생각
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >점점 더 많은 사람들이 MSG가 건강에 해롭지 않다는 견해를 조장하고 있지만, MSG가 완전히 무해한 것은 아니다. 만은 사람들이 MSG복합증후군(MSG symptom complex)이라는 것을 경험하는데, 과거에는 이를 중국음식점 증후군이라고 일컬었다. 일반적인 증상으로는 두통, 발한, 메스꺼움 및 피로 등이 있다. 알레르기 임상면역학 저널(Allergy and Clinical Immunology)에 게재된 한 연구에서 참가자의 36% 이상이 MSG에 대한 부작용이 있다고 보고하였다. 연구원인 제니퍼 슝(Jennifer Xiong)에 따르면, 다량의 MSG은 글루탐산의 흔적이 뇌 속의 뉴런과 상호작용하도록 하여 뇌에 부종을 유발할 수 있다고 한다. 알레르기 임상면역학 저널에 게재된 또 다른 연구에서는, 참가자의 40%가 다량의 MSG를 섭취한 후 알레르기 반응을 보였다. 또한, 학술지 오비시티(비만)에 게재된 2008년 연구는 "비만 발병률이 MSG를 사용하지 않는 사람보다 사용자에게서 현저히 높았다"고 서술하며 MSG 섭취를 체중 증가와 연관지었다. 따라서, MSG는 피하는 것이 최선이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >MSG는 당신의 건강에 해롭지 않다. 많은 사람들이 잘못된 정보를 가지고 있는 것일 뿐이다. 우선 MSG는 글루탐산(glutamic acid)에서 파생되며, 이는 자연에서 가장 풍부하게 찾아볼 수 있는 아미노산 중 하나이다. 글루탐산은 토마토, 포도, 치즈 그리고 버섯 등을 포함하는 다양한 식품에서 발견되며, 인체에서도 생성된다. 헬스라인 닷 컴(healthline.com)에 따르면 미국과 영국의 하루 평균 MSG 섭취량은 0.6g에 조금 못 미치고, 한국과 일본의 경우 평균 1.5g 안팎이다. MSG는 아시아에서 널리 소비되고 있지만, 이 “중국 음식점 증후군”에 대한 불만은 대부분 서방 국가에서 비롯된다. 해당 국가들, 특히 미국의 경우, 다수의 저렴한 식당들이 그들의 요리에 소금을 듬뿍 넣어 양념하는데, 소금은 증후군의 대부분 증상과 관련이 있다. 따라서, 실제로 비난 받아야 할 것은 소금 함량이지만, 고정관념은 떨쳐버리기 힘들다. MSG는 섭취해도 안전하며, 음식의 맛 또한 좋게 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is MSG harmful to one's health?</li>
          <li>Do Koreans like to use MSG as a food ingredient in cooking?</li>
          <li>Can MSG cause side effects such as allergies?</li>
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

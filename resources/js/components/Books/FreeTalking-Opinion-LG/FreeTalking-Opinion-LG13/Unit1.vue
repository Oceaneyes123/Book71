<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/leaves_1417-1533.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Chinese Herbal Medicine
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
      <td class = "lowertable" >Chinese herbal medicine is definitely effective and should not be disregarded. It has been used for centuries in China, where herbs are used to treat many acute and chronic conditions. According to Cleveland Clinic, an academic medical center in Ohio, “Chinese herbs can address unhealthy body patterns that manifest in a variety of symptoms and complaints. The aims of Chinese herbal therapy are to help you regain balance in your body and to strengthen your body’s resistance to disease.” In addition to decreasing flu symptoms, improving digestion, and alleviating pain, Chinese herbs are useful in the rehabilitation from many chronic diseases. Furthermore, according to the U.S. National Center for Complementary and Integrative Health (NCCIH), one in five Americans use Chinese herbal products. One reason why so many people rely on Chinese medicine is the fact that it does not have very many side effects. The few side effects that do come with Chinese herbal medicine are practically harmless. It should be taken more seriously.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Chinese herbal medicine is not a trustworthy form of treatment. Studies about it are inconclusive. According to the NCCIH, “Chinese herbal products have been studied for many medical problems, including stroke, heart disease, mental disorders, and respiratory diseases. Because many studies have been of poor quality, no firm conclusions can be made about their effectiveness.” There are also safety concerns. The NCCIH stated, “Some Chinese herbal products have been found to be contaminated with undeclared plant or animal material, drugs, pesticides, and incorrect herbs, some of which have caused organ damage.” According to The Guardian, “Herbal medicines can cause kidney failure and liver damage in some consumers because they contain toxic chemicals or heavy metals, or react harmfully with other drugs.” Moreover, Ian Musgrave, an Australian toxicologist, said that herbs can be a source of very potent toxins. Thus, Chinese herbal medicine should be used as a last resort, and you must consult your doctor before making the decision to start herbal therapy.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>disregard</b> 무시[묵살]하다
        </p>
        <p>
          <b>acute</b> (질병이) 급성의
        </p>
        <p>
          <b>chronic</b> 만성적인
        </p>
        <p>
          <b>manifest</b> 나타나다
        </p>
        <p>
          <b>trustworthy</b> 신뢰할[믿을] 수 있는
        </p>
        <p>
          <b>inconclusive</b> (확고한 결정·결과에 이를 정도로) 결정적이 아닌, 결론에 이르지 못하는
        </p>
        <p>
          <b>contaminate</b> 오염시키다
        </p>
        <p>
          <b>pesticide</b> 살충제, 농약
        </p>
        <p>
          <b>toxicologist</b> 독물학자
        </p>
        <p>
          <b>potent</b> 강한[강력한]
        </p>
        <p>
          <b>consult</b> 의견을 묻다, 상담[상의]하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >중국 한방약은 확실히 효과가 있으므로 무시해서는 안된다. 그것은 중국에서 수세기 동안 사용되어 왔는데, 약초는 많은 급성과 만성적인 상태를 치료하는데 사용된다. 오하이오 주의 한 학술 의료센터인 클리브랜드 클리닉에 따르면, “중국 약초는 다양한 증상과 불안에서 나타나는 건강하지 못한 신체 패턴을 치료할 수 있다. 중국 한방 치료의 목적은 몸의 균형을 되찾게 해주고, 병에 대한 저항을 강화하는 것이다.” 한방 약초는 독감 증상 감소, 소화 개선, 통증 완화뿐만 아니라 많은 만성 질환의 재활에 유용하다. 게다가, 미국보완대체의학국(NCCIH)에 따르면, 미국인 다섯 명 중 한 명이 중국 약초 제품을 사용하고 있다고 한다. 많은 사람들이 한약에 의존하는 한 가지 이유는 한약이 많은 부작용을 가지고 있지 않기 때문이다. 중국의 한방약과 함께 나타나는 몇 가지 부작용은 사실상 해롭지 않다. 그것은 좀 더 심각하게 받아들여야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >한방약은 신뢰할 수 있는 치료법이 아니다. 그것에 대한 연구는 결론에 이르지 못했다. NCCIH에 따르면, “중국 한방 제품은 뇌졸중, 심장병, 정신 질환, 호흡기 질환 등 많은 의학적 문제를 연구해 왔다. 많은 연구들이 질이 좋지 않았기 때문에 그 효과에 대한 확실한 결론을 내릴 수 없다.” 안전에 대한 우려도 있다. NCCIH는 “신고되지 않은 식물이나 동물성 물질, 약물, 살충제, 잘못된 약초 등에 오염된 중국산 한방제품이 일부 발견되어 장기에 손상을 입혔다.”고 진술했다. 가디언지에 따르면, “한약들은 독성 화학물질이나 중금속을 함유하고 있거나 다른 약들과 유해하게 반응하기 때문에 일부 소비자들에게 신장 기능 저하와 간 손상을 일으킬 수 있다.” 게다가, 호주의 독성학자인 이안 머스그레이브는 허브가 매우 강력한 독소의 원천이 될 수 있다고 말했다. 그러므로, 한방 치료는 최후의 수단으로 이용되어야 하고, 여러분은 한방 요법을 시작하기로 결정하기 전에 의사와 상의해야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Have you ever tried Chinese herbal medicine?</li>
          <li>Are Chinese herbal medicines safe?</li>
          <li>What do you think are the benefits of using Chinese herbal medicines?</li>
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


<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/woman-takes-shows-pills_1153-5089.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Multivitamins Healthy?
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
      <td class = "lowertable" >Multivitamins are good for your health. They contain around 13 vitamins and 16 minerals that are deemed essential to your health. According to healthline.com, “Your body needs these nutrients for reproduction, maintenance, growth, and regulation of bodily processes.” In addition, several studies suggest that multivitamins are linked to a reduced risk of heart attacks. According to a study published in the Journal of Nutrition, taking multivitamins for at least three years was correlated with a 35 percent lower risk of dying from heart disease. Furthermore, multivitamins can help reduce the risk of developing cancer. According to a study in the Annals of Internal Medicine, taking multivitamins can reduce the risk of colon cancer by 31 percent. Plus, several studies have found that multivitamins can improve memory in older adults, improve mood, and reduce symptoms of depression. Multivitamins can even slow down the progression of age-related macular degeneration, one of the leading causes of blindness. Thus, more people should take multivitamins.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Multivitamins are ineffective, and they can even harm your health. Many studies state that multivitamins have no effect on heart health. According to a decade-long study published in The Journal of the American Medical Association, there were no reductions in heart attacks or strokes among the 14,000 participants. In addition, multivitamins can even lead to an increased risk of cancer. According to Fang Fang Zhang, an associate professor at Tufts University, “As potential benefits and harms of supplement use continue to be studied, some studies have found associations between excess nutrient intake and adverse outcomes, including increased risk of certain cancers.” She also said that people should focus on having a healthy diet instead of relying on multivitamins. Moreover, multivitamins can cause many side-effects. Pregnant women should avoid supplements with high amounts of vitamin A, which is associated with birth defects. Smokers should take this advice as well, since excess vitamin A is linked to lung cancer. Multivitamins are completely unnecessary.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>supplement</b> 보충제
        </p>
        <p>
          <b>deem</b> 여기다
        </p>
        <p>
          <b>essential</b> 필수적인
        </p>
        <p>
          <b>correlate</b> 연관성이 있다
        </p>
        <p>
          <b>colon</b> 결장
        </p> 
        <p>
          <b>macular degeneration</b> 시력 감퇴
        </p>
        <p>
          <b>ineffective</b> 효과 없는
        </p>
        <p>
          <b>stroke</b> 뇌졸중
        </p>
        <p>
          <b>excess</b> 초과한
        </p>
        <p>
          <b>adverse</b> 부정적인
        </p> 
        <p>
          <b>side-effect</b> 부작용
        </p> 
        <p>
          <b>sufficient</b> 충분한
        </p> 
        <p>
          <b>deficiency</b> 결핍증
        </p> 
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >종합비타민은 건강에 좋다. 그것은 건강에 필수적이라고 여겨지는 약 13종의 비타민과 16종의 무기질을 함유하고 있다. healthline.com에 따르면, “당신의 몸은 신체 과정의 재생, 유지, 성장 및 통제를 위해 이러한 영양소가 필요하다.” 게다가 여러 연구에서 종합비타민이 감소된 심장마비의 위험과 연관이 있다고 시사한다. 영양학회지에 실린 한 연구에 따르면, 종합 비타민을 최소 3년 동안 섭취하는 것은 심장병으로 사망하는 위험을 35% 낮춰주는 것과 연관이 있었다. 뿐만 아니라, 종합비타민은 암 발생의 위험을 줄이는 것을 도울 수 있다. 내과학 회보의 한 연구에 따르면, 종합비타민을 먹는 것은 대장암의 위험을 31% 줄여줄 수 있다. 뿐만 아니라 여러 연구가 노년의 기억을 개선시킬 수 있고, 기분을 향상시키며 우울증의 증상을 감소시킬 수 있다는 것을 발견했다. 종합비타민은 심지어 실명의 주요 원인 중 하나인 나이와 관련 있는 시력 감퇴의 진행을 늦출 수 있다. 그러므로 더 많은 사람들이 종합 비타민을 먹어야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >종합비타민은 효과가 없고 그것은 심지어 당신의 건강을 해칠 수 있다. 많은 연구가 종합비타민이 심장 건강에 아무런 효과가 없다고 진술한다. 미국의학협회저널에 게재된 10년간 진행된 연구에 따르면, 14,000명의 참가자 중 심장마비 또는 뇌졸중에 감소가 없었다. 게다가, 종합비타민은 심지어 암의 위험을 높이게 될 수도 있다. 터프츠대학교의 부교수인 팡팡장에 따르면, “보조제 사용의 잠재적인 유익과 피해는 계속해서 연구되며, 일부 연구는 특정 암의 증가된 위험을 포함하여 과도한 영양소 섭취와 부정적인 결과 사이의 연관성을 발견했다. 그녀는 또한 종합비타민제에 의존하기 보다는 건강한 식단을 가지는 데 집중하여야 한다고 말했다. 게다가, 종합비타민제는 많은 부작용을 일으킬 수 있다. 임신한 여성은 선천적 장애와 연관 있는 비타민 A가 많이 함유된 보조제를 피해야만 한다. 흡연자 역시 이 조언을 받아들여야 하는데, 이는 과다한 비타민 A가 폐암과 연관이 있기 때문이다. 종합비타민제는 완전히 불필요하다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you take multivitamins?</li>
          <li>Are multivitamins good for health?.</li>
          <li>What are the side effects of taking multivitamins?</li>
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

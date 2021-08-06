
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/various-types-sugar-brown-sugar-white-concrete-top-view_114579-4997.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Artificial Sweeteners Harmful?
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
      <td class = "lowertable" >Research shows that most artificial sweeteners are unsafe and detrimental to your health. According to a study from Purdue University, artificial sweeteners come with side effects such as headaches, migraines, weight gain, and serious conditions like cardiovascular disease. Furthermore, Holly Strawbridge, a former editor at Harvard Health, states that artificial sweeteners can lead to sugar addiction. They don’t provide any sense of satisfaction, and this can cause sugar-deprived people to find comfort in sweet foods. Thus, a dependence on artificial sweeteners can eventually result in obesity, diabetes, kidney damage, and other health problems. Moreover, many sugar-free products contain aspartame, a notorious sugar substitute. In addition to causing headaches, aspartame has been found to impair memory performance and predispose babies to obesity later in life. Worst of all, according to the American Journal of Industrial Medicine, aspartame has carcinogenic effects. </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >An article in the Annals of Oncology states that more than 50 studies about the carcinogenic effects of saccharin, a sugar alternative, have been published. But none of these experiments involved any humans. Only mice were tested on, and they’re known to be more susceptible to developing disorders. Newer studies were done, and saccharin was removed from the U.S. government’s list of carcinogens. As for aspartame, it has had a poor reputation since 1996, when a study about it possibly causing cancer was released. Many people focused on these points: Brain cancer became more common from 1975 to 1992, and many people consumed aspartame during that period. However, the increase in cancer was found mostly in the elderly, who weren’t the main consumers of aspartame. Plus, aspartame was approved in 1981, so how could it have caused cancer in the 1970s? </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>sweetener</b> 감미료
        </p>
        <p>
          <b>aspartame</b> 아스파르테임(단맛이 아주 강한 합성 감미료)
        </p>
        <p>
          <b>detrimental</b> 해로운
        </p>
        <p>
          <b>migraine</b> 편두통
        </p>
        <p>
          <b>deprive</b> 빼앗다
        </p>
        <p>
          <b>comfort</b> 위로, 위안
        </p>
        <p>
          <b>predispose</b> (병에) 걸리기 쉽게 하다
        </p>
        <p>
          <b>carcinogenic</b> 발암성의
        </p>
        <p>
          <b>susceptible</b> 민감한
        </p>
        <p>
          <b>reputation</b> 평판
        </p>
        <p>
          <b>focus</b> 집중하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >연구는 대부분의 인공 감미료가 안전하지 않고 당신의 건강에 해롭다는 것을 보여준다. Purdue 대학의 한 연구에 따르면, 인공 감미료들은 두통, 편두통, 몸무게 증가, 그리고 심장혈관계질병과 같은 심각한 상태들과 같은 부작용이 딸려 있다. 게다가, Harvard Health의 전 편집장인 Holly Strawbridge는 인공 감미료가 설탕 중독에 이르게 할 수 있다고 말한다. 그것들은 어떠한 만족이라는 감각을 제공하지 않고, 이것은 설탕이 부족한 사람들이 달콤한 음식에서 위안을 발견하도록 야기할 수 있다. 그러므로, 인공 감미료에 대한 의존은 마침내 비만, 당뇨병, 신장 손상, 그리고 다른 건강 문제라는 결과를 낳을 수 있다. 게다가, 많은 무설탕 삼풍들은 악명 높은 설탕 대체물인 아스파르테임을 포함한다. 두통을 일으키는 것 이외에도, 아스파르테임은 기억 성능을 손상시키고 아기들이 나중에 비만을 갖게 하는 성향을 만든다고 발견되었다. 가장 나쁜 것은, American Journal of Industrial Medicine에 따르면, 아스파르테임은 발암 효과를 가지고 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >Annals of Oncology의 논문은 설탕 대체제인 사카린에 대한 발암 효과에 관한 50편 이상의 연구들이 출판되었다고 말한다. 그러나 이 실험들 중 어떤 것도 어떠한 사람도 포함하지 않았다. 쥐들만 실험되었고, 그것들은 발병하는데 더 민감하다고 알려져 있다. 더 새로운 연구가 이루어졌고, 사카린은 미국 정부의 발암 물질 목록으로부터 제거되었다. 아스파르테임에 관해 말하자면, 그것은 그것이 아마도 암을 야기할 수 있다는 것에 관한 연구가 발표되었던 1996년부터 나쁜 명성을 가지고 있다. 많은 사람들은 이런 점들에 집중했다: 뇌종양은 1775년부터 1992년까지 더 흔해졌고, 많은 사람들은 그 기간 동안 아스파르테임을 소비했다. 그러나 암의 증가는 대부분 아스파르테임의 주요 소비자가 아니었던 어르신들에게서 발견되었다. 게다가, 아스파르테임은 1981년에 승인되었으므로, 그것이 어떻게 1970년대에 암을 일으킬 수 있었겠는가?</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Are artificial sweeteners a healthy part of your diet? Explain.</li>
          <li>Are artificial sweeteners worse than sugar?</li>
          <li>What are the side effects of artificial sweeteners?</li>
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

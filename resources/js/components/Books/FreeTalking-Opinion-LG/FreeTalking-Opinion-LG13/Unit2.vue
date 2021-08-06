`
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/sausage-assortment-salami-pepperoni-ham-wooden-board_140725-10639.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Processed Meat
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
      <td class = "lowertable" >Processed meats are clearly unhealthy, as they have been linked with diseases like cancer and heart disease in numerous studies. Let’s explore why this is the case. First of all, eating high amounts of processed meat is more prevalent among people with unhealthy lifestyles. According to a study in the International Journal of Behavioral Nutrition and Physical Activity, smoking is more common among those who eat processed meats regularly. Moreover, their intake of fruits and vegetables is also lower. A study in BMC Medicine also concluded that there is “a moderate positive association between processed meat consumption and mortality, in particular due to cardiovascular diseases, but also to cancer.” In fact, eating processed meat is associated with an increased risk of many chronic diseases, including cancer. A study in Cancer Prevention Research found that eating processed meat raises the risk of bowel cancer after conducting a long study involving rats. Thus, it is imperative that people reduce their intake of processed meats. </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Processed meat has an unwarranted reputation as a life-threatening carcinogen. There are several studies debunking this myth. According to meatmythcrushers.com, “One of the largest studies ever done, in which data from 14 major studies was pooled, found that there was no association between red and processed meat and cancer. Furthermore, a comprehensive study on processed meat and colon cancer concluded that there was insufficient evidence to support a link between the two.” In addition, processed meat encompasses a broad spectrum. The site explained, “Processed meat certainly has been stigmatized in recent years, but it’s important to remember that all meat must be processed before it is consumed.” Most studies linking processed meat with cancer show that people who eat processed meat are more likely to suffer from hypertension, heart disease, and different forms of cancer. However, they cannot prove that processed meat is actually the cause. Therefore, there is no need to avoid processed meats entirely.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>prevalent</b> 일반적인[널리 퍼져 있는]
        </p>
        <p>
          <b>intake</b> 섭취(량)
        </p>
        <p>
          <b>mortality</b> 사망자 수[사망률]
        </p>
        <p>
          <b>chronic</b> 만성적인
        </p>
        <p>
          <b>imperative</b> 반드시 해야 하는
        </p>
        <p>
          <b>unwarranted</b> 부당한, 부적절한
        </p>
        <p>
          <b>carcinogen</b> 발암 물질
        </p>
        <p>
          <b>debunk</b> (생각·믿음 등이) 틀렸음을 드러내다[밝히다]
        </p>
        <p>
          <b>encompass</b> (많은 것을) 포함하다
        </p>
        <p>
          <b>stigmatize</b> 오명을 씌우다, 낙인 찍다
        </p>
        <p>
          <b>hypertension</b> 인고혈압(증)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >가공육은 수많은 연구에서 암과 심장병과 같은 질병들과 연관되어 왔기 때문에 분명히 건강에 좋지 않다. 그 이유를 살펴보자. 첫번째로, 많은 양의 가공육을 먹는 것은 건강하지 않은 생활방식을 가진 사람 사이에서 더 널리 퍼져있다. 행동 영양학과 신체활동 국제 저널의 연구에 따르면, 가공육을 정기적으로 먹는 사람들 사이에서 흡연이 더 흔하다고 한다. 게다가, 과일과 채소 섭취량도 더 낮다. BMC 의학저널의 연구는 또한 “가공육 소비와 사망률 사이에는, 특히 심혈관 질환과 또한 암에 기인해서, 중간 정도의 긍정적인 연관이 있다.”고 결론냈다. 실제로, 가공육을 섭취하는 것은 암을 비롯한 많은 만성 질환의 위험 증가와 관련이 있다. 암예방학술지의 연구는 쥐를 대상으로 한 오랜 연구를 수행한 후에 가공육을 먹는 것이 대장암의 위험을 증가시킨다는 것을 발견했다. 따라서, 사람들이 반드시 가공육의 섭취를 줄여야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >가공육은 생명을 위협하는 발암물질이라는 부적절한 평판을 가지고 있다. 이러한 근거 없는 믿음이 틀렸음을 밝히는 여러 연구가 있다. meatmythcrushers.com에 따르면, “14개의 주요 연구들을 모은, 가장 큰 연구들 중 하나는 붉은 가공육과 암 사이에는 아무런 연관이 없다는 것을 찾아냈다. 게다가, 가공육과 대장 암에 대한 종합적인 연구는 두가지의 연관성을 뒷받침할 증거가 불충분하다는 결론을 내렸다.” 또한, 가공육은 광범위한 범위를 포괄한다. 사이트는 “ 가공육은 최근 몇 년동안 확실히 오명을 썼었지만, 모든 고기는 먹기 전에 반드시 가공되어야 한다는 것을 기억하는 것이 중요하다.”고 설명했다. 가공육과 암을 연관짓는 대부분의 연구는 가공육을 먹는 사람들이 고혈압, 심장병, 그리고 다른 형태의 암에 걸릴 가능성이 더 높다는 것을 보여준다. 그러나, 가공육이 실제 원인이라는 것을 증명할 수는 없다. 따라서, 가공육을 완전히 피할 필요는 없다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is processed meat good or bad for your health?</li>
          <li>What are the dangers of eating processed meat?</li>
          <li>Do Koreans consume processed meat everyday?</li>
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

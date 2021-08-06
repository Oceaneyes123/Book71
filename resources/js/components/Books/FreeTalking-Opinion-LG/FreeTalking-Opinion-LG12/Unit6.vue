<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/kimchi-ready-eat-black-plate_1150-35690.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Fermented Foods Healthy?
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
      <td class = "lowertable" >Fermented foods are quite healthy. First of all, they improve digestive health. According to a study led by Marina Ritchie, a biology professor at Canada’s Dalhousie University, the probiotics in fermented foods can help restore the balance of beneficial bacteria in your gut. Furthermore, they may alleviate some digestive problems, such as irritable bowel syndrome (IBS). A six-weeklong study published in Alimentary Pharmacology & Therapeutics showed that consuming 125 g of fermented milk per day improved IBS symptoms. In addition, according to various studies, consuming fermented foods may help with lessening the severity of bloating, gas, constipation, and diarrhea. Next, fermented foods can boost your immune system. Because of their rich probiotic content, fermented foods can reduce the risk of catching a cold, and they can even help you recover faster from a cold. This is also partly due to the fact that many fermented foods naturally contain vitamin C, iron, and zinc. Thus, we should all eat more fermented foods.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Fermented foods are not good for your health. They can cause side effects in certain individuals. According to a study in the American Journal of HealthSystem Pharmacy, the high probiotic content in fermented foods can cause a temporary increase in gas and bloating. These symptoms are especially common after eating fermented foods that contain a lot of fiber, such as kimchi and sauerkraut. Moreover, many fermented foods are high in sodium because of their abundant salt content. For instance, although kimchi is promoted as a healthy side dish, a daily portion contains 1,232 mg of sodium. Because of kimchi, the average sodium intake for a Korean adult is an alarming 4,553 mg. According to the World Health Organization, the average adult should limit their daily sodium intake to 2,000 mg, and the ideal amount is no more than 1,500 mg. There’s also research that suggests probiotics can evolve in your gut and cause harm. As you can see, fermented foods are unhealthy.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>digestive</b> 소화의
        </p>
        <p>
          <b>alleviate</b> 완화하다
        </p>
        <p>
          <b>irritable bowel syndrome</b> 과민성 대장 증후군
        </p>
        <p>
          <b>constipation</b> 변비
        </p>
        <p>
          <b>diarrhea</b> 설사
        </p>
        <p>
          <b>recover</b> 회복하다
        </p>
        <p>
          <b>zinc</b> 아연
        </p>
        <p>
          <b>side effect</b> 부작용
        </p>
        <p>
          <b>sodium</b> 나트륨
        </p>
        <p>
          <b>abundant</b> 풍부한
        </p>
        <p>
          <b>intake</b> 섭취(량)
        </p>
        <p>
          <b>perk</b> 특전
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >발효된 음식은 매우 건강에 좋다. 먼저, 그것들은 소화 건강을 향상시킨다. 캐나다의 댈루이스 대학의 생물학 교수인 마리나 리치가 이끈 한 연구에 따르면, 발효된 음식의 유산균은 내장에 있는 유익한 균의 균형을 회복시키는 데 도움이 될 수 있다. 게다가, 그것들은 과민성 대장 증후군과 같은 일부 소화 장애를 완화시킬 수 있다. 소화 약리학과 치료 학술지에 실린 6주 동안 진행된 한 연구는 매일 125그램의 발효된 우유를 마시는 것이 IBS 증상을 개선시켰다는 것을 보여주었다. 게다가, 다양한 연구에 따르면, 발효된 음식을 먹는 것은 붓기, 가스, 변비 및 설사의 심한 정도를 줄이는 데 도움이 될 수 있다. 다음으로, 발효된 음식은 면역 체계를 향상시킬 수 있다. 풍부한 유산균 함량 때문에, 발효된 음식은 감기에 걸릴 위험을 줄일 수 있고, 그것들은 감기로부터 더 빠른 회복을 도울 수도 있다. 이것은 부분적으로 많은 발효 음식들이 자연스럽게 비타민 C, 철분 및 아연을 함유하고 있다는 사실 때문이다. 그러므로, 우리는 모두 더 많은 발효 음식을 먹어야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >발효된 음식은 건강에 좋지 않다. 어떤 개인에게는 그것은 부작용을 일으킨다. 미국 건강체계 약학 저널의 한 연구에 따르면, 발효된 음식에 있는 높은 유산균 함량은 가스와 붓기를 일시적으로 증가시킬 수 있다. 이 증상들은 김치와 독일식 김치와 같이 많은 섬유질을 함유하고 있는 발효된 음식을 먹고 난 후에 특히 흔하다. 더욱이, 많은 발효 음식들은 풍부한 소금 함량 때문에 나트륨이 높다. 예를 들어, 김치가 건강에 좋은 반찬으로 홍보되지만, 1일 섭취량은 1,232 mg의 나트륨을 포함하고 있다. 김치 때문에, 한 명의 한국인 성인의 평균 나트륨 섭취량은 놀랍게도 4,553 mg이다. 세계 보건 기구에 따르면, 평균 성인은 그들의 1일 나트륨 섭취량을 2,000 mg으로 제한해야 하고, 이상적인 양은 1,500 mg을 넘어서는 안 된다. 유산균이 내장에서 진화하여 해가 될 수도 있다는 것을 시사하는 연구도 있다. 보다시피, 발효 음식은 건강에 해롭다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think Koreans consume an excessive amount of fermented food?</li>
          <li>Is there any harm in eating fermented food?</li>
          <li>What happens if you eat too much fermented food?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/composition-with-plate-alarm-clock-measuring-tape-colored-background-diet-concept-weight-loss-plan-copy-space_127032-2211.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is Intermittent Fasting Healthy?
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
      <td class = "lowertable" >Intermittent fasting is incredibly good for your body. Not only does intermittent fasting help with weight loss, but it also improves overall health. There are several methods, but the most popular way involves restricting your daily eating period to eight hours. Doing this leads to a reduction in caloric intake and changes to hormone levels, resulting in weight loss. According to a 2014 study, people following this eating pattern lost up to 7 percent of their waist circumference. The same study also found that intermittent fasting can reduce insulin resistance, cholesterol, and inflammation. Several studies have also stated that intermittent fasting can increase the brain hormone BDNF (brain derived neurotrophic factor) and help grow new nerve cells. Some studies have even observed longer lifespans in rats that fasted. Interestingly, they lived up to 36-83 percent longer. In addition, intermittent fasting simplifies daily routines, as you don’t need to cook or eat out as often. It is easy to see why it’s so popular these days.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Intermittent fasting is not for everyone. In fact, it can be downright dangerous for certain individuals. According to healthline.com, “If you’re underweight or have a history of eating disorders, you should not fast without consulting with a health professional first.” Because intermittent fasting causes weight loss, those who are underweight should follow a diet that results in a healthy weight. As for people who have experienced eating disorders, fasting may bring back bad habits. The effectiveness of intermittent fasting among women has also been questioned. One study revealed that it worsened blood sugar control in women, and another study showed that female rats that fasted became emaciated, masculinized, and infertile. Moreover, “There are a number of anecdotal reports of women whose menstrual period stopped when they started doing intermittent fasting and went back to normal when they resumed their previous eating pattern,” according to healthline.com. Thus, it is clear that intermittent fasting is not meant for everybody. Calling it healthy is an overstatement.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>caloric</b> 칼로리의
        </p>
        <p>
          <b>intake</b> 섭취(량)
        </p>
        <p>
          <b>circumference</b> 둘레
        </p>
        <p>
          <b>brain-derived neurotrophic factor</b> 뇌유래신경영양인자
        </p>
        <p>
          <b>lifespan</b> 수명
        </p>
        <p>
          <b>simplify</b> 간소화[단순화]하다, 간단[평이]하게 하다
        </p>
        <p>
          <b>downright</b> (부정적이거나 불쾌한 것을 강조하여) 순전히[완전히]
        </p>
        <p>
          <b>emaciated</b> 쇠약한, 수척한
        </p>
        <p>
          <b>masculinized</b> 웅성화한
        </p>
        <p>
          <b>infertile</b> 불임의
        </p>
        <p>
          <b>anecdotal</b> 입증되지 않은, 일화적인
        </p>
        <p>
          <b>overstatement</b> 과장한 말
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >간헐적 단식은 여러분의 몸에 엄청나게 좋습니다. 간헐적 단식은 체중 감량에 도움이 될 뿐만 아니라 전반적인 건강도 개선시켜 줍니다. 몇 가지 방법이 있지만, 가장 인기 있는 방법은 하루 식사 시간을 8시간으로 제한하는 것입니다. 이렇게 하는 것은 칼로리 섭취를 줄이고 호르몬 수치를 변화시켜 체중을 감소시킵니다. 2014년 연구에 따르면, 이러한 식습관을 따르는 사람들은 허리 둘레가 7퍼센트까지 빠졌다고 합니다. 같은 연구는 또한 간헐적인 단식이 인슐린 저항성, 콜레스테롤, 그리고 염증을 감소시킬 수 있다는 것을 발견했습니다. 몇몇 연구들은 또한 간헐적인 단식이 뇌 호르몬 BDNF(뇌 유래 신경 영양 인자)를 증가시키고 새로운 신경 세포를 성장시키는데 도움을 줄 수 있다고 언급했습니다. 어떤 연구는 심지어 단식한 쥐의 수명이 더 길다는 것을 관찰하기도 했습니다. 흥미롭게도, 단식한 쥐들은 36-83% 더 오래 살았습니다. 게다가 간헐적인 단식을 하면 자주 요리하거나 외식을 할 필요가 없기 때문에 일상 생활을 단순화합니다. 요즘 간헐적 단식이 왜 이렇게 인기가 많은지 쉽게 알 수 있습니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >간헐적 단식은 모두를 위한 것은 아닙니다. 간헐적 단식은 사실 특정 개인에게 아주 위험할 수 있습니다. Healthline.com에 따르면, "만약 여러분이 저체중이거나 섭식 장애 이력이 있다면, 건강 전문가와 먼저 상의하지 않고 단식을 해서는 안 된다”고 한다. 간헐적 단식은 체중 감량을 유발하기 때문에 저체중인 사람들은 건강한 체중을 얻는 식이요법을 따라야 합니다. 섭식 장애를 경험한 사람들의 경우, 금식은 나쁜 습관을 되살릴 수 있습니다. 여성의 간헐적 단식의 효과도 의문시되어 왔습니다. 한 연구는 간헐적 단식으로 여성의 혈당 조절이 악화되었다고 밝혔고, 다른 연구는 금식한 암컷 쥐들이 쇠약해지고, 남성화되고, 불임이 된 것으로 나타났습니다. 또한 healthline.com에 따르면, "간헐적 단식을 시작했을 때 월경이 중단되고 이전의 식습관을 다시 시작했을 때 정상으로 돌아갔던 여성들에 대한 많은 일화가 있습니다. 그러므로 간헐적인 단식이 모두를 위한 것이 아니라는 것은 분명합니다. 간헐적 단식이 건강하다고 하는 것은 과장된 표현입니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is intermittent fasting really effective?</li>
          <li>How safe is intermittent fasting?</li>
          <li>What are the side effects of intermittent fasting?</li>
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

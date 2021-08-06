<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/man-holding-barbell-floor-gym_1268-17044.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Does Lifting Weights Stunt Growth?
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
      <td class = "lowertable" >Bodybuilding and other exercises related to muscle strength and growth can affect an adolescent’s height. These exercises require extra caution, as they can injure growth plates. According to the Australian Strength and Conditioning Association, children who want to lift weights should “have the maturity to follow clear instructions and an appreciation of the dangers present when training.” Unfortunately, most teenagers and young children are not wise enough to follow precautions. It is common knowledge that young people lack good decision-making skills and are prone to exhibiting rebellious behavior. Even with proper form, there is no guarantee that the child will not sustain any injuries. Constant supervision is also difficult to maintain. Instead, teenagers should engage in cardiovascular exercises. Sports such as basketball and soccer are great forms of exercise, as they keep the heart pumping and the body in constant motion. In order to reach your potential height, be patient and wait until you have fully grown.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Strength training is not a factor when it comes to stunted growth. It is simply a myth, and there is no scientific evidence or research that supports this belief. According to a study in Translational Pediatrics, a scientific journal, resistance training programs have numerous benefits. Healthline.com states that these benefits include “increasing strength and bone strength index, decreasing fracture risk and rates of sports-related injury, and growing self-esteem and interest in fitness.” So, where does this misconception come from? According to Rob Raponi, a naturopathic doctor and certified sports nutritionist, many people associate strength training with injuries to growth plates. In immature bones, these injuries can stunt growth. It is imperative that people under the age of 18 demonstrate proper form when lifting weights. A lack of knowledge is the main reason why teenagers experience stunted growth. Health experts say that proper supervision is key, so make sure you receive guidance from a personal trainer unless you want to hurt yourself.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>adolescent</b> 청소년
        </p>
        <p>
          <b>maturity</b> 성숙함, 원숙함 
        </p>
        <p>
          <b>appreciation</b> 올바른 인식
        </p>
        <p>
          <b>precaution</b> 예방책, 예방 조치[수단]
        </p>
        <p>
          <b>prone</b> (좋지 않은 일을) 하기[당하기] 쉬운
        </p>
        <p>
          <b>rebellious</b> (규칙·일반 통념 등에 대해) 반항적인
        </p>
        <p>
          <b>sustain</b> (피해 등을) 입다[당하다]
        </p>
        <p>
          <b>cardiovascular</b> 심혈관의
        </p>
        <p>
          <b>resistance</b> 저항력
        </p>
        <p>
          <b>fracture</b> 골절
        </p>
        <p>
          <b>naturopathic</b> 자연 요법(사)의
        </p>
        <p>
          <b>imperative</b> 반드시 해야 하는, 긴요한
        </p>
       </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >보디빌딩 및 근육의 힘과 성장과 관련된 다른 운동들은 청소년들의 키에 영향을 줄 수 있습니다. 이러한 운동들은 성장판을 상하게 할 수 있기 때문에 각별한 주의가 필요합니다. ASCA에 따르면 역기를 들어 올리고자 하는 아이들은 “명확한 지시를 따르고 훈련 할 때 나타나는 위험을 인식 할 수 있는 성숙함”을 가져야 합니다. 안타깝게도 대부분의 10대들과 어린 아이들은 주의지침을 따를 만큼 현명하지 못합니다. 어린 아이들이 의사결정 능력이 부족하고 반항적인 행동을 보이기 쉽다는 것은 모두가 알고 있습니다. 적절한 방식이라고 하더라도 아이가 부상을 당하지 않는다는 보장은 없습니다. 지속적으로 감독하기도 어렵습니다. 10대들은 대신 유산소 운동을 해야 합니다. 농구, 축구와 같은 스포츠는 심장을 뛰게 하고 몸을 지속적으로 움직이게 하기 때문에 훌륭한 운동 방식입니다. 최대한 자랄 수 있는 키에 이르도록 인내심을 가지고 완전히 자랄때까지 기다려야 합니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >체력단련이 성장 둔화의 요인은 아닙니다. 근거가 없는 말일 뿐이며, 이를 뒷받침하는 과학적 증거나 연구는 없습니다. 과학 저널인 Translational Pediatrics의 연구에 따르면 저항력 훈련 프로그램은 많은 이점을 가지고 있다고 합니다. Healthline.com은 이러한 장점들에는 "힘과 뼈의 강도 지수 증가, 골절 위험과 스포츠 관련 부상 비율 감소, 그리고 건강에 대한 자신감과 관심 증가"가 있다고 말합니다. 그렇다면 이러한 오해는 어디에서 오는 것일까요? 자연병리학 의사이자 공인 스포츠 영양사인 Rob Raponi에 따르면, 많은 사람들이 근력 운동과 성장판의 부상을 연관시킨다고 합니다. 이러한 부상은 미성숙한 뼈의 성장을 방해할 수 있습니다. 필수적으로 18세 미만의 사람들은 역기를 들 때 적절한 방식으로 들어야 합니다. 10대들의 성장을 방해하는 주요 원인은 지식의 부족입니다. 건강 전문가들은 적절한 감독이 핵심이라고 말하므로, 다치고 싶은게 아닌 이상 개인 트레이너로부터 지도를 받아야 합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are the benefits of lifting weights?</li>
          <li>Is it possible to lose weight by lifting weights?</li>
          <li>Does weight lifting decrease or hinder height and growth?</li>
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

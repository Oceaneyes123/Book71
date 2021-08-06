<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/hand-button-man-multimedia-mail_1150-1730.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is Social Networking Good for Society?
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
      <td class = "lowertable" >Social Networking websites often engage and captivate young minds. This Can be a beneficial tool for teaching. In the United States, a 2007 study found that 59 percent of students with access to the Internet use social networking sites to discuss educational topics, and 50 percent use the sites to talk about school assignments. In addition, young people can learn how to socialize on social networking sites. “It’s almost like social networks are training wheels for life in a lot of ways,” said Dr. Larry Rosen, a psychologist and technology researcher. “It teaches you to express empathy and see how people respond. It teaches you to also just develop your sense of self of who you are. It’s a place where you can grow and develop.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >According to studies, middle school, high school, and college students who look at Facebook at least one time during a 15-minute study break are more likely to receive lower grades. In addition, many young Facebook and Twitter users show more tendencies to be narcissistic, and the overuse of media and technology can negatively affect the psychological health of children and teens. New research has found that heavy users of social media are more likely to experience anxiety and depression.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>social network</b> 소셜네트워크, 사회연결망[관계망]
        </p>
        <p>
          <b>socialize</b> (사람들과) 사귀다[어울리다/교제하다]
        </p>
        <p>
          <b>tendency</b> 성향, 기질; 경향
        </p>
        <p>
          <b>narcissistic</b> 자기 도취증에 빠진
        </p>
      </div>
       
      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >소셜 네트워킹 웹사이트는 종종 젊은(어린) 사람들의 마음을 사로잡는다. 이것은 교육의 유익한 도구가 될 수 있다. 미국의 2007년도의 조사는 인터넷 접근이 가능한 학생들의 59%가 교육적인 주제를 논의하기 위해 소셜 네트워킹 사이트를 사용하고, 50%가 학교 과제를 이야기 하기 위해 그 사이트를 사용한다는 것을 발견 했다. 또한, 어린 사람들은 소셜 네트워킹 사이트에서 사람들과 어울리는 법을 배울 수 있다. “소셜 네트워크는 여러 방면으로 인생을 위한 보조 바퀴 같다”고 심리학자이자 기술 연구자인 Larry Rosen 박사는 말했다. 그것은 당신에게 공감을 표현하는 법과 사람들이 어떻게 응답하는 지를 가르친다. 그것은 또한 여러분 자신에 대한 자아감을 개발하라고 가르친다. 그것은 당신이 성장하고 개발 할 수 있는 공간이다.”</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >조사에 따르면, 학습 중 15분의 쉬는 시간 동안 적어도 한 번 페이스북을 들여다 보는 중,고등학생과 대학생들은 더 낮은 성적을 얻게 되기 쉽다고 한다. 또한, 많은 나이 어린 페이스북과 트위터 사용자들은 자기 도취증에 빠지기 쉽고 미디어와 기술의 지나친 사용은 아이들과 청소년들의 심리적 건강에 좋지 않은 영향을 미칠 수 있다. 새로운 연구는 소셜 미디어를 과하게 사용하는 사람들은 근심과 우울증을 겪기 쉽다는 것을 발견했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you have a social media account? If yes, how often do you use it?</li>
          <li>Is using any social networking site helpful?</li>
          <li>Do you think students should use social networking sites?</li>
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

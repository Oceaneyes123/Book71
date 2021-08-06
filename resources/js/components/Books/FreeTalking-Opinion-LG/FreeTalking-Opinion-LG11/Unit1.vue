<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/front-view-woman-reading-something-her-students_23-2148633356.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Computers Replace Teachers?
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
      <td class = "lowertable" >Have you ever had a computer that hasn’t crashed? Have you ever had a computer that has understood your emotional problems? To have a computer teach the next generation of children is a mistake. When you look at how addicted children are to their smartphones, it paints a clearer picture: our children may learn the essentials of knowledge, but how will they grow in wisdom and interpersonal ability? A child taught by a computer will emulate a computer ? cold, unfeeling, and confused. Not to mention that any computer malfunction would derail an entire school day. In addition, any replacement of people in teaching jobs creates a huge loss in the economy. Where will all those with liberal arts and teaching degrees, a growing supply of people, find employment? Therefore, children should be taught by humans, who can understand, teach, and motivate them to become better people.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >What have humans done for civilization that computers haven’t done far better? In World War II cannon targets were calculated by humans and sometimes the errors led to accidents. Today, computers calculate our weapons and effectively destroy them without accident. At times a website teaches far better than any person ever could. Every single person has probably used Wikipedia at least once. While humans can understand emotion they are also just as capable of being wildly emotional. When teachers teach, it can contain false information or personal opinions, but computers do not make errors. Even then, the parents of children should at least be somewhat responsible for their emotional growth. With parents providing emotions and computers providing education, children of the future will receive the best of both worlds</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>malfunction</b> (장기, 기계 등이) 제대로 작동하지 않다
        </p>
        <p>
          <b>crash</b> (컴퓨터가) 갑자기 서버리다
        </p>
        <p>
          <b>impatient</b> 성격이 급한
        </p>
        <p>
          <b>addicted</b> 중독된
        </p>
        <p>
          <b>essentials</b> 본질적 요소, 요점
        </p>
        <p>
          <b>interpersonal</b> 대인관계에 관련된
        </p>
        <p>
          <b>not to mention</b> ~은 말할 것도 없고
        </p>
        <p>
          <b>liberal arts</b> 교양과목
        </p>
        <p>
          <b>motivate</b> 동기를 부여하다
        </p>
        <p>
          <b>calculate</b> 계산하다, 산출하다
        </p>
        <p>
          <b>at least</b> 최소한
        </p>
        <p>
          <b>shapeless</b> 모양이 없는
        </p>
        <p>
          <b>emotion</b> 감정
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >고장 난 적이 없는 컴퓨터를 써 본 적이 있나요? 여러분의 감정적인 문제를 이해하는 컴퓨터를 써 보았나요? 컴퓨터가 다음 세대의 어린이를 가르치는 것은 실수이다. 여러분이 그들의 스마트폰에 어린이들이 얼마나 중독적인가를 보면, 그것은 더 분명한 그림이 그려진다: 우리의 어린이들은 지식의 본질을 배울 수 있지만, 지혜와 의사소통 능력은 어떻게 함양할 것인가? 컴퓨터를 통해서 배운 어린이는 차갑고, 감정이 없으며, 그리고 혼란스러운 컴퓨터를 모방할 것이다. 어떠한 컴퓨터의 오작동이 전 학교 수업을 탈선 시킬 것은 말할 것도 없다. 게다가, 가르치는 직업에서의 어떠한 사람의 교체는 경제에 큰 손실을 야기시킨다. 교양 과목과 교육 학위를 가진 사람들이 점점 더 많아지고 있는데 이들은 어디서 일자리를 찾을 것인가? 그러므로, 어린이들은 이해할 수 있고, 가르칠 수 있고, 그리고 그들을 더 나은 사람이 될 수 있도록 동기부여할 수 있는 사람에 의해 가르침을 받아야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >문명을 위해 인간이 한 일들 중 컴퓨터가 훨씬 더 잘할 수 없었던 것들이 무엇이 있었는가? 제 2차 세계대전에서 대포의 목표물은 인간에 의해 계산되었고 때로 실수는 사고를 낳기도 하였다. 오늘날, 컴퓨터는 사고 없이 우리의 무기를 계산하고 효과적으로 파괴한다. 가끔은 웹사이트의 교사들이 누군가가 할 수 있는 정도보다 훨씬 더 뛰어나다. 모든 사람은 아마 적어도 한 번쯤은 위키피디아를 사용했을 것이다. 인간이 감정을 이해할 수 있지만, 그들은 또한 과도하게 감정적이 되기도 한다. 교사들이 가르칠 때, 그것은 거짓된 정보나 개인적인 의견을 포함할 수 있지만 컴퓨터는 실수를 하지 않는다. 그렇다고 하더라도, 아이들의 부모들은 적어도 어느 정도 그들의 감정적인 성장에 책임을 가져야 한다. 부모들은 감정을, 컴퓨터들은 교육을 제공해줌으로써, 미래의 아이들은 두 개의 세상에서 가장 최고의 것을 받을 수 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How can a computer be more beneficial to learning than a teacher?</li>
          <li>What are the disadvantages of learning from a computer rather than a teacher?</li>
          <li>As a student, do you prefer to learn from a teacher or from a computer?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/close-up-woman-working-digital-monitors_23-2148910245.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Invest In Artificial Intelligence?
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
      <td class = "lowertable" >Artificial intelligence is the future of this world. When we consider the technology of today, most people do not realize how often we use artificial intelligence technology. From Iphone’s Siri to Google’s search prediction algorithm, artificial intelligence is all around us. We have thoroughly embraced it. People are purchasing items like the Alexa in droves. Artificial intelligence is coming to computers, televisions, even refrigerators. While the big supercomputers like AlphaGo and Deep Blue gather the attention and headlines, the truth is that artificial intelligence is all around us. The electronics that we love using and the web pages that we visit every day have some form of artificial intelligence. This is why we should continue to invest in it. Everyone is afraid of a terminator type of future, but in truth artificial intelligence simply serves to improve the quality of life for humans. Why should we stop improving everyone’s quality of life? </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Artificial intelligence will be the end of this world. For years, scientists and inventors have warned the world about artificial intelligence. Tech billionaire Elon Musk warned students and professors at an MIT conference about artificial intelligence, saying that without any oversight and checks and balances the creation of artificial intelligence is like “summoning the devil.” He has argued that AI is a fundamental risk to the existence of civilization. Even worse, we are beginning to make ‘smart’ homes. That essentially means that we are giving control of our locks, thermostats, and appliances to an artificial intelligence. While they are invented to be friendly and helpful, what if the opposite happens? Even worse, what if the same happens and humanity becomes lazier and more inept. While artificial intelligence seems like we are augmenting our intelligence, it basically means that we are replacing it with convenience.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>artificial intelligence</b> 인공지능
        </p>
        <p>
          <b>thoroughly</b> 완전히
        </p>
        <p>
          <b>gather</b> 모으다
        </p>
        <p>
          <b>warn</b> 경고하다
        </p>
        <p>
          <b>billionaire</b> 밀억만장자, 갑부
        </p>
        <p>
          <b>oversight</b> 관리, 감독
        </p>
        <p>
          <b>civilization</b> 문명
        </p>
        <p>
          <b>thermostat</b> 온도 조절 장치
        </p>
        <p>
          <b>inept</b> 솜씨 없는, 서투른
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >인공 지능은 이 세상의 미래이다. 우리가 오늘날의 인공지능을 고려할 때, 우리 대부분은 우리가 얼마나 자주 인공 지능 기술을 사용하는지 인지하지 못한다. 아이폰의 시리에서 구글의 탐색 예상 알고리즘까지, 인공 지능은 항상 우리 주변에 있다. 우리는 그것을 완전히 받아들였다. 사람들은 알렉사와 같은 물건들을 대량으로 구입한다. 인공 지능은 컴퓨터, 텔레비전, 심지어 냉장고에까지 왔다. 알파고와 딥 블루와 같은 슈퍼 컴퓨터가 관심과 헤드라인을 모으는 반면, 사실 인공 지능은 우리 주변에 항상 있다. 우리가 사랑하는 전자기기와 우리가 매일 방문하는 웹 페이지도 일종의 인공 지능이다. 이것이 우리가 그것에 투자를 계속 해야만 하는 이유이다. 우리 모두는 미래의 종식을 두려워하지만, 사실 인공 지능은 인류를 위해 인간의 삶의 질을 단순히 개선시킨다. 우리가 모두의 삶의 질을 높이는 것을 왜 멈추어야만 하는가?</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >인공지능은 이 세계의 끝일 것이다. 수 년 동안 과학자들과 발명가들은 인공 지능에 대해 세계에 경고를 주어왔다. 기술 억만장자 엘론 머스크는 인공지능에 대해 MIT의 한 컨퍼런스에서 학생들과 교수들에게 경고하며 관리 그리고 감시와 견제 없이 인공 지능의 개발은 “악마를 소환하는 것”과 같다고 말했다. 그는 인공지능이 문명의 존재에 근본적인 위험이라고 주장해왔다. 설상가상으로 우리는 “스마트” 집을 만들기 시작했다. 이것은 본질적으로 우리가 우리의 자물쇠, 온도 조절 장치 그리고 가전 기기에 대한 통제를 인공지능에 주고 있는 것을 의미한다. 그들이 친근하고 도움이 되고 개발되었지만 그 반대가 발생하면 어떨까? 설상 가상으로 만약 같은 일이 일어나고 인류는 더 게을러지고 서툴게 되면 어떻게 될까? 인공지능이 우리의 지능을 증가시키는 것처럼 보이는 반면 그것은 기본적으로 우리가 그것을 편안함으로 대체하고 있음을 의미한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are the advantages and disadvantages of artificial intelligence?</li>
          <li>Why should companies or businesses be investing in artificial intelligence?</li>
          <li>Can artificial intelligence replace some human race?</li>
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

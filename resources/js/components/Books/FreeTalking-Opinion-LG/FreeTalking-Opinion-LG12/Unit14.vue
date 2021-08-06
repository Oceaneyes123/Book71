
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/close-up-graduate-student-holding-cap_23-2148950587.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is Your College Major Important?</h1>
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
      <td class = "lowertable" >Although it may be overwhelming for prospective college students to choose what to major in, the end result is definitely worthwhile. Not only is it important to find a job that pays well, it is also crucial to find one that is available. There are many job fields that are oversaturated. People often turn a blind eye to in-demand jobs that they view as undesirable or daunting. According to Sonet Van Zyl, an associate professor of viticulture, “There are more job opportunities than there are people available.” Tom Cortina, an assistant dean, said this is the case as well. He explained, “We, meaning academia, are not actually graduating enough computer scientists to fill all of the positions out there that are computing related. That’s how in demand computer scientists are.” Furthermore, according to USA Today, the unemployment rate for actors in the U.S. is 24.2 percent, guaranteeing the lowest job security. Is a degree in theater beneficial? Thus, it is imperative that you select a major after careful consideration.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Despite what many of us are led to believe, your college major isn’t important. Your college degree is simply a prerequisite for the competitive workforce. Many jobs require at least a bachelor’s degree, but it does not matter what field it is in. According to research by the Federal Reserve Bank of New York, 62 percent of recent U.S. college graduates have jobs that require a degree. However, only 27 percent of college graduates are working in a job that actually relates to their major. For instance, many English teachers in Korea who are from overseas do not possess degrees that are even remotely related to linguistics or pedagogy. TESOL certification, however, is mandatory for some English teaching positions. In addition, according to Forbes magazine, your major does not determine your salary. It explained, “History majors who pursued careers in business ended up earning as much as business majors.” Thus, it is perfectly acceptable to major in something you are passionate about.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>prospective</b> 장래의, 유망한
        </p>
        <p>
          <b>worthwhile</b> 가치[보람] 있는
        </p>
        <p>
          <b>oversaturated</b> 과포화된
        </p>
        <p>
          <b>turn a blind eye to</b> ~을 못 본 체하다
        </p>
        <p>
          <b>daunting</b> 벅찬, 주눅이 들게 하는
        </p>
        <p>
          <b>viticulture</b> 포도재배학
        </p>
        <p>
          <b>academia</b> 학계
        </p>
        <p>
          <b>imperative</b> 반드시 해야 하는
        </p>
        <p>
          <b>prerequisite</b> (무엇이 있기 위해서는 꼭 필요한) 전제 조건
        </p>
        <p>
          <b>remotely</b> 아주 약간
        </p>
        <p>
          <b>linguistics</b> 언어학
        </p>
        <p>
          <b>pedagogy</b> 교육학
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >대학 입학을 앞둔 학생들이 전공 선택을 앞두고 있다면 스트레스 받을지도 모르겠지만, 결국 그들이 선택한 것은 분명 그럴 만한 가치가 있는 일이지요. 연봉이 높은 직업을 얻는 것도 중요하지만, 그러려면 그 가능성을 높여줄 전공을 잘 고르는 것이 우선되어야 할 것입니다. 경쟁이 극심한 직업들이 현실에는 부지기수이기 때문입니다. 우리는 대개 꺼리거나 고된 일에는 외면하는 경향이 강합니다. 소넷 반 지엘(Sonet Van Zyl) 포도 재배 부교수에 의하면, “이 분야에서 일을 하는 공급자의 수보다 일자리 기회가 더 많이 있다”라고 한다. 이어서 보조 학장인 톰 코르티나(Tom Cortina)가 이를 뒷받침하는 예시를 들었습니다. 그는 “학계적으로 보자면, 우리는 실제로 컴퓨터와 관련된 모든 직업을 가질 만큼 충분한 컴퓨터 과학자를 길러내지 못하고 있다. 그만큼 우리는 컴퓨터 과학자를 찾는 데 항상 목이 말라 있다.”라고 말했다. 또한 USA투데이의 보도에 따르면, 미국 내에서 배우들의 실업률은 24.4%로 일자리 안정성이 가장 낮은 것으로 드러났다. 이러한 상황에서 우리는 과연 연극, 연기 관련 전공을 택해야 하는 걸까요? 그러므로 전공 선택에는 보다 신중해야 하겠습니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >보통 전공이 중요하다는 믿음이 많지만, 그게 꼭 사실은 아니라고 생각합니다. 대학 학위는 단지 해당 인력의 경쟁력을 평가하는 조건 중 하나일 뿐입니다. 대다수의 직업들이 최소 학사급의 학위를 요구하고는 있지만, 어떤 걸 전공했는지는 크게 상관이 없다고 생각합니다. 뉴욕 연방준비은행의 연구로, 최근 미국 대학 졸업생의 62%가 학위를 필수로 요구하는 직업군에 종사하는 것으로 알려졌습니다. 그러나, 이 중 단 27%의 졸업생만이 실제로 자신의 전공과 관련된 직장에서 일하고 있다고 합니다. 예를 들어, 해외에서 온 한국의 많은 영어 교사들은 언어학이나 교육학과는 전혀 관련이 없는 학위를 소유하고 있기도 합니다. 물론, 몇몇 영어 강사직에 지원하는 이들이라면 TESOL 자격증을 필수로 취득해야 하겠지만요. 또한 포브스 잡지에 따르면 전공은 급여와 관계가 없다고 합니다. “사업 경력을 쌓은 역사학 전공자는 결국 경영학 전공자만큼의 수입을 올렸다.”고 한다. 따라서, 그저 당신의 열정에 맞는 전공을 선택하면 된다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What was your major in college? Was that your choice?</li>
          <li>Does your college major matter when it comes to getting a job?</li>
          <li>What major would you prefer to pursue if you could study again?</li>
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

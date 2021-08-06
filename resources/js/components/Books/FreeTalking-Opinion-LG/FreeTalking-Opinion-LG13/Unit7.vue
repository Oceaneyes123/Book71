<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/name-writing-with-black-letters-wooden-dices-with-old-book-around-high-quality-photo_114579-52994.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Importance of Names
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
      <td class = "lowertable" >The importance of names should not be overlooked. Names can affect perception, ultimately acting in one’s favor or hindering them. Names that sound distinctively African-American, for instance, can play a role in hiring decisions. According to Katherine A. DeCelles, a professor at Harvard Business School, “Discrimination still exists in the workplace.” She co-authored an article regarding multiple studies that looked at the influence of names in the hiring process. According to Harvard, “Employer callbacks for resumes that were whitened fared much better in the application pile than those that included ethnic information, even though the qualifications listed were identical. 25 percent of black candidates received callbacks from their whitened resumes, while only 10 percent got calls when they left ethnic details intact.” Even companies that claim they are nondiscriminatory are guilty of judging applicants based on their names. Many American jobseekers of Asian and Hispanic descent resort to changing their names as well. Unfortunately, names matter more than you might think.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Names are simply names – nothing more, nothing less. They can’t hold you back from overcoming adversity. One woman named Marijuana Pepsi Vandyck, who is African-American, is living proof that names are not important. She has a Ph.D. and “her full-time job involves helping underprivileged students. She works as the director of a program at Beloit College that serves students who come from low-income backgrounds, are first-generation college students, or have disabilities. On the side, she works as a life coach and sells real estate,” according to The Washington Post. Moreover, according to writer Lauren Martin, “In Freakonomics, there was a chapter about names debating this exact question. Does your name have an effect on your success? After an in-depth analysis on the socioeconomic, political, and race issues of naming, they found that there is no evidence that your name determines your success.” According to author Sarah J. Maas, “Names are not important. It’s what lies inside of you that matters.”</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>perception</b> 인식(하여 갖게 된 생각)
        </p>
        <p>
          <b>distinctively</b> 특징적으로
        </p>
        <p>
          <b>fare</b> (특정 상황에서) 잘, 잘못, 더 잘하다 등
        </p>
        <p>
          <b>nondiscriminatory</b> 차별 대우가 없는
        </p>
        <p>
          <b>descent</b> 혈통
        </p>
        <p>
          <b>resort</b> 의지하다, (보통 달갑지 않은 수단에) 호소하다
        </p>
        <p>
          <b>adversity</b> 역경
        </p>
        <p>
          <b>underprivileged</b> (사회·경제적으로) 혜택을 못 받는
        </p>
        <p>
          <b>real estate</b> 부동산
        </p>
        <p>
          <b>in-depth</b> 철저하고 상세한, 면밀한
        </p>
        <p>
          <b>socioeconomic</b> 사회경제적
        </p>
        <p>
          <b>determine</b> (무엇의 방식·유형을) 결정하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >이름의 중요성을 간과해서는 안 됩니다. 이름은 인식에 영향을 미칠 수 있고, 궁극적으로 자신에게 유리하게 작용하거나 방해가 될 수 있습니다.. 예를 들어, 뚜렷하게 아프리카계 미국인으로 들리는 이름들은 채용 결정에 있어 중요한 역할을 할 수 있습니다. 하버드 경영대학원의 캐서린 A. 데셀 교수에 따르면 "직장에는 여전히 차별이 존재한다"고 합니다. 캐서린은 채용 과정에서 이름이 미치는 영향을 조사한 여러 연구에 대한 기사를 공동 집필했습니다. 하버드에 따르면, "나열된 자격이 동일하더라도, 인종 정보를 적지 않은 이력서에 고용주가 연락하는 경우가 인종 정보를 기재한 이력서의 경우보다 훨씬 더 많습니다. 인종 정보를 적지 않은 이력서를 내고 연락을 받은 흑인 후보는 25%인 반면, 인종 세부 사항을 그대로 적었을 때 연락을 받은 흑인은 10%에 불과했습니다." 심지어 비차별적이라고 주장하는 기업들도 지원자의 이름을 보고 판단합니다. 많은 아시아계와 히스패닉계 미국인 구직자들은 이름을 바꾸는 것에 매달리고 있습니다. 안타깝게도 이름은 여러분이 생각하는 것보다 더 중요합니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >이름은 단순히 이름일 뿐 그 이상도 이하도 아닙니다. 이름은 여러분이 역경을 극복하는 것을 막을 수 없습니다. 아프리카계 미국인 마리화나 펩시 밴디크라는 한 여성은 이름이 중요하지 않다는 살아있는 증거입니다. 그녀는 박사 학위를 가지고 있고, "그녀는 주로 소외된 학생들을 돕고 있습니다. 그녀는 저소득층 출신이거나, 이민 2세대 대학생이거나, 장애가 있는 학생들을 위한 벨로이트 칼리지의 프로그램 디렉터로 일하고 있습니다. 부업으로 그녀는 라이프 코치로 일하고, 부동산업을 한다"고 워싱턴 포스트가 전했습니다. 게다가 작가 로렌 마틴에 따르면, "Freakonomics에서 정확히 이 질문에 대한 토론의 장이 있었다고 합니다. 당신의 이름이 당신의 성공에 영향을 주나요? 이름의 사회경제적, 정치적, 인종적 문제를 심도 있게 분석한 결과, 이름이 성공을 좌우한다는 증거가 없다는 사실을 발견했습니다. 작가 사라 J 마스에 따르면, "이름은 중요하지 않습니다. 여러분 안에 있는 것이 중요하다"고 합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Why are names important?</li>
          <li>Do you like your name?</li>
          <li>Do you ever wish to change your name? Why or why not?</li>
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

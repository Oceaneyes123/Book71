
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/businessman-drawing-keys-success_1134-645.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Academics and Success in Life
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
      <td class = "lowertable" >Whether one is proposing marriage, applying for a job or looking for a new business partner, the first thing people ask is, “What do you do?” In other words they judge you by your academic qualifications. No biodata resume or curriculum vitae is acceptable without the inclusion of education qualifications. Therefore it is an unannounced rule in both the corporate world and the social world that a man’s acquisition of academic qualification is a giant leap towards opportunities in every aspect of life.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Success never depends upon grades. If success and opportunities were measured by grades then the corporate world and potential marriage partner would not ask for bio data in resumes, where other qualifications are also mentioned. Nor would they interview new prospects in order to find out what they are likeas people, rather they would give a blind appointment to the people with the best paper qualifications. So qualifications alone is never enough, success depends upon physical characteristics, personality, and a willingness to work hard.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>qualification</b> 자격
        </p>
        <p>
          <b>acquisition</b> 획득
        </p>
        <p>
          <b>aspect</b> 측면
        </p>
        <p>
          <b>potential</b> (…이 될) 가능성이 있는, 잠재적인
        </p>
        <p>
          <b>prospect</b> 예기[예상]하여
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >결혼을 하려고 프러포즈하고, 취업 원서를 내고, 새로운 파트너를 구할 때 사람들은 먼저 뭘 하는지 질문한다. 다시 말해 성적 증명서로 그들을 판단한다. 학업 성적표 없이 생체 이력서와 이력서가 받아들여지지 않는다. 그러므로 성적 증명서의 획득은 삶의 모든 부분의 기회를 잡기 위한 큰 도약이 된다는 것은 회사와 사회의 숨겨진 규칙이다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >성공은 점수에 달려있지 않다. 성공과 기회가 점수로 매겨질 수 있다면 회사나 잠재적인 결혼 상대자는 생체 정보 이력서를 요구하지 않을 것이고 다른 자격증들을 언급할 것이다. 어떤 사람인지 알기 위해 새로운 관점으로 인터뷰하지 않고 차라리 서류 증명서로 만남을 가질 것이다. 성공은 증명서 만으로는 충분치 않고 신체적 특징, 성격, 일을 열심히 하려는 마음가짐에 달려있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is being good in academics affects someone’s chance of succeeding in life? Why or why not?</li>
          <li>If you’re a CEO of a company, would you hire someone with grades that are average or below average? Why or why not?</li>
          <li>How would you describe a person who is successful?</li>
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

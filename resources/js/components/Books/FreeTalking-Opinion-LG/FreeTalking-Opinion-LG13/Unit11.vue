<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/male-hand-answering-questionary-form-with-pen_1262-2288.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Standardized Tests Should Be Banned
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
      <td class = "lowertable" >Even though standardized tests are really common and most students are used to them, they have more drawbacks than benefits. These tests cause too much stress for students, don’t always accurately measure performance, and there are alternatives. Some critics of standardized tests believe they can be psychologically damaging. The stress can force students to cram day and night, not sleeping, eating, or even taking necessary bathroom breaks. This stress can lead to numerous negative consequences for students’ mental, physical, and emotional health. In extreme cases, they can even cause students to attempt suicide. Additionally, many people have test anxiety or choke under the pressure. In these cases, even if a student knows the material, their score will not reflect their true ability. This can lead to a poor assessment and excellent students being denied further educational opportunities such as university admission. This is a waste of potential. Lastly, we don’t need these tests to evaluate students. There are many alternative ways to determine how much a student has learned. One way is to simply use their grades from school. Others could be interviews, more hands-on approaches, or even essays that aren’t timed. These would all allow students that are poor test takers to demonstrate their ability, too.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Standardized tests have been part of education for hundreds of years. There are good reasons that we use them and we shouldn’t change that now. First, these tests make sure that students are evaluated equally. Everyone gets the same questions and is required to know the same material. This way some students will not have an advantage for going to an easy school or having an easy teacher. Second, standardized tests ensure students can’t cheat. They are monitored extremely closely and any sort of irregularity will lead to disqualification. No one should be allowed to get ahead by doing something so immoral. Third and final, the pressure of the test proves that students know when they need it. For example, if a medical student can’t pass an important test in a high pressure situation, most people would probably not want them to be their surgeon. These tests have been around for centuries and they are just as important today.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
         
        <p>
          <b>drawback</b> 문제점
        </p>
        <p>
          <b>alternative</b> 대안
        </p>
        <p>
          <b>extreme</b> 극도의
        </p>
        <p>
          <b>case</b> 경우
        </p>
        <p>
          <b>hands-on</b> 직접 해 보는
        </p>
        <p>
          <b>demonstrate</b> 보여주다[발휘하다]
        </p>
        <p>
          <b>immoral</b> 비도덕적인, 부도덕한
        </p>
        <p>
          <b>surgeon</b> 외과 전문의
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >표준화된 시험은 정말 흔하고 대부분의 학생들이 이에 익숙하지만, 표준화된 시험들은 장점보다 단점이 더 많습니다. 표준화된 시험은 학생들에게 너무 많은 스트레스를 주고, 항상 정확하게 성적을 측정하지는 않습니다. 그리고 대안이 있습니다. 표준화된 시험에 대한 일부 비평가들은 시험이 심리적으로 해로울 수 있다고 생각합니다. 스트레스는 학생들에게 밤을 새워가며 벼락치기를 하거나, 잠을 자거나, 밥을 먹거나, 심지어 필요한 짧은 휴식도 취하지 못하도록 강요할 수 있습니다. 이러한 스트레스는 학생들의 정신적, 육체적, 그리고 정서적 건강에 많은 부정적인 결과를 초래할 수 있습니다. 극단적인 경우, 심지어 시험 때문에 학생들이 자살 시도를 할수도 있습니다. 게다가 많은 사람들이 시험 공포증을 갖거나, 압박감으로 질식할 수 있습니다. 이러한 경우, 학생들이 시험 주제에 대해 안다고 해도, 학생들의 점수는 진짜 실력을 반영하지 못할 것입니다. 이는 형편없는 평가와 우수한 학생들이 대학 입학같은 추가적인 교육 기회로부터 받지 못하는 상황으로 이어질 수 있습니다. 이는 잠재력을 낭비하는 것입니다. 마지막으로, 학생들을 평가하기 위해 이러한 시험이 필요하지 않습니다. 학생이 얼마나 많은 것을 배웠는지를 평가하는 많은 대안들이 있습니다. 한 가지 방법은 간단하게 학교 성적을 이용하는 것입니다. 다른 방법들로는 인터뷰, 더 많은 실제적인 접근법, 또는 심지어 시간을 재지 않고 쓰는 에세이가 될 수도 있습니다. 이 모든 방법들은 가난한 수험생들도 그들의 능력을 발휘할 수 있게 해줄 것입니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >표준화된 시험은 수백 년 동안 교육의 일부였습니다. 우리가 표준화된 시험들을 사용하는 데는 좋은 이유가 있고, 지금 이를 바꾸면 안 됩니다. 첫째, 이 시험들은 학생들이 동등하게 평가되도록 합니다. 모든 사람이 같은 질문을 받고 동일한 자료를 배워야 합니다. 이런 식으로 일부 학생들이 수월한 학교에 가거나 수월한 선생님을 만나는 것에 대한 이점이 없을 것입니다. 둘째로, 표준화된 시험은 학생들이 부정행위를 할 수 없도록 보장합니다. 학생들은 극도로 면밀하게 감시되며, 어떤 종류의 부정행위는 실격으로 이어질 것입니다. 누구도 그렇게 부도덕한 일을 해서 성공하는 것이 허용되서는 안 됩니다. 세번째이자 마지막으로, 시험의 압박은 학생들이 언제 그것이 필요한지 알고있다는 것을 증명합니다. 예를 들어, 만약 의대생이 압박이 높은 상황에서 중요한 시험에 통과하지 못한다면, 대부분의 사람들은 아마도 그 의대생들이 그들의 의사가 되는 것을 원하지 않을 것입니다. 이러한 시험들은 수세기 동안 진행되어 왔으며 오늘날에도 마찬가지로 중요합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is it common in Korea to provide standardized tests?</li>
          <li>Is standardized testing a reliable measure of intelligence?</li>
          <li>Should standardized tests, in your opinion, be prohibited?</li>
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

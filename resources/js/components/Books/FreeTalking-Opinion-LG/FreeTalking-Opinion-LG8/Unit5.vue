<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/two-girl-with-crayon-drawing-lesson-classroom_1150-3849.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Who is Responsible for the Costs of Nursery Education?
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
      <td class = "lowertable" >It is evident that free nursery provision ensures a good start in education for all children by providing a more stimulating environment than parents can achieve at home, with music, books, and arts and crafts activities alongside physical play. An early start can be made on educational basics such as literacy and numeracy, allowing every child a greater chance to achieve their full potential.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Research indicates that starting children too young in formal education is counter-productive and can limit their academic progress in later years.It can also put them off schooling from an early age. Health and safety rules, and the convenience of the teachers also dictate that children in nursery schools spend little time outside, exploring the physical environment and playing in the open air, thus limiting an important part of early years development.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>provisions</b> 제공[공급]하다, 주다 
        </p>
        <p>
          <b>stimulate</b> 궁금증을 자아내다
        </p>
        <p>
          <b>literacy</b> 글을 읽고 쓸 줄 아는 능력
        </p>
        <p>
          <b>potential</b> 잠재력
        </p>
        <p>
          <b>counter-productive</b> 역효과를 낳는
        </p>
        
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >무료 유치원(육아) 공급은 부모들이 집에서 성취하는 음악, 책, 미술, 공예활동과 신체적 놀이와 더불어 더 많은 환경을 제공해 모든 아이들에게 좋은 교육의 시작을 확실하게 각인 시킬 수 있는 증거가 되기도 한다. 일찍이 시작 함으로써 언어와 수리 같은 교육의 기본을 형성하고 모든 아이들이 그들의 잠재력을 달성할 수 있는 기회를 준다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >연구는 너무 어릴 때 공식 교육을 시작하면 비생산적이고 이후 학업 진행을 제한할 수 있다고 지적했다. 또한 이것은 이른 나이에 그들을(아이들을) 학교로부터 멀게 할 수 있다. 건강 안전 규칙과 선생님들의 편의 또한 유치원의 아이들이 외부에서 적은 시간을 보내고, 물리적 환경을 탐험하고 열린 공간에서 노는 것이 부족하기에 이것은 어린 발달단계에 큰 부분을 제한한다고 구술했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think it is essential for kids to be sent to nursery school? Why or why not?</li>
          <li>Does interacting with other kids helpful in a child’s development? Why?</li>
          <li>Is introducing a child to a formal learning environment at a young age affects their development? Why or why not?</li>
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

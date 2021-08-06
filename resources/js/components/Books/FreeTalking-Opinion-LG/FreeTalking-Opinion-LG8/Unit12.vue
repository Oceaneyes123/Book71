<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/diverse-hands-touching-white-paper-mockup-pink-wallpaper_53876-96147.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Society Needs Competition?
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
      <td class = "lowertable" >This debate must stay logical. Healthy competition is a symbol of a flourishing society. Competition Provides a fair and equal opportunity to all the players. Survival of the fittest; it means that the fittest come out on top. As asserted in the definition of this debate competition creates merit. Aggressive competition will weed out those who aren't good and seed out those who outshine their contemporaries. The end-result is something positive for the society.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Treating cases of cheating, bribery as negligible without further investigation on the matter is rather presumptuous. Competition Would only be fair if every student/worker being evaluated existed in the same environment exactly, with the same or rather equivalent resources, suited/catered to each student / worker's needs based on individual strengths, weaknesses and personalities. As this is not the case competition reveals a monster of inefficiency labeling undeserving candidates as good and bad without basis.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>competition</b> 경쟁
        </p>
        <p>
          <b>flourish</b> 번창하다
        </p>
        <p>
          <b>assert</b> 주장
        </p>
        <p>
          <b>contemporaries</b> 동시대인
        </p>
        <p>
          <b>negligible</b> 무시하다
        </p>
        <p>
          <b>presumptuous</b> 주제넘은, 건방진
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >이 논쟁은 논리적이어야 한다. 건전한 경쟁은 번영하는 사회의 상징이다. 경쟁은 모든 선수들에게 공정하고 똑 같은 기회를 제공한다. 가장 적당한 생존은, 가장 적당한 것이 최고를 낳는다는 것을 의미한다. 이 논쟁의 정의에서 주장하는 것처럼 경쟁은 장점을 만들어낸다. 공격적인 경쟁은 좋지 못한 사람들을 걸러내고 동년배보다 뛰어난 사람들의 씨를 뿌린다. 그 결과는 사회에 긍정적이다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >그 문제에 관해 무시해도 될 정도로 조사하지 않고 부정행위, 뇌물 수수를 다루는 것은 다소 건방지다. 경쟁은 다소 동등한 자원을 가지고, 개인적인 강점, 약점 그리고 성격에 근거한 학생/근로자의 필요에 맞춘, 모든 학생/근로자가 정확히 같은 환경에 존재한다면 공정할 것이다. 이것은 그 경우가 아니기 때문에 경쟁은 자격이 없는 후보라는 꼬리표를 붙이는 비효율성이란 괴물을 드러낸다. </td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Can you give an example of a “healthy competition” in a society?</li>
          <li>Do you think it is advantageous for a person to have a competitive mindset? Why?</li>
          <li>Is having a competition beneficial in society? Why?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/acoustic-guitar-recording-studio-room-musicians-rehearsals_169016-3805.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Learning a musical instrument should be mandatory at school
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
      <td class = "lowertable" >Students should be forced to learn a musical instrument in school. Learning a musical instrument will give a student a valuable skill and is also very fun. Students will enjoy being able to play their favorite songs on a musical instrument. In addition, learning a musical instrument helps students learn. Learning a musical instrument teaches a student to think in a new way and encourages students to develop good studying skills. This is because mastering an instrument is very difficult and takes time and dedication. </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Learning a musical instrument should not be mandatory at school. Playing music is just a hobby that many people do for fun. It is not the same as learning math, history, or science. Forcing a student to learn an instrument at school risks wasting valuable school and studying time. Moreover, students that wish to learn an instrument can learn that instrument outside of school. There is no reason that learning an instrument should be mandatory at school. All students should not be forced to learn an instrument just because some students want to.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>valuable</b> 가치 있는
        </p>
        <p>
          <b>favorite</b> 좋아하는
        </p>
        <p>
          <b>to encourage</b> 격려하다
        </p>
        <p>
          <b>to master</b> ~을 숙달하다
        </p>
        <p>
          <b>reason</b> 이유
        </p>
        <p>
          <b>dedication</b> 헌신
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >학생들은 학교에서 악기를 배우도록 강요를 받아야 합니다. 악기를 배우는 것은 학생들에게 중요한 기술을 가르쳐주고 또한 매우 즐겁습니다. 학생들은 악기로 그들이 좋아하는 노래를 연주할 수 있는 것을 즐길 것입니다. 게다가 악기를 배우는 것은 학생들이 학습에 도움이 됩니다. 악기를 배우는 것은 학생들이 새로운 방법으로 생각하도록 가르치고 학생들이 좋은 공부하는 기술을 개발하도록 장려합니다. 이것은 악기를 통달하는 것은 매우 어렵고, 시간이 걸리고 전념해야 하기 때문입니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >악기를 배우는 것을 학교에서 의무화해서는 안 됩니다. 음악을 연주하는 것은 많은 사람들이 즐기기 위해 하는 그저 취미입니다. 악기를 배우는 것은 수학, 역사나 과학을 배우는 것과 같지 않습니다. 학교에서 악기를 배우도록 학생에게 강요하는 것은 소중한 학교시간과 공부할 시간을 낭비할 위험이 있습니다. 게다가 학생들은 악기를 배우기를 원하면 과외 활동으로 악기를 배울 수 있습니다. 악기를 배우는 것을 학교에서 의무화해야 할 이유가 없습니다. 오로지 일부 학생들이 원하므로 모든 학생들이 악기를 배우도록 강요를 받지 말아야 합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Did you learn to play a musical instrument when you were a child? What instrument did you learn and how long did it take you to master it?</li>
          <li>What are the benefits of learning to play a musical instrument?</li>
          <li>Should students be obliged to study a musical instrument in school?</li>
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

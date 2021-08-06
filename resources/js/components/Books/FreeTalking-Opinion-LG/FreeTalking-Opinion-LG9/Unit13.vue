<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/agency-young-adult-profession-stressed-black_1134-1279.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Peer Pressure
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
      <td class = "lowertable" >On balance, the pros of peer pressure tip the scales in its favor. When you are among your peers, the pressure that you receive from them motivates you to do your best. If your classmates are getting perfect scores on their tests, then you, too, will be motivated to study harder. This motivation is not only limited to school, either. Individuals can be motivated to do volunteer work and do better at work.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >I am against peer pressure. Peer pressure causes too much stress for people. At school, students will feel pressure to fit in with the other students, so they will do whatever it takes to fit in socially or academically. Students will register for extra classes if their scores are lower than their peers. Students might also try to conform in harmful ways. If some popular students take up bad things, then other students are going to feel pressured to start them, too.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>peer pressure</b> 동료의 압력
        </p>
        <p>
          <b>motivate</b> (행동 등의) 이유[원인]가 되다
        </p>
        <p>
          <b>fit in</b> 일치하다
        </p>
        <p>
          <b>conform</b> (규칙·법 등에) 따르다[맞다]
        </p>
      </div>
      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >모든 것을 감안할 때, 동료집단으로부터 받는 압력의 장점은 그것에게 좋게 저울 한 쪽이 무겁게 한다. 당신이 당신의 동료들 사이에 있을 때, 그들로부터 당신이 받는 압력은 당신이 최선을 다하도록 동기를 부여한다. 만일 반 친구들이 시험에서 만점을 받는다면, 당신도, 역시, 더 열심히 공부하도록 동기가 부여될 것이다. 이 동기는 역시 단지 학교에만 국한된 것이 아니다. 개인들은 자원봉사를 하고 직장에서 더 잘하도록 동기가 부여될 수 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >스트레스는 인생의 정상적인 부분이다. 그러나 스트레스는 나쁜 것일 필요는 없다. 스트레스 문제는 사람들이 그것을 부정적인 시각으로 본다는 것이다. 만일 사람들이 스트레스를 짐 대신 기회로 간주한다면, 사람들은 그것에 관해 그렇게 많이 초조해하지 않을 것이다. 그러므로 새로운 것을 배워야 하는 것에 관해 불평하는 학생들은 그것에 관해 걱정하지 말아야 한다. 그들은 새로운 것을 배우는 기회들을 수용해야 한다. 나쁜 것을 할지도 모르는 다른 학생들이 하는 것에 맞출 필요를 느끼는 학생들에게 있어서, 그들은 그런 종류의 영향을 무시해야 한다. 긍정적인 역할 모델들은 우리 사회 모든 곳에서 발견될 수 있다. 학생들은 학교에 너무 멋진 사람들을 존경하고 맞출 필요를 느낄 필요가 없다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are your thoughts on peer pressure?</li>
          <li>Have you ever made a decision that was influenced by peer pressure?</li>
          <li>Do you think that peer pressure is something that can cause a negative effect on a person’s life?</li>
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

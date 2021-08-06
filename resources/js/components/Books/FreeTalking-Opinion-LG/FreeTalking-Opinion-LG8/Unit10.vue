<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/workwear-coats-jackets-hanging-rack_53876-63422.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">The Meaning of Uniforms

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
      <td class = "lowertable" >Uniforms can help people to be identified. If a policeman was giving a parking ticket to a person, they would need something to prove that they are a police officer and have the authority. It also helps army/navy troops to recognize each other. It can also help team or company members recognize one another.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Using a uniform to assume someone’s occupation creates opportunities for deceiving people. It is important to rely on valid identification rather than uniforms, which can be replicated easily. There are enough avenues for advertising without needing a uniform for such purposes. For the majority of the time employees will wear their uniform at work and therefore the only target audience will be individuals who are already customers of the company.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>uniform</b> 제복, 군복, 교복, 유니폼
        </p>
        <p>
          <b>authority</b> 지휘권
        </p>
        <p>
          <b>recognize</b> (어떤 사람·사물을 보거나 듣고 누구·무엇인지) 알아보다
        </p>
        <p>
          <b>deceiving</b> 속이다, 기만하다
        </p>
        <p>
          <b>avenues</b> (나아갈) 길, 방안
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >유니폼은 사람들이 신분을 확인하는데 도움을 줄 수 있다. 만약 경찰이 어떤 사람에게 주차위반딱지를 준다면, 그들이 경찰관이고 권위를 갖고 있음을 증명할 어떤 것이 필요할 것이다. 그것은 또한 육군/해군이 서로를 인정하는 데 도움이 된다. 또한 팀이나 동료들에게 서로를 인정하게끔 도와줄 수 있다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >누군가의 직업을 추측하기 위해 유니폼을 입는 것은 사람들을 속일 수 있는 기회를 유발한다. 그것은 유니폼이 쉽게 복제될 수 있다기 보다 유효한 신분 증명에 의존하는 것이 중요하다. 광고행위를 하는 회사들이 그러한 목적으로 유니폼을 요구하지 않고도 충분히 나아갈 방향들이 있다. 시간제 직원들의 대다수가 직장에서 유니폼을 입을 것이다. 따라서 유일하게 그 타겟이 되는 사람들은 그 회사에 이미 존재하는 고객들일 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is wearing a uniform a must? Why or why not?</li>
          <li>Do you think a uniform is a form of identification? Why?</li>
          <li>Should civilians be allowed to wear police or any military uniform as costumes? Why?</li>
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

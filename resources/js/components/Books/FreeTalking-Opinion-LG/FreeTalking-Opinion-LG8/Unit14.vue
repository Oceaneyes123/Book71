
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/upset-teenage-girl-crossing-arms-chest-being-angry-mother-who-is-taking-away-credit-card_343059-505.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Strict Parents: Should they be More Laissez Faire?
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
      <td class = "lowertable" >Children need to know the ground rules and be clear on the boundaries. If you are vague and ambiguous when giving orders and strict about a matter oneday yet relaxed on the same matter a different day, the child will be confused and won't know how to react; it will stress them out more to never be sure of what isn't and is OK than to be punished strictly a couple of times but to know exactly why.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Some parents can be overbearing and do not even give out much praise as in their opinion, only A’s are to be expected of the child and this doesn’t really deserve any praise as it is not particularly significant. The child will try their hardest to impress their parents or attempt to reach the high goals their parents set for them, yet some will inevitably fail. This leads to low self-esteem, shame and disappointment.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>Laissez Faire</b> 자유방임주의
        </p>
        <p>
          <b>boundaries</b> 경계(선), 분계선
        </p>
        <p>
          <b>ambiguous</b> 애매하다
        </p>
        <p>
          <b>overbearing</b> 고압적인 태도
        </p>
        <p>
          <b>inevitable</b> 불가피한, 필연적인
        </p>
        <p>
          <b>self-esteem</b> 자부심
        </p>

      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >아이들은 기본 원칙들을 알고 이를 명확히 할 필요가 있다. 만약 여러분이 명령을할 때 애매모호하고 하루는 어떤 문제에 엄격하고 다른 하루는 같은 문제에 관대하다면, 그 아이는 혼란스럽고 어떻게 반응할 지 모를 것이다; 이는 몇 번 엄격히 처벌받아 정확히 왜인지 알게 하는 것보다 옳고 그른 것을 결코 확실하지 못하게 하여 그들을 더 스트레스 받게 할 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >어떤 부모들은 강압적일 수 있고 그들의 의견에 따라 많은 칭찬을 해주지 않는다, 아이에게 A만을 기대하게 하고 이는 특히 중요하지 않기 때문에 사실 칭찬 받지 못한다. 아이는 부모에게 감명을 주기 위해 정말 열심히 노력하고 부모들이 정한 높은 목표를 달성하도록 시도할 것이다. 하지만 일부는 분명히 실패할 것이다. 이는 자부심 부족, 수치심 그리고 실망감으로 이어진다. </td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think a parent should be strict to their children? Why or why not?</li>
          <li>When you were a child, were your parents strict? How do you think that affected you?</li>
          <li>Do you think it’s important to compliment your child every once in a while? Why or why not?</li>
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


<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/women-sitting-table-shaking-hands-smiling_23-2147650878.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Public Etiquette
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
      <td class = "lowertable" >Etiquette ought to be taught in schools. Public morality is descending lower by the day. Because of this, more education is needed. Why is this descent happening? The reason why public etiquette is declining so fast stems from the lack of uniformity in moral education. The way to solve this is to have a universal curriculum that is taught to students in both public and private schools. Why should this happen at schools? It is because schools provide a centralized location for experts in the field of moral education to reach the greatest number of students. </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The best place to teach public morals is at home. Parents, the primary givers of their children, have their children’s best interests at heart. As their parents, they have the right to raise their kids in the way that they see fit. Many definitions of politeness exist. What some parents may view as polite may be seen as rude to another group of parents. Since differing views of politeness exist, teaching a uniform standard of etiquette is pointless. And finally, generations of parents have complained to no end about the declining values of the younger generations. This debate is just another round of the old criticizing the young.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>etiquette</b> (사회·특정 직종 구성원들 사이의) 예의[에티켓]
        </p>
        <p>
          <b>public morality</b> 사회 도덕
        </p>
        <p>
          <b>descent</b> 내려오기, 내려가기, 하강, 강하
        </p>
        <p>
          <b>uniformity</b> 한결같음, 고름; 일정불변, 균일성; 균등(성), 등질, 균일, 획일, 일률(opp. variety)
        </p>
        <p>
          <b>best interest</b> 최고의 이익
        </p>
        <p>
          <b>politeness</b> 공손[정중]함, 우아[고상]함
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >에티켓은 학교에서 가르쳐야 한다. 공중 도덕은 날로 더 낮아지고 있다. 이것 때문에, 더 많은 교육이 필요하다. 왜 이런 낮아지는 현상이 발생하는가? 공공 예절이 매우 빠르게 낮아지는 이유는 도덕 교육의 통일성의 부재에서 생겨난다. 이것을 해결할 수 있는 방법은 공립 및 사립 학교들의 학생들에게 가르쳐지는 대중적인 교육과정을 갖는 것이다. 왜 이것이 학교에서 일어나야 하는가? 학교들이 도덕 교육의 전문가들이 가장 많은 숫자의 학생들에게 이를 수 있는 중점적인 위치를 제공하기 때문이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >공중 도덕을 가르칠 수 있는 가장 좋은 장소는 집이다. 아이들의 주요 보호자인, 부모들은 자신들의 아이들의 이익을 염두한다. 그들의 부모로서, 그들은 그들이 보기에 알맞은 방식으로 아이들을 기를 권리가 있다. 예의 바름에 관한 많은 정의들이 존재한다. 일부 부모들이 예의 바르다고 간주하는 것이 다른 모임의 부모들에게는 무례하다고 간주될 수 있다. 예의 바름에 관한 다른 관점들이 존재하기 때문에, 예절에 관한 획일적인 기준을 가르치는 것은 무의미하다. 그리고 마침내, 부모님 세대들은 젊은 세대들의 가치의 하락에 관하여 헛되이 불평해왔다. 이 토론은 젊은 사람들을 비판하는 기성 세대들의 단지 다른 경기일 뿐이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think that public etiquette is important? Why or why not?</li>
          <li>Should public etiquette be taught at school or at home?</li>
          <li>Can the environment a child grows up in affect their manners? Why or why not?</li>
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

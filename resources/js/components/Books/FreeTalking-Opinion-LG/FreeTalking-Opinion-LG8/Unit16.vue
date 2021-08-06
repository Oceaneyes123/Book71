<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/being-sad-feel-like-outcast_329181-14198.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Dealing with Bullies
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
      <td class = "lowertable" >Consequences are the best way to teach people to change certain antisocial behavioral characteristics. One reason is that if a bully gets away with it, s/he has no incentive to change (no defamation, no giving up things; nothing): “I did it cause I could.” Another reason is that the bully begins to identify with being a bully, as if that whos/he is, guilt factors in pressuring the bully to believe that this is his/her calling:”I can’t change who I am.” It becomes a habit,and habits are hard to get rid of: “I know it's bad, but I can’t help it, this is what I do, I’ve done it all my life. I can’t stop now.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Kids who commit suicide usually have problems outside of bullies. Bullies pick on kids who stand out, either by being very good at something or very bad, either way victims tend to be loners. Victims tend not to fit in. In sum, bullies pick on kids with pre existing problems. Oftentimes, bullies were bullied in the past or fit the same criteria. A bully could be a teacher’s pet or a jock just as a victim can be either. The question of the source of damage can be impossible to solve.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>consequences</b> (발생한 일의) 결과
        </p>
        <p>
          <b>incentive</b> (어떤 행동을 장려하기 위한) 장려책
        </p>
        <p>
          <b>loner</b> 주로 혼자 지내는 사람, 혼자 있기를 더 좋아하는 사람
        </p>
        <p>
          <b>bully</b> (약자를) 괴롭히는 사람
        </p>
        <p>
          <b>guilt</b> 죄책감
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >결과는 사람들로 하여금 특정한 반사회적 행동 특성을 바꾸도록 가르칠 수 있는 가장 좋은 방법이다. 한 이유는, 만일 괴롭혀도 처벌받지 않으면, 그들은 행동을 바꿀 이유가 없다 (명예훼손도 없고, 어떤 것을 포기하는 것도 없고; 아무 것도 없는 것이다.): “나는 할 수 있기 때문에 그렇게 했어요.” 또 다른 이유는 괴롭힘은 괴롭힘을 확인하기 위해 시작된다, 마치 누군가를 괴롭히는 사람들이 “나는 나를 바꿀 수가 없어요.”라고 믿는 것과 같이 말이다. 그것은 버릇이 되었고, 버릇은 없애기 힘들다: “나도 그것이 나쁜 줄 알지만 어쩔 수 없어요, 이게 내가 하는 일이고, 나는 평생 그래 왔고, 지금 그만 둘 수 없어요.”.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >자살을 하는 대부분의 어린이들은 괴롭힘을 당하는 것 말고 다른 이유가 있다. 괴롭히는 사람들은 눈에 띄거나, 혹은 무엇인가를 아주 잘하거나 못하는 아이를 선택한다. 어느 쪽이든 주로 혼자 있는 경향이 있는 희생자들이다. 희생자들은 잘 어울리지 못하는 경향이 있다. 요약하자면 괴롭히는 사람들은 원래 문제가 있는 아이들을 고른다. 종종 괴롭히는 아이들은 과거에 괴롭힘을 당했거나 같은 기준에 적합하다. 괴롭히는 아이는 선생님이 예뻐하는 학생 또는 운동을 많이 하는 남학생이 될 수 있으며 희생자 또한 그렇다. 문제의 근원은 풀기 힘들다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Have you ever been bullied before? For what reason?</li>
          <li>Do you think school bullying should be more strictly monitored? Why or why not?</li>
          <li>Why do you think bullies exist?</li>
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

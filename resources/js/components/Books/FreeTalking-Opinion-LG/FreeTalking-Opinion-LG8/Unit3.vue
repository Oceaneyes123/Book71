
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/smile-corporate-skyscraper-teeth-bare_1134-1439.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Athletes Receive Government Funding?
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
      <td class = "lowertable" >Being a top sportsman or woman means hours of training every day in order to become the very best. It is not possible to train in this way while working in a normal job. Athletes can only train full time if they are paid to do so, and given the best equipment and coaching. If we want to see top athletes competing at the highest level, we must be prepared for our government to pay for it out of our taxes.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >It is not the job of the state to fund sporting success. Even if government wanted to give money away to top athletes, they have so many more important things to spend our taxes on - like education, health and security. A better way to fund top sportsmen is through the free market. If you are good enough at popular sports like football, tennis, basketball, boxing, and cricket, then people will pay to see you and you can become very rich. If you are not talented enough, or your sport isn’t one people will pay to watch, why should the government give you money? </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>equipment</b> 장비, 용품
        </p>
        <p>
          <b>coaching</b> 코치, 개인 교습
        </p>
        <p>
          <b>training</b> (스포츠 대회를 위한) 훈련
        </p>
        <p>
          <b>fund</b> (이용 가능한) 돈
        </p>
        <p>
          <b>highest level</b> 최고 수준; 최고 수뇌, 최고위층
        </p> 
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >최고의 남자운동선수나 여자 운동선수가 된다는 것은 최고가 되기 위해 매일 몇 시간씩 훈련을 한다는 것을 의미한다. 일상의 일을 하면서 이렇게 훈련한다는 것을 불가능하다. 만약 운동선수들이 돈을 받고, 그리고 제일 좋은 장비와 코치가 있다면 그들은 풀타임 (전임제)로 훈련 받을 수 있다. 만약 우리가 가장 높은 수준의 경기를 펼치는 최고의 선수들을 보고 싶다면 우리는 반드시 정부가 우리의 세금에서 지불한다는 것에 대한 준비를 해야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >스포츠의 성공에 투자하는 것은 국가의 일이 아니다. 정부들이 만약 최고의 선수들에게 돈을 주는 것을 원한다 했다 해도 교육, 건강, 그리고 보안 등 우리의 세금을 써야 할 더 중요한 것들이 많이 있기 때문이다. 최고의 선수들에게 지원금을 주는 더 좋은 방법은 자유시장을 통해서이다. 만약 당신이 축구, 테니스, 농구, 복싱, 크리켓 같이 유명한 스포츠를 잘 한다면 사람들은 당신을 보기 위해 돈을 지불할 것이고 당신은 부자가 될 수 있을 것이다. 만약 당신이 충분히 잘하지 못하거나 당신의 스포츠가 사람들이 보기 위해 돈을 지불하는 종목이 아니라면 왜 정부가 당신에게 돈을 주어야 하나?</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you like watching sports? If yes, who is your favorite athlete and why?</li>
          <li>Would you consider being a national athlete as an occupation? Why or why not?</li>
          <li>Do you think it’s a must for the government to fund athletes?</li>
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

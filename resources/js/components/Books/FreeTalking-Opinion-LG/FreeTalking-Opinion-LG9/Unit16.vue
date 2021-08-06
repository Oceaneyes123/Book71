<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/female-travelers-travel-happily_1150-5737.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should we do what we like doing?
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
      <td class = "lowertable" >I think that we should do what we like. If we choose a job that we like, we will be passionate about our work. Because we will be passionate about our work, we will try harder to do a good job. We will be able to produce better and more creative work. In addition, we will happily go to work every day. If we are not happy with our jobs, we will get a lot of stress from work. Getting a lot of work related stress is bad for our health. In some extreme cases, people have died or committed suicide from stress at work.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Doing what you are good at is better than the alternative. Society demands that people do their jobs well. If you are not able to perform at a high level at work, employers are not going to hire you. Some people might want to be professional athletes, but what kinds of fans are going to go see athletes who cannot perform well? Even though some people might try their hardest to become professional athletes, they simply do not have the talent for it.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>passionate</b> 욕정[열정]을 느끼는[보이는], 격정적인
        </p>
        <p>
          <b>creative</b> 창조적인, 창의적인
        </p>
        <p>
          <b>alternative</b> 대안, 선택 가능한 것
        </p>
        <p>
          <b>high level</b> 고위급의
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >우리가 좋아하는 일을 해야 한다고 생각한다. 우리가 좋아하는 일을 선택한다면, 우리의 일에 대해 열정적일 것이다. 우리의 일에 대해 열정적일 것이기 때문에, 우리는 일을 잘하기 위해 더 노력할 것이다. 우리는 더 나은 그리고 더 창조적인 일을 생산해 낼 수 있을 것이다. 게다가, 우리는 매일 직장에 행복하게 출근할 것이다. 만일 우리가 일에 만족하지 않는다면, 일로 인하여 많은 스트레스를 받을 것이다. 일과 관련된 스트레스를 많이 받는 것은 건강에 나쁘다. 일부 극단적인 경우, 직장에서의 스트레스로 인하여 사람들은 죽거나 자살한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >당신이 잘 하는 일을 하는 것이 그 대안보다 더 낫다. 사회는 사람들이 일을 잘 해야 한다고 요구한다. 만일 당신이 직장에서 높은 수준으로 일을 수행할 수 없다면, 고용주들은 당신을 고용하지 않을 것이다. 어떤 사람들은 전문 선수가 되고 싶을지 모르지만, 어떤 팬들이 잘하지 못하는 운동선수를 보러 갈 것인가? 비록 어떤 사람들이 전문 선수가 되기 위해 최선을 다할지라도, 단지 재능이 없는 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What is your dream job?</li>
          <li>Do you think all people should do what they like to do for a living? Why or why not?</li>
          <li>If you were to choose between doing what you like and a well-paying job, which one will you choose and why?</li>
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

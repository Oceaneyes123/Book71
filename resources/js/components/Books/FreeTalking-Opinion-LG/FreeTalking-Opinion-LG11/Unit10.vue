<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/portrait-young-woman-wearing-protective-mask-using-her-mobile-phone-while-standing-outdoors-street_58466-15740.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should People Be Allowed To Walk While On Their Smartphones?

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
      <td class = "lowertable" >In China, the city of Chongqing opened a lane for smartphone users so that they would be safe from walking into lamp posts or traffic. In 2013, a study at Ohio State University found that smartphone walking injuries in the US increased by crazy margins. In 2005, only 256 emergency room cases had occurred because of ‘distracted walkers.’ In 2010, that number jumped to 1,506. Today, that number has quadrupled. When you walk while using a smartphone, your field of vision closes down to 5%. A study published in 2012 by Stony Brook University found that those who texted while walking were 60% more likely to veer off course than non-texters. If people are fined for texting while driving, then the same should happen for walkers. People who walk while texting can harm themselves or others. There should be punishments before this problem worsens.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >People have been yearning for distraction since the dawn of time. In ancient times, Thales of Miletus, a famous philosopher and astrologer, was busy staring at the stars and fell into a well. This has become a very famous anecdote that illustrates the situation perfectly. Whether it is a bird, a plane, or a smartphone, people will be distracted. Granted, these smartphone zombies are becoming a greater problem in the world, but to impose rules will only make people do it in secrecy with greater risk. Prohibition never solves problems, particularly ones stemming from an innateness of human nature. Perhaps it is more sensible for phone companies to have watches sold in tandem with their phones. With a smartwatch you can check it and go back to staying on the road instead of veering off course. Companies should fix this problem, before governments go into imposing oppressive laws.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>distraction</b> (주의) 집중을 방해하는 것
        </p>
        <p>
          <b>lane</b> 도로, 길
        </p>
        <p>
          <b>lamp post</b> 가로등 기둥
        </p>
        <p>
          <b>margin</b> 차이
        </p>
        <p>
          <b>quadruple</b> 네 배가 되다
        </p>
        <p>
          <b>punishment</b> 처벌
        </p>
        <p>
          <b>yearn</b> 갈망하다, 동경하다
        </p>
        <p>
          <b>astrologer</b> 점성술사
        </p>
        <p>
          <b>impose</b> 부과하다
        </p>
        <p>
          <b>in tandem with</b> ~와 동시에
        </p>
        <p>
          <b>oppressive</b> 억압[탄압]하는, 억압적인
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >중국 충칭시는 스마트폰 사용자들만을 위한 도로를 개장해서, 그들이 가로등 기둥에 받치거나 교통으로부터 안전하게 걸을 수 있게 한다. 2013년, 오하이오 주립 대학의 연구는 미국에서 스마트폰 보행 사고가 극적으로 증가했다는 것을 발견했다. 2005년, 256건의 응급실 사고가 ‘주의가 산만해진 보행자’에 의해 발생되었다. 2010년에 그 수는 1,506건으로 증가했다. 오늘날, 그 수치는 네 배가 되었다. 만약 여러분이 스마트폰을 사용하면서 걷는다면, 여러분의 시야의 범위는 5%로 줄어든다. 2012년 스토니 브룩 대학에서 발표한 한 연구는, 보행 중 문자를 보내는 사람들은 그렇지 않는 사람들에 비해 60% 더 항로를 이탈할 가능성이 있다고 발견했다. 만약 운전 중에 문자를 보내는 사람들에게 벌금을 부과한다면, 똑같은 벌금이 보행자에게도 적용되어야만 한다. 보행 중 문자를 보내는 사람은 그들 혹은 타인을 다치게 할 수 있다. 이 문제가 악화되기 전에 처벌이 있어야만 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >인류가 시작될 때부터 사람들은 오락활동을 갈망해 왔다. 고대 시대에, 유명한 철학가이자 점성술사였던 밀레투스의 탈레스는 별을 바라보는 데 바빠 우물에 떨어지기도 하였다. 이것은 그 상황을 완벽하게 예증해 주는 아주 유명한 일화가 되었다. 그것이 새든 비행기든 스마트폰이든 사람들은 주의를 빼앗길 것이다. 물론 스마트폰에 중독된 좀비들이 세계적으로 더 큰 문제가 되고 있지만, 규제를 부과하는 것은 사람들이 더 큰 위험과 함께 몰래 그것을 하도록 만들 뿐이다. 금지한다고 해서 절대 문제가 해결되지 않으며, 인간의 타고난 본성에서 나오는 것들은 특히 더 그렇다. 아마도 전화 회사들이 전화들과 시계를 나란히 파는 것이 더 현명할 수도 있다. 스마트워치로 당신은 그것을 확인하고 항로에서 벗어나는 대신 도로에 다시 머물 수 있다. 회사들은 정부가 억압적인 법을 부과하기 전에 이러한 문제를 고쳐야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is it safe to use a smartphone while walking?</li>
          <li>What are the risks of using a smartphone while walking?</li>
          <li>Should there be a law prohibiting people from using their phones while walking?</li>
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

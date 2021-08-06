<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/asian-women-refuse-fast-food-because-slimming-pink_1150-13185.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Junk Food Be Banned?
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
      <td class = "lowertable" >According to Healthline News in 2014, the Center for Disease Control and Prevention declared nearly 17 million US children between the ages of 2 and 19 are obese. If there’s ever a need to change the way food in schools is handed out, now is the time. With the mass production of saturated fats, artificial preservatives and the overabundance of sugar in junk food, the threat of obesity and diseases like diabetes is a reality for many children today. As students’ bodies are constantly changing and growing, it is much more important that they grow and mature with strong, healthy bodies. Studies have shown students who live and eat more healthily also improve their memory, concentration skills, and overall academic performance.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Making choices in what to eat and what not to eat is the responsibility of no one else but the students themselves. While the parents may play a big part in forming their children’s appetite, the school certainly does not have the duty to take care of what the students eat. The primary purpose of schools or any educational institution is to educate children; not to make choices on behalf of them. Thus, what the schools should be doing is imprinting the ideas of a healthy diet on the students instead of banning junk food altogether. The schools may also attempt to emphasize the importance of exercising in classes and increase the number of hours for physical education within its curriculum.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>obese</b> 비만의
        </p>
        <p>
          <b>saturated fat</b> 포화 지방
        </p>
        <p>
          <b>artificial</b> 인공적인, 가공된
        </p>
        <p>
          <b>overabundance</b> 과잉, 과다
        </p>
        <p>
          <b>diabetes</b> 당뇨병
        </p>
        <p>
          <b>as a whole</b> 전체적으로
        </p>
        <p>
          <b>imprint</b> 각인시키다, 새기다
        </p>
        <p>
          <b>altogether</b> 완전히
        </p>
        <p>
          <b>curriculum</b> 교과 과정
        </p>
  </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >2014년 Healthline News에 따르면, 2세에서 19세의 미국 아이들 약 1,700만명이 비만이라고 질병관리예방본부에서 선언했다. 만약 학교에서 음식이 분배되는 방법이 변화해야 할 필요성이 있다면, 지금이 바로 그 때이다. 정크 푸드의 포화 지방과 인공 방부제, 그리고 과다한 당의 대량 생산으로 비만과 당뇨병 등의 질병 위협은 오늘날 아이들에게 실질적인 위협이다. 학생들의 신체가 끊임없이 변화하고 자라나면서, 그들이 튼튼하고 건강한 신체를 가지고 성숙해야 한다는 것이 중요하다. 더욱 건강하게 살고 먹는 학생들의 기억력과 집중력, 그리고 전반적인 학업 성취도 역시 개선된다는 것을 연구들이 보여 왔다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >무엇을 먹고 먹지 말아야 하는지에 대한 선택을 하는 것은 다른 누구의 책임도 아닌 학생들 자신의 책임이다. 아이의 입맛을 형성하는 데에 부모가 큰 역할을 할 수 있지만, 학교는 확실히 학생들이 무엇을 먹을지에 대해 관리할 의무가 없다. 학교 또는 모든 교육 시설의 주요 목적은 아이들을 가르치는 것이다; 그들을 대신해서 선택해 주는 것이 아니다. 이와 같이, 학교가 해야 할 일은 정크 푸드를 전반적으로 금지시키는 대신에 학생들에게 건강한 식단에 대한 생각을 새기는 것이다. 학교는 교실에서 운동하는 것의 중요성을 강조하거나 교과 과정에서 체육 시간을 더욱 늘리려는 시도를 할 수도 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you eat junk food? If yes, how often?</li>
          <li>Is it ideal for kids to eat junk foods? Why or why not?</li>
          <li>Should junk foods be banned from stores? Why?</li>
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

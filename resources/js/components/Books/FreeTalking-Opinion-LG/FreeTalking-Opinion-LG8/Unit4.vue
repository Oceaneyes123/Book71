<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/retirement-plan_1101-738.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should There Be a Mandatory Retirement Age?
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
      <td class = "lowertable" >Mandatory retirement gives younger people greater opportunities of employment. Considering the high unemployment statistics in many countries, it will help reduce youth unemployment. This is more economically sound - it makes more sense to pay more pensions than to support the unemployed youth of the country. If they are not given the opportunity to begin a career, or become established at a company, it is far more difficult to encourage them later in life.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The population in many countries is ageing. People are living longer. Forcing people to retire simply increases the heavy economic burden of pensioners. The ratio of the dependent population to the working population is increasing, and a mandatory retirement age is an unnecessary measure that exacerbates the problem. Instead, we should be actively encouraging those who are able to continue working.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>mandatory</b> 법에 정해진, 의무적인
        </p>
        <p>
          <b>retirement</b> (정년이 되어서 하는) 은퇴
        </p>
        <p>
          <b>unemployment</b> 실직 상태
        </p>
        <p>
          <b>pension</b> 연금; 생활 보조금, 수당
        </p>
        <p>
          <b>exacerbate</b> 악화시키다
        </p>
  </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >정년제는 젊은 사람들에게 더 많은 고용의 기회를 준다. 많은 나라의 높은 실업 통계를 고려하면, 정년제는 청년 실업을 줄이는데 도움이 될 것이다. 이것이 좀더 경제적으로 안전하다 ? 청년 실업자들을 부양하는 것 보다 (퇴직자들에게) 연금을 지불하는 것이 이치에 맞는다. 청년들이 일할 기회가 없거나, 회사에서 자리를 잡을 기회가 없다면, 나중에 청년들이 (일할 수 있도록)격려하는 것은 훨씬 더 어렵다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >많은 나라의 인구가 나이를 먹고 있다. 사람들은 더 오래 살고 있다. 사람들을 퇴직하게 하는 것은 단순히 연금 수령자의 경제적 부담을 가중시킬 뿐이다. 노동인구에 의존해 사는 인구 비율은 증가하고 있으며, 의무 정년제는 이 문제를 악화시키는 불필요한 수단이다. 대신에, 우리는 계속 일 할 수 있는 사람들을 적극적으로 격려해야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>At what age do you see yourself retiring from work?</li>
          <li>Do you think there should be a mandatory retirement age? At what age do you think it should be and why?</li>
          <li>Do you agree that as long as a person is still able to work, they should be allowed to do so?</li>
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

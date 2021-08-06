<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/closeup-shot-entrepreneur-working-from-home-his-personal-finances-savings_181624-34445.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Why is life so expensive?
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
      <td class = "lowertable" >Muhammad Yunus, an entrepreneur, once said, “Poverty does not belong in civilized human society. Its proper place is in a museum.” Although many countries around the world today are well-established financial giants, poverty is ironically still a reality that many people struggle with every day. Uncontrollable circumstances leave millions jobless and out on the streets, forcing them to give up on any hope for a better life and future. One way to battle poverty and to take serious steps to gradually overcome this issue is universal basic income (UBI). </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Providing universal basic income (UBI) ensures that all citizens will sustain their basic needs, that no one will live in poverty, and encourages people to be more productive. So what’s not to like? Although the concept of UBI promises to solve many of our long-lasting socio-economic problems, poverty and wealth disparity is highly complex and difficult to resolve. With the cost of living growing by the day, let us consider a basic income of W1,000,000 per month. Korea, with a population of roughly 50 million citizens, this would amount to a yearly government tax bill of W600,000,000,000,000. Megan McArdle of Bloomberg View stated, “Handing out a universal benefit of any size at all will be fantastically expensive.” This enormous amount actually exceeds the Korean government’s entire budget by almost double for the entire year. This is simply not a price tag that any developed country in the world can afford.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>entrepreneur</b> 기업가
        </p>
        <p>
          <b>ironically</b> 반어적으로
        </p>
        <p>
          <b>uncontrollable</b> 통제할 수 없는
        </p>
        <p>
          <b>circumstances</b> 상황
        </p>
       </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >기업가인 무하마드 유너스는 “가난은 문명화된 인간 사회에 속하지 않는다. 그것의 적절한 장소는 박물관 안에 있다”라고 말했다. 비록 세계의 많은 나라들이 안정된 금융 강대국이지만, 가난은 아이러니하게도 여전히 많은 사람들이 매일 힘겹게 다루고 있는 현실이다. 통제할 수 없는 상황들은 수백만 명의 사람들의 일자리를 잃게 하고 거리로 내몰아서, 그들이 더 나은 생활과 미래를 가지는 희망을 강제로 포기하게 만든다. 가난과 싸우고 이 문제를 점진적으로 극복하기 위해 중대한 조치들을 취하는 한 가지 방법은 기본소득이라 할 수 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >기본소득을 제공하는 것은 모든 스위스 시민들이 그들의 기본적인 욕구들을 지속시킬 것이고, 어느 누구도 가난하게 살지 않게 할 것이라는 점을 보장하고, 사람들이 더 생산적이게 부추긴다. 안 좋아할 이유가 있나요? 기본소득의 개념은 우리의 오래 지속되는 사회경제적인 문제들 중 많은 문제들을 풀기로 약속하고 있지만, 가난과 빈부격차는 대단히 복잡하고 풀기 어렵다. 생활비가 하루마다 상승하면서, 우리에게 매달 일백만 원의 기본소득을 고려해 봅시다. 약 5천만 명의 인구를 가지고 있는 한국에서 이 금액은 1년 단위의 정부 납입고지서가 600조원에 달할 것을 의미한다. 블룸버그 뷰의 메간 맥아들은 “다양한 크기의 보편적인 혜택을 나눠 주는 것은 대단히 비쌀 것이다”라고 말했다. 이 엄청난 금액은 한해 동안 한국 정부의 전체 예산을 실제로 거의 두 배 초과한다. 이것은 세계의 어떠한 선진국도 감당할 수 있는 가격표가 아니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think cost of living is more expensive these days than 5 or 10 years ago? Why?</li>
          <li>What can you say about universal basic income?</li>
          <li>In your opinion, will providing a UBI be more helpful?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/side-view-cropped-unrecognizable-business-people-working-common-desk_1098-20474.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Work Quality or Work Quantity?
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
      <td class = "lowertable" >Over several decades, South Korea has undergone exponential economic growth, making the seniority-based pay system the most suitable and appropriate for workers, as well as for the nation’s economy. Since then, this pay system has been employed by most domestic businesses, allowing steady increases in wage according to years of service due to the relatively low wage during this rapid growth period. However, times have changed in Korea’s economy, which calls for a more fundamental change in the labor environment to match the circumstances.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >How much we get paid at work is directly linked to what we can afford and how we can support our everyday lives. Our salary definitely reflects our ability and efficiency as an individual at work. A performance-based wage system may sound reasonable and motivating, but is that really the case? In an interview with Workforce, management theorist Frederick Herzberg said, “If you want people motivated to do a good job, give them a good job to do.” Author Alfie Kohn also said that a performance-based system does things to employees instead of working with them, meaning that it won’t motivate or transform them. Instead, he said it would create rowdy competition that may complicate coworker relationships.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>undergo</b> 겪다
        </p>
        <p>
          <b>exponential</b> 기하급수적인
        </p>
        <p>
          <b>wage</b> 임금
        </p>
        <p>
          <b>match</b> 맞추다, 부응하다
        </p>
        <p>
          <b>circumstance</b> (주로 복수) 환경
        </p>
        <p>
          <b>afford</b> 여유가 되다, 형편이 되다
        </p>
        <p>
          <b>reasonable</b> 타당한, 사리에 맞는
        </p>
        <p>
          <b>rowdy</b> 소란스러운
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >수십 년에 걸쳐, 한국은 엄청난 경제적인 성장을 하여서, 성과연봉제를 국가 경제뿐만 아니라 근로자들에게 가장 알맞고 적절하게 만들었습니다. 그때 이후로, 이 임금 체계는 대부분의 국내 기업들에 의하여 쓰여서, 이 급속한 성장 시기 동안 비교적 낮은 임금 때문에 수년 간의 근무연수에 따라 임금을 꾸준히 인상시키고 있다. 그러나, 한국의 경제 시기는 변했고, 이것은 노동환경에서 그 상황에 맞추기 위해 더욱 근본적인 변화를 요구하고 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >리가 직장에서 받는 급여는 우리의 일상을 지원할 수 있고 무엇을 살 수 있는지 판단한다. 우리의 연봉은 확실히 회사 내의 우리의 능력과 효율성을 반영한다. 성과연봉제는 합리적이고 동기부여가 되는 것처럼 보이나 과연 그런가? 워크포스와의 인터뷰에서 경영관리 이론가 프레드릭 헤즈버그는 “사람들이 일을 잘할 수 있도록 동기부여를 하고 싶다면 좋은 직업을 주면 된다.”라고 했다. 작가 알피 콘은 또한 성과연봉제는 직원들과 일하는 대신 고용주들에게 영향을 미친다고 말했는데, 이것은 그것이 고용주들에게 동기 부여를 주거나 그들을 바꾸지는 않을 것이라는 것을 의미한다. 그 대신, 그는 결국 회사동기들과의 관계가 복잡해지게 만들 수 있는 심한 경쟁심만 생길 것이라고 말했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What do you think is more important, work quality or work quantity?</li>
          <li>Should a person be paid based on the amount of work they’ve done? How about the quality of work?</li>
          <li>Must an employee focus more on the amount of work they can do, or the quality of work?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/vaping-device-e-cigarette_144627-30850.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is Vaping Unhealthy?
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
      <td class = "lowertable" >Despite what many people believe, vaping harms your body. E-cigarettes contain nicotine, which is an addictive and dangerous substance found in traditional cigarettes. Noting a 900 percent increase in vaping among teenagers between 2011 and 2015, U.S. Surgeon General Jerome Adams called e-cigarette use an epidemic. In addition, according to a study in The Journal of the American Medical Association, teenagers who use e-cigarettes are four times more likely to start smoking than those who have never used tobacco. Surprisingly, the study also said that e-cigarettes serve as a gateway to smoking. Plus, a Harvard study noted that nicotine may impair brain development in young people, increasing the risk of developing attention deficit hyperactivity disorder and disruptive impulse control. Moreover, Nancy Brown, CEO of the American Heart Association, said that the tobacco industry markets e-cigarettes in a wide range of fruit and candy flavors to appeal to teenagers. Thus, vaping is just as unhealthy as smoking.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >E-cigarettes are a better alternative to traditional cigarettes. E-cigarettes help people to quit smoking, and they also decrease the number of deaths and diseases caused by regular cigarettes. According to a study from this year, cigarette smokers who pick up vaping are 67 percent more likely to quit smoking. In addition, a study in The New England Journal of Medicine states that e-cigarettes are twice as effective as regular nicotine replacements, like patches and gums, when it comes to helping people get rid of their smoking habits. Furthermore, the U.S. National Academies of Science, Engineering, and Medicine found conclusive evidence that switching from traditional cigarettes, which are known to cause lung cancer, heart disease, and stroke, to e-cigarettes dwindles the exposure to carcinogens and toxicants. Peter Hajek, a professor at Queen Mary University of London, said, “Smokers who switch to vaping remove almost all the risks smoking poses to their health.” Therefore, vaping is definitely safer than smoking.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>epidemic</b> 급속한 확산[유행]
        </p>
        <p>
          <b>gateway</b> ~에 이르는 수단
        </p>
        <p>
          <b>impair</b> 손상[악화]시키다
        </p>
        <p>
          <b>attention deficit hyperactivity disorder</b> 주의력 결핍 과잉 활동 장애
        </p>
        <p>
          <b>impulse</b> 충동
        </p>
        <p>
          <b>appeal</b> 관심[흥미]을 끌다
        </p>
        <p>
          <b>effective</b> 효과적인
        </p>
        <p>
          <b>conclusive</b> 결정적인, 확실한
        </p>
        <p>
          <b>carcinogen</b> 발암 물질
        </p>
        <p>
          <b>toxicant</b> 독물
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >많은 사람들의 믿음에도 불구하고, 전자담배는 몸을 해롭게 한다. 전자담배는 기존 담배에서 발견되는 중독성 있고 위험한 니코틴을 함유하고 있다. 2011년과 2015년 사이에 10대들의 전자담배 사용이 900퍼센트 증가한 것을 주목하며 미국의 의무감 (醫務監)인 제롬 아담스는 전자담배 사용을 유행병이라고 불렀다. 게다가, 미국의학협회저널의 연구에 따르면, 전자담배를 사용하는 10대들은 담배를 전혀 사용해보지 않은 사람들보다 담배를 시작할 가능성이 네 배 더 높았다. 놀랍게도, 그 연구는 또한 전자 담배가 흡연으로의 관문 역할을 한다고도 말했다. 뿐만 아니라, 한 하버드의 연구는 니코틴이 주의력 결핍 및 과잉 행동 장애를 발달시키고 충동 조절을 방해하는 위험을 증가시키면서, 젊은 사람들의 뇌 발달을 손상시킬 수 있다고 주목했다. 게다가, 미국심장협회의 CEO인 낸시 브라운은 담배 산업이 10대들의 관심을 끌 수 있는 광범위한 과일과 캔디 맛의 전자담배를 출시한다고 말했다. 그러므로, 전자담배는 흡연만큼이나 건강에 해롭다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >전자담배는 기존 담배에 더 나은 대안이다. 전자담배는 사람들이 금연을 하도록 돕고, 그것은 또한 일반적인 담배가 발생시키는 사망 및 질병 숫자를 감소시킨다. 올해의 한 연구에 따르면, 전자담배를 하는 흡연자들은 67퍼센트 더 금연할 가능성이 크다. 게다가, 뉴잉글랜드 의학저널의 한 연구가 사람들이 그들의 흡연 습관을 없애도록 도와주는 데 있어서 전자담배가 패치 및 껌과 같은 일반적인 니코틴 대체제보다 두 배 더 효과적이라고 언급한다. 그리고, 전미 과학, 엔지니어링 및 의학학회는 폐암, 심장병 및 뇌졸중을 일으키는 것으로 알려진 기존 담배로부터 전자담배로 전환하는 것이 발암물질과 독물로의 노출을 줄인다는 결정적 증거를 찾아냈다. 런던의 퀸메리대학의 교수인 피터 헤이젝은 “전자담배로 전환하는 흡연자는 흡연이 그들의 건강에 제기하는 거의 모든 위험을 없앤다” 라고 말했다. 따라서, 전자담배는 분명히 흡연보다 더 안전하다.</td>
          </tr>
          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is vaping bad for your health?</li>
          <li>Is vaping a good idea when you’re trying to quit smoking? Explain.</li>
          <li>What motivates people to vape or smoke?</li>
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

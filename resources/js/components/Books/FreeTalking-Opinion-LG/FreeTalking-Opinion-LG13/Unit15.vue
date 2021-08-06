<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/beautiful-sunrise-fishing-dip-nets-pakpra-phatthalung-thailand_335224-816.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Overfishing poses a greater threat to the environment than global warming
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
      <td class = "lowertable" >Overfishing is a problem that humanity must deal with immediately.The increasing demand for fish globally means that the problem of overfishing is rapidly accelerating. One of the most important factors for overall ocean health is ocean biodiversity. The loss of even one small species of fish can affect all the other species that call theocean home. For example, if tuna fish were to become extinct, plankton populations could grow to become out of control and affect many other species of fish. Likewise, the loss of a significant proportion of global fish supplies risks increasing starvation and malnutrition amongst the human populations that live in regions that rely on fish for protein.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Although overfishing is a looming threat, the magnitude of global warming means that it is a more important concern. Global warming will affect everyone and everything on the planet, including fish.For example, the melting of the polar ice caps risks changing the temperature of the ocean which could cause many species of fish to become extinct. Reducing the amount that we fish will not matter if fish species are going extinct because of global warming. </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>associated with</b> ~와 연관된
        </p>
        <p>
          <b>population</b> 개체수
        </p>
        <p>
          <b>starvation</b> 기아
        </p>
        <p>
          <b>immediate</b> 즉각적인
        </p>
        <p>
          <b>humanity</b> 인류, 인간
        </p>
        <p>
          <b>accelerate</b> 증가하다
        </p>
        <p>
          <b>biodiversity</b> 생물의 다양성
        </p>
        <p>
          <b>extinct</b> 멸종의
        </p>
        <p>
          <b>significant</b> 상당한
        </p>
        <p>
          <b>portion</b> 부분
        </p>
        <p>
          <b>malnutrition</b> 영양결핍
        </p>
        <p>
          <b>magnitude</b> 규모
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >남획은 인류가 반드시 즉시 대처해야 하는 문제입니다. 어류에 대한 증가하는 수요는 남획이라는 문제가 빠르게 증가하고 있다는 것을 의미합니다. 바다의 건강에 대한 가장 중요한 요소 중 하나는 생물의 다양성입니다. 어류 중 하나의 작은 종의 소멸도 바다를 집이라고 부르는 다른 모든 종들에게 영향을 미칠 수 있습니다. 예를 들어, 만일 참치가 멸종하게 된다면, 플랑크톤 개체 수는 증가하여 통제할 수 없게 되고 많은 다른 어류 종들에게도 영향을 미칩니다. 마찬가지로, 전세계적인 어류 공급의 상당한 부분을 잃는다면 기아는 증가하고 단백질을 얻기 위해 어류에 의지하는 지역에서 살고 있는 인류 사이에 영양결핍이라는 위험을 감수해야 합니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >비록 남획이 무시무시한 위협이지만, 온실효과의 규모는 그것이 더 큰 걱정거리라는 것을 의미합니다. 온실효과는 어류를 포함하여 지구상의 모든 것과 모든 사람에게 영향을 미칩니다. 예를 들어, 극지방의 만년설이 녹는 것은 많은 어류를 멸종하게 만들 수 있는 바다의 온도를 변하게 할 수 있습니다. 온실효과 때문에 만일 어종이 멸종한다면, 우리가 잡는 어류의 양을 줄이는 것은 중요하지 않을 것입니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What impact does overfishing have on the environment?</li>
          <li>Is overfishing more harmful than global warming?</li>
          <li>In what ways can overfishing be solved?</li>
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

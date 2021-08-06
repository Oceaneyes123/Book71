<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/interested-dark-haired-girl-wears-casual-attire-chilling-park-near-university-using-laptop_197531-6966.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Does Going to a Good University Matter?
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
      <td class = "lowertable" >Whether it is justified or not, some universities have a certain amount of grandeur about them. From The very moment they are mentioned they have an impressive nature. This is not only with Oxford and Cambridge, but also with those red brick universities in the U.K.’s oldest towns. If nothing else, these universities would certainly make a person feel proud for attending and being able to tell people about it. It is also likely that employers from red brick universities will prefer red-brick university alumni for employees because they can relate to them.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Going to university should not be like collecting badges. University education is not only about the institution you go to but also the skills you learn. If we suggest that those skills are of differing quality,then we are saying something is very wrong with our education system. All of our universities are assessed against the same objective criteria by many external examiners and their research and teaching is assessed by many different institutions. Therefore, a 2.1 from one university should be the same as another.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>grandeur</b> 장엄함
        </p>
        <p>
          <b>red-brick university</b> 붉은 벽돌로 된
        </p>
        <p>
          <b>institution</b> (대학·은행 등과 같이 특정 목적을 지닌 대규모) 기관
        </p>
        <p>
          <b>criteria</b> 기준
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >정당하든 안 하든, 일부 대학들은 어느 정도의 위엄을 가지고 있다. 그들이 언급되는 바로 그 순간, 그들은 인상 깊은 본질을 갖고 있다. 이것은 옥스포드와 캠브리지뿐만이 아니라 영국의 가장 오래된 도시의 빨간 벽돌로 된 대학들에도 있다. 최소한, 이러한 대학들은 그 학교에 재학중인 것과 사람들에게 그것을 말할 수 있다는 것에 분명 자신을 자랑스럽게 할 것이다. 빨간 벽돌 대학의 고용주들은 빨간 벽돌 대학 졸업생들이 그들과 연관이 있기 때문에 더 선호할 것이다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >대학에 들어가는 것이 증표를 모으는 것처럼 되어서는 안 된다. 대학 교육은 여러분이 가는 기관뿐만 아니라 여러분이 배우는 기술이다. 만약 우리가 그러한 기술이 다양한 질을 갖고 있다라고 제안한다면, 우리는 교육 제도에 문제가 있다고 말할 수 있다. 우리 모든 대학들은 많은 외부 채점관들에 의해 동등한 객관적 기준에 따라 평가 받고 그들의 연구와 가르침은 많은 다양한 기관들에 의해 평가 받는다. 따라서, 한 대학의 2.1 학점은 다른 대학과 동등해야 한다. </td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think that some companies hire employees based on their university alma mater? Why or why not?</li>
          <li>Is it essential to be able to go to a good university? Why?</li>
          <li>Do you think all universities should have the same standard in teaching? Why?</li>
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

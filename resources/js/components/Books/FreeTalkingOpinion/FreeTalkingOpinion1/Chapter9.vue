<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://image.freepik.com/free-photo/group-multiethnic-diverse-hands-raised_53876-64967.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <transition name="slide-fade">
        <h1 v-if="showTitle" class="upper-header-opinion1">Is Majority Vote Really The Best Way To Make Decision?
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class="line-top-opinion1">
  </div>

  <h3  class = "lower-header-opinion1 white--text">Topic</h3>
  <div style = "line-height: 1.6;">
    <div style="padding : 16px;">   

    <table class = "standard-table">

    <tr>
      <td class = "uppertable" ><b>A :</b></td>
      <td class = "lowertable" >I think majority vote is a reasonable way to make decisions.
      It is impractical to take into account every single opinion in a group.
      Going with the option that most people chose allows better representation.</td>
    </tr>
    <tr style="color:#1565C0;">
      <td class = "uppertable" ><b>B :</b></td>
      <td class = "lowertable" >I disagree. Majority vote may reflect more people's views.
      However, being a majority doesn't mean being wiser.
      It just means that more people agree with Sometimes minority opinions offer a better solution.</td>
    </tr>

    </table>

    </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>majority vote</b> 다수결
        </p>
        <p>
          <b>discuss</b> 토론하다
        </p>
        <p>
          <b>reasonable</b> 합리적인
        </p>
        <p>
          <b>impractical</b> 비현실적인
        </p>
        <p>
          <b>opinion</b> 의견
        </p>
        <p>
          <b>option</b> 선택
        </p>
        <p>
          <b>representation</b> 대의 권
        </p>
        <p>
          <b>reflect</b> 반영하다
        </p>
        <p>
          <b>minority</b> 소수
        </p>
        <br />
        <p style="color: #56AAFF;">
          <b>take into account 고려하다.</b>
        </p>

      </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-translate-opinion1 white--text">해석</h3>
      <div style="padding : 16px;">

                      <p class = "korean">
                        <b>
                        다수결의 원칙은 결정을 내리는 데 최선의 방법인가?
                        </b>
                      </p>

                      <table class = "standard-table">

                       <tr>
                        <td class = "uppertable" ><b>A :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >다수결은 의사 결정을 내리기 위한 합리적인 방법이라고 생각해 집단 내의 모든 의견을 고려하는 것은 비현실적이야.
                        대부분의 사람들이 선택한 선택에 따라 더 나은 표현을 할 수 있어</td>
                      </tr>
                      <tr style="color:#1565C0;">
                        <td class = "uppertable" ><b>B :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >나는 동의하지 않아, 다수결은 더 많은 사람들의 견해를 반영할지도 몰라.
                          그러나 과반수가 된다고 해서 현명해 지는 것은 아니야.
                          그것은 더 많은 사람들이 당신의 의견에 동의한다는 것을 의미해.
                          때로는 소수의 의견이 더 나은 해결책을 제시하기도 해.</td>
                      </tr>

                    
                      </table>

        


      </div>

     <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Questions</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Why do a lot of people believe in the opinion of the majority?</li>
          <li>Give me a situation where majority vote is usually followed in making decisions.</li>
          <li>What are the instances when majority vote is not applicable?</li>
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

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}


body{

  font-size: 16px;
}



</style>

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/wedding-cake-decor-made-two-rocking-chairs_8353-1725.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Marriage Be Mandatory?
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
      <td class = "lowertable" >Marriage should be compulsory. At less than one baby per woman, Korea’s birth rate is at an all-time low. The government is trying to encourage couples to build families, like giving newlywed couples affordable housing. However, the bigger problem is that more and more Koreans are opting not to get married. According to Statistics Korea, in 2018, the number of marriages in the country decreased by 2.6 percent from 2017. In 2017, the number of marriages decreased by 6.1 percent from 2016. As you can see, the rate has been on the decline for several years. Therefore, one solution to Korea’s falling birth rate is to encourage marriage. However, encouraging couples to marry is simply not enough. With mandatory marriage, couples will have to get engaged and eventually get married. This may sound like a dramatic move, but if the government is serious about Korea’s plummeting population, mandatory marriage should be something to consider.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Marriage should remain a choice, and it should never be mandatory. How are mandatory marriages any different from forced marriages? Forcing someone into marriage is a form of human rights abuse. According to the Universal Declaration of Human Rights, which was adopted by the U.N. in 1948, “Marriage shall be entered into only with the free and full consent of the intending spouses.” In addition, these forced marriages often lead to unhappy, miserable lives. In Afghanistan, where forced marriages are prevalent, women sometimes resort to committing suicide in order to escape these marriages, according to German broadcaster Deutsche Welle. Monika Hauser, a German women’s rights activist, explained, “The suicide rate is rising particularly in towns because women are fighting against forced marriages there.” Due to large populations of Muslim and South Asian migrant families, forced marriages take place in European countries as well. Abuse is also quite common in these marriages. Thus, marriage should be optional.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>compulsory</b> 강제적인, 의무적인
        </p>
        <p>
          <b>newlywed</b> 신혼의
        </p>
        <p>
          <b>affordable</b> (가격이) 알맞은
        </p>
        <p>
          <b>opt</b> (~을 하기로 하지 않기로) 택하다
        </p>
        <p>
          <b>engaged</b> 약혼한
        </p>
        <p>
          <b>plummet</b> 폭락[급락]하다
        </p>
        <p>
          <b>consent</b> 동의[허락]
        </p>
        <p>
          <b>spouse</b> 배우자
        </p>
        <p>
          <b>miserable</b> 비참한
        </p>
        <p>
          <b>prevalent</b> 널리 퍼져 있는
        </p>
        <p>
          <b>resort</b> (보통 달갑지 않은 수단에) 호소하다
        </p>
        <p>
          <b>optional</b> 선택적인
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >결혼은 반드시 필수가 되어야 한다. 여성 한 명당 아기가 한 명 이하로, 한국의 출산율은 사상 최저수준이다. 정부는 신혼부부들에게 감당할 수 있는 가격의 주택을 제공하는 것과 같이 커플들이 가정을 꾸리도록(만들도록) 독려하려고 노력하고 있다. 하지만 더 큰 문제는 더욱 더 많은 한국인들이 결혼을 하지 않기로 선택하고 있다는 것이다. 한국 통계청에 따르면, 2018년에, 이 나라의 혼인 건수는 2017년도보다 2.6% 감소하였다. 2017년에는 2016년에 비해 결혼숫자가 6.1% 감소하였다. 당신이 볼 수 있는 것처럼, 이 비율은 몇 년 동안 감소해왔다. 그렇기 때문에, 한국의 떨어지는 출산율에 대한 하나의 해결책은 결혼을 장려하는 것이다. 하지만, 커플들을 결혼하도록 장려하는 것 만으로는 충분하지 않다. 의무 결혼과 함께 커플들은 약혼해야 하고, 결국 결혼해야 할 것이다. 이는 호들갑스러운 조치로 들릴 수 있지만, 정부가 한국의 곤두박질치는 인구에 대해 진지하다면 의무 결혼은 고려해 볼 문제이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >결혼은 선택으로 남아있어야 하고 절대 의무가 되어서는 안된다. 의무 결혼이 강제 결혼과 어떻게 다르겠는가? 누군가를 결혼하도록 강제하는 것은 한 형태의 인간 권리 학대이다. 1948년 U.N.에 의해 채택된 세계 인권 선언에 따르면, “결혼은 반드시 희망하는 배우자들간의 자유롭고 완전한 합의에 의해서만 체결되어야만 한다.” 또한, 이 강제된 결혼들은 종종 불행하고 비참한 삶으로 이어진다. 독일의 방송인인 Deutsche Welle에 따르면 강제 결혼이 만연한 아프가니스탄에서는 여성들이 가끔 그들의 결혼으로부터 탈출하기 위해 자살을 시도하는 것을 최후의 수단으로 삼는다. 독일의 여성 인권 운동가인 모니카 하우저는 “마을에서 자살률이 특히 늘어나고 있는데 왜냐하면 여성들이 그곳에서 강제 결혼에 저항해서 싸우고 있기 때문입니다.” 라고 설명하였다. 이슬람 교도들과 남아시아 이주 가족들의 대규모 인구 때문에, 강제 결혼은 유럽 국가에서도 이루어지고 있다. 이러한 결혼들에서는 학대 또한 꽤 흔한 일이다. 그러므로, 결혼은 반드시 선택적이어야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is it acceptable in your country to live together with your partner without getting married?</li>
          <li>Why is it important to get married?</li>
          <li>What are the disadvantages of marriage?</li>
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

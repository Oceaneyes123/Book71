<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/business-financial-concept-stack-money-background-flat-lay_176474-6549.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Do I need to carry cash anymore?
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
      <td class = "lowertable" >Less than a decade ago, the idea of using a credit card was still foreign to many in Korea. But today, who doesn’t use a credit card as a primary method of payment? In the near future, it’s likely that countries will continue adopting more electronic payment systems as IoT devices seep into daily life. It’s needless to say that cashless systems will make life more convenient as users won’t need to carry around cold hard cash. According to Cisco, mobile money has helped developing countries like Kenya and Somalia transfer money safely without visiting a bank. In addition, cashless systems decrease the amount of money spent by financial institutions to print, count, secure, and manage physical money. Bengt Nilervall with the Swedish Federation of Trade said, “It’s safer this way and it saves us money, as handling money and transporting cash is costly.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Our ever-advancing technological world indicates that carrying cold hard cash in our wallets is rapidly becoming antiquated due to the rise of IoT-enabled devices in the payment industry. In South Korea, electronic payments gained popularity after the introduction of T-money in 2004, according to The Straits Times. Since then, it has been reported that South Koreans are relying less on cash and more on cards and electronic payments. While a cashless system does offer convenience and speedy transactions, there are still too many hiccups in our technology today. Electronic payment systems cannot guarantee complete safety for all its users.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>foreign</b> 이질적인
        </p>
        <p>
          <b>adopt</b> 채택하다
        </p>
        <p>
          <b>cashless</b> 현금이 불필요한
        </p>
        <p>
          <b>hard cash</b> 현금
        </p>
        <p>
          <b>institution</b> 기관
        </p>
        <p>
          <b>indicate</b> 보여주다
        </p>
        <p>
          <b>antiquated</b> 구식인
        </p>
        <p>
          <b>guarantee</b> 보장하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >약 10년 전 만해도 신용 카드를 쓰는 발상은 한국의 많은 사람들에게 아직 이질적이었다. 하지만 이제 누가 신용 카드를 주요한 결제 방식으로 사용하지 않는가? 멀지 않아 사물인터넷이 일상 생활에 스며들면서, 국가들은 더 많이 전자 결제 시스템을 채택할 것 같다. 사용자들이 현금을 들고 다닐 필요가 없기 때문에, 현금이 불필요한 시스템이 삶을 더욱 편리하게 만들 것이란 점은 말할 필요도 없다. 시스코에 따르면, 모바일 머니는 이미 케냐나 소말리아와 같은 개발도상국들이 은행을 방문할 필요 없이 계좌 이체를 무사하게 할 수 있게 도와주었다. 게다가, 현금이 불필요한 시스템은 지폐 인쇄, 계산, 보안, 그리고 관리에 쓰였던 금융 기관들의 지출을 줄여준다. 스웨덴 무역연맹의 벵 닐레발은 “그것은 돈 관리와 운송에 드는 비용이 비싸기 때문에, 더 안전하며 우리가 돈을 절약하게 해줍니다”라고 말했다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >우리의 빠르게 발전하는 과학기술 세상은 우리 지갑에 현금을 들고 다니는 것이 결제 업계에 빠르게 확산되고 있는 사물인터넷 사용이 가능한 기기들 덕분에 구식이 될 것임을 시사하고 있다. 더 스트레이트 타임즈에 따르면, 2004년에 티머니가 소개된 후 전자결제가 한국에서 유행 했다고 한다. 그때부터, 계속해서 한국 국민들은 현금을 덜 쓰고 더욱 카드들과 전자결재를 이용한다고 보고 되었다. 현금이 불필요한 체제는 편리함과 빠른 거래를 보장해 주지만, 우리의  기술에는 아직도 너무 많은 결함이 있다. 전자결제 시스템은 모든 사용자들에게 완전한 안전함을 보장해 줄 수 없다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you still take cash with you when going out? Why or why not?</li>
          <li>What are the advantages of using a credit card on a daily basis?</li>
          <li>Do you think there will come a time where using cash will not be an option?</li>
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

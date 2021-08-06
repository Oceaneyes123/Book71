<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/bitcoin-new-concept-virtual-money-graphics-digital-background-gold-coin-with-image-letter-b-mining-blockchain-technology-close-up_169016-4494.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Invest In Bitcoin?
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
      <td class = "lowertable" >Bitcoin is dangerous, and while people may think that it will become a stable form of traded currency, it is too unstable. In the past, trading commodities with such volatility have often come to punish investors. In the Netherlands, tulips were once a high-priced commodity. Unfortunately, the bubble burst and left many investors with withering tulip bulbs and empty pockets. While bitcoin is a digital currency, it has had a history of black market trading for illegal goods. In the past, the internet black market has used bitcoin and its untraceable transactions to sell drugs, buy assassins, and sell explicit imagery. In China, the government has essentially made bitcoin transactions illegal. In Korea, a leading bitcoin exchange shut down after multiple hacking attacks, leaving customers empty-handed. Many suspect North Korea to be thriving on the bitcoin boom with their illicit funds division. Using bitcoin is essentially a form of money laundering. We should not invest in bitcoin like we should not invest in illegal drugs, it is too dangerous.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Bitcoin has had a shady past, but the past is in the past. Today, many people can use bitcoins more widely. There are ATMs all around the world that can exchange money for digital currency. In fact, these ATMs are even located in popular areas like the Sacramento Kings arena. There are even apps which let you play games to get fractions of bitcoin. As the currency expands at a crazy rate, those who invested in it are reaping dividends. The Winklevoss twins, often known as the twins who sued Facebook, have become billionaires by investing their settlement into bitcoins. They even used bitcoin to pay for their flight on the Virgin Galactic space shuttle. In fact, bitcoin has even helped the homeless. Many homeless people cannot open bank accounts, but there was a case of a man who used free wi-fi during bitcoin’s first days to receive fractions of bitcoin from apps. The current all-time-high for bitcoin is $20,000. Fractions are worth thousands now.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>billionaire</b> 억만장자, 갑부
        </p>
        <p>
          <b>volatility</b> 휘발성, 변덕
        </p>
        <p>
          <b>currency</b> 통화
        </p>
        <p>
          <b>unfortunately</b> 불행하게도, 유감스럽게도
        </p>
        <p>
          <b>black market</b> 암시장
        </p>
        <p>
          <b>transaction</b> 거래, 매매
        </p>
        <p>
          <b>money laundering</b> 돈 세탁
        </p>
        <p>
          <b>fraction</b> 부분, 일부
        </p>
        <p>
          <b>sue</b> 고소하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >비트코인은 위험하고 사람들이 그것이 무역 통화의 주요부분이 될 것이라고 생각하지만, 그것은 너무 불안정하다. 과거에, 그러한 휘발성이 있는 무역 상품은 투자자를 자주 처벌했다. 네델란드에서 튤립은 한때 높은 가격의 상품이었다. 불행히도, 그 버블은 붕괴되었고, 많은 투자자들을 시든 튤립 종자와 빈털터리로 만들었다. 비트코인은 디지털 화폐인 반면, 그것은 불법적인 재화로써 블랙 마켓의 역사를 가지고 있다. 과거에, 인터넷 암시장은 비트코인을 사용했고, 약을 팔고, 암살범을 사고, 그리고 노골적인 영상을 파는 추적되지 않는 상거래에 사용했다. 중국에서, 정부는 본질적으로 비트코인 거래를 불법으로 만들었다. 한국에서, 다수의 해킹 공격 이후의 비트코인 교환거래 금지는 고객들이 돈이 없게 만들었다. 많은 이들은 북한이 그들의 불법적인 자금 분배로 비트코인 붐이 번성할 것이라고 추측한다. 비트코인의 사용은 본질적으로 돈세탁의 형태이다. 우리는 불법 약물에 투자하지 않는 것과 같이 그것이 너무 위험하기 때문에 비트코인에 투자하지 말아야만 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >비트코인은 그늘진 과거가 있지만 과거는 과거에 있을 뿐이다. 오늘날 많은 사람들은 비트코인을 더 광범위하게 사용할 수 있다. 전 세계에 돈을 이 디지털 화폐로 교환할 수 있는 ATM기계가 존재한다. 사실상 이러한 ATM은 심지어 새크라멘토 킹스 아레나와 같은 유명한 지역에 위치한다. 심지어 비트코인의 일부를 얻기 위해 당신이 게임을 하게 해주는 어플도 존재한다. 이 화폐가 미친 속도로 확장됨에 따라 이것에 투자한 사람들은 배당금을 거두고 있다. 페이스북을 고소한 쌍둥이로 자주 알려진 윙클보스 쌍둥이는 그들의 합의금을 비트코인에 투자에 억만장자가 되었다. 그들은 심지어 버진 갈라틱스 우주왕복선에서의 비행을 지불하기 위해 비트코인을 사용했다. 사실, 비트코인은 노숙자들도 도와주었다. 많은 노숙자들이 은행 계좌를 열 수 없지만 어플로부터 비트코인의 일부를 받기 위해 비트코인의 초기에 무료 와이파이를 이용한 남자의 경우도 있다. 비트코인의 현재 최고의 높은 가격은 2만달러이다. 부분들은 현재 수 천 달러의 가치에 달한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is Bitcoin popular in Korea? If yes, how did it become popular?</li>
          <li>Is Bitcoin a good investment?</li>
          <li>What are the risks of investing in Bitcoin?</li>
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

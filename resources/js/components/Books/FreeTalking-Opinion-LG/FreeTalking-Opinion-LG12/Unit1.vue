<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://img.freepik.com/free-photo/retro-television_1159-804.jpg?size=338&ext=jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is Cable Better Than Streaming Services?
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
      <td class = "lowertable" >Most people still watch cable, so it’s quite obvious that it reigns supreme. It’s the preferred way to watch TV for most of the respondents who participated in a recent survey conducted by an American research company. In fact, only 27 percent said they preferred streaming services. Plus, although a lot of people believe that streaming services are cheaper, this isn’t the case. In the U.S., a cable package with 140 channels costs around $50 (W60,600) a month. A Netflix subscription costs around $16 (W19,400) a month, but you also need to factor in the costs of owning a computer and an internet connection. If you buy a cheap computer and settle for a slow internet connection, Netflix will take forever to load. The video quality will suffer as well. Also, streaming services lack many basic channels that you might be familiar with. Cable has more content but costs less, so it’s a lot better than streaming.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Cable is a thing of the past! I feel sorry for people who still watch cable. Most people who rely on cable tend to be over the age of 60, according to surveymonkey.com. This is because they aren’t the best with technology, so the thought of using a streaming service is daunting for them. However, once you have everything set up, watching something on Netflix is a piece of cake. Just click on a show you want to watch! And unlike cable, you don’t even have to wait for a show to air. You won’t miss any of your favorite shows either, because all you have to do is press play. Furthermore, according to the Pew Research Center, only 10 percent of Americans don’t use the internet, and 95 percent of the Korean population uses the internet. This makes signing up for a streaming service a cinch, so go ahead and replace your cable subscription with a streaming service.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>prefer</b> 선호하다
        </p>
        <p>
          <b>obvious</b> 명백한
        </p>
        <p>
          <b>survey</b> (설문) 조사
        </p>
        <p>
          <b>settle for</b> ~으로 만족하다, ~을 받아들이다
        </p>
        <p>
          <b>lack</b> ~이 없다, 부족하다
        </p>
        <p>
          <b>tend</b> 경향이 있다
        </p>
        <p>
          <b>daunting</b> 벅찬, 주눅이 들게 하는
        </p>
        <p>
          <b>cinch</b> 아주 쉬운 일
        </p>
        <p>
          <b>replace</b> 대체하다
        </p>
        <p>
          <b>steadily</b> 꾸준히
        </p>
        <p>
          <b>entirely</b> 완전히
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >대부분의 사람들이 아직도 케이블을 시청하므로, 케이블이 대권을 장악하고 있다는 것은 꽤 명백하다. 그것은 미국의 한 조사 업체가 실시했던 최근의 설문조사에 참가한 응답자의 대부분이 TV를 시청하는 선호되는 방식이다. 사실, 27%만 스트리밍 서비스를 선호한다고 말했다. 게다가, 비록 많은 사람들이 스트리밍 서비스가 더 저렴하다고 믿지만, 이것은 사실이 아니다. 미국에서, 140개의 채널이 있는 케이블 패키지는 매달 약 50달러 (6만원)의 비용이 든다. 넷플릭스 구독은 매달 약 16달러 (19,400원)의 비용이 들지만, 당신은 컴퓨터와 인터넷 연결을 소유하는 비용을 고려할 필요가 있다. 만일 당신이 저렴한 컴퓨터를 구입하고 느린 인터넷 연결로 만족한다면, 넷플릭스는 로딩하는데 엄청난 시간이 걸릴 것이다. 영상 품질도 더 나빠질 것이다. 또한, 스트리밍 서비스는 당신이 익숙할지도 모르는 많은 기본 채널이 없다. 케이블은 더 많은 콘텐츠가 있지만, 더 적은 비용이 들기 때문에, 케이블은 스트리밍보다 훨씬 더 낫다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >케이블은 옛날 얘기이다! 나는 아직도 케이블을 보는 사람들을 안타까워한다. surveymonkey.com에 따르면, 케이블에 의존하는 대부분의 사람들은 60세가 넘는 경향이 있다. 이것은 그들이 기술에 가장 익숙하지 않기 때문이므로, 스트리밍 서비스를 사용하는 생각은 그들에게 주눅이 들게 한다. 그러나 일단 모든 것이 설정되면, 넷플릭스에서 무언가를 시청하는 것은 쉬운 일이다. 당신이 보기를 원하는 프로그램에 클릭만 하라! 그리고 케이블과 다르게, 당신은 심지어 어떤 프로그램이 방영되기를 기다릴 필요가 없다. 당신이 해야 하는 것이 재생을 누르는 것 밖에 없기 때문에 당신은 당신이 좋아하는 프로그램의 어떤 것도 놓치지 않을 것이다. 게다가, 퓨리서치센터에 따르면, 미국인의 단 10%만이 인터넷을 사용하지 않고, 한국 인구의 95%가 인터넷을 사용한다. 이것은 스트리밍 서비스에 가입하는 것을 아주 쉬운 일로 만들므로, 어서 가서 당신의 케이블 구독을 스트리밍 서비스로 대체하라.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How often do you watch TV these days?</li>
          <li>Do you prefer cable television or online streaming services? Why?</li>
          <li>Do you think cable TV is going to die soon as streaming becomes more popular?</li>
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

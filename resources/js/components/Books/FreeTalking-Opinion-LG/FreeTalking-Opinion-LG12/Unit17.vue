<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/person-holding-mobile-phone-with-white-screen_23-2148794620.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">iPhones Versus Android Phones
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
      <td class = "lowertable" >It’s pretty clear that iPhones are better than Android phones. First of all, iPhones are faster. They contain an A12 Bionic chip, which Apple calls “the smartest and most powerful chip ever in a smartphone.” According to tomsguide.com, Android phones are catching up. However, nothing can beat the performance of an iPhone. Mark Spoonauer, who writes for the site, said, “The gap is narrower than it has been in the past thanks to the Snapdragon 855 processor that will power this year’s leading Android phones, but the iPhone XS scored a higher 11,420 to the 855-powered Galaxy S10 Plus’ 10,732.” He added, “We’ve also found that the latest iPhones can transcode video faster in our editing test, with the iPhone XS taking just 39 seconds, compared to nearly 2.5 minutes for the Galaxy S10.” In addition, iPhones are safer. A study by Pulse Secure revealed that 97 percent of mobile malware and viruses were for Android phones. The iPhone wins!</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Everyone wants iPhones, but that doesn’t mean they’re better than Android phones. Android phones come with a better A.I. assistant. Called Google Assistant, it is better than Apple’s Siri in many ways. According to lifewire.com, “It uses everything Google knows about you and the world to make life easier for you. For instance, if your Google Calendar knows that you’re meeting someone at 5:30 and that traffic is terrible, Google Assistant can send you a notification telling you to leave early.” Siri, on the other hand, is limited to relatively simple tasks. According to medium.com, “If you speak too fast or with a strong accent, Siri will not understand you.” Furthermore, Android uses Gmail as its main e-mail app, and cnn.com says that Apple’s email app is clunky and slow to navigate. The site also says that Android is better than Apple when it comes to maps and organizing your contacts. If you’re thinking about switching to an iPhone, reconsider.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>performance</b> 성능
        </p>
        <p>
          <b>transcode</b> 하나의 인코딩에서 다른 인코딩으로 전환시키다
        </p>
        <p>
          <b>malware</b> 악성 소프트웨어
        </p>
        <p>
          <b>traffic</b> 교통(량)
        </p>
        <p>
          <b>notification</b> 알림
        </p>
        <p>
          <b>accent</b> 말씨
        </p>
        <p>
          <b>clunky</b> 투박한
        </p>
        <p>
          <b>map</b> 지도
        </p>
        <p>
          <b>organize</b> (특정한 순서·구조로) 정리하다
        </p>
        <p>
          <b>switch</b> 바꾸다  
        </p>
        <p>
          <b>reconsider</b> 재고하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >아이폰이 안드로이드폰보다 낫다는 것은 꽤 분명하다. 우선, 아이폰이 더 빠르다. 그것에는 애플이 “스마트폰 사상 가장 스마트하고 강력한 칩”이라고 부르는 A12 바이오닉 칩이 들어있다. tomsguide.com(톰스가이드)에 따르면, 안드로이드 폰이 따라잡고 있다. 하지만, 어떤 것도 아이폰의 성능을 능가할 수 없다. 이 사이트에 기고하는 마크 스푸나우어에 따르면 “올해의 주요한 안드로이드폰을 작동시킬 스냅드래곤 855 프로세서에 힘입어 과거보다 그 격차가 좁아졌지만, 아이폰XS는 1만 1,420점으로 855-구동 갤럭시S10플러스의 1만 732점 보다 더 높은 점수를 받았다”고 말했다. 그는 또, “우리의 편집 테스트에서 우리는 최신 아이폰이 동영상을 더 빨리 인코딩 전환할 수 있다는 것을 발견하였는데, 2.5분 가까이 걸리는 갤럭시S10과 비교하여 아이폰 XS는 단 39초 밖에 걸리지 않았다”고 덧붙였다. 게다가 아이폰은 더 안전하다. 펄스시큐어의 한 연구는 97 퍼센트의 모바일 악성 소프트웨어와 바이러스가 안드로이드폰을 겨냥한 것임을 밝혀냈다. 아이폰의 승리!</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >모두가 아이폰을 원하지만 그렇다고 그것이 안드로이드폰보다 낫다는 뜻은 아니다. 안드로이드폰에는 더 나은 A.I 비서가 따라온다. 이는 구글 어시스턴트라고 불리며, 여러 면에서 애플의 시리(Siri)보다 더 낫다. lifewire.com (라이프와이어)에 따르면, “이것은 당신의 삶을 더 편안하게 만들기 위하여 구글이 당신과 세계에 대해 아는 모든 것을 이용한다. 예를 들어, 만약 구글 캘린더가 당신이 5시 30분에 누군가를 만난다는 것과 교통 상황이 끔찍하다는 것을 알고 있다면, 구글 어시스턴트는 당신에게 일찍 출발하라는 알림을 보낼 수 있다”고 한다. 반면 시리는 비교적 단순한 업무에 국한되어 있다. medium.com(미디엄)에 따르면, “너무 빨리 말하거나 강한 억양으로 말하면, 시리는 당신을 이해하지 못할 것이다”고 한다. 더 나아가, 안드로이드는 메인 이메일 앱으로 지메일(Gmail)을 사용하고 있으며, cnn.com은 애플의 이메일 앱이 투박하고 탐색 속도가 느리다고 말한다. 해당 사이트는 또한 안드로이드가 지도와 연락처를 정리하는 것에 관한 한 애플보다 더 낫다고 말한다. 만약 아이폰으로 바꿀 생각이었다면, 재고해 보라.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What operating system are you using? Are you satisfied with its features?</li>
          <li>Which operating system, in your opinion, is better: iOS or android?</li>
          <li>What are the downsides of using an iOs? An android?</li>
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

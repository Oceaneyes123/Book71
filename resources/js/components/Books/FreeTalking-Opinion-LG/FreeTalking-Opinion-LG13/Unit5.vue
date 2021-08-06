<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/rows-red-seats-theater_53876-64712.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Get Rid of Movie Theaters?
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
      <td class = "lowertable" >Movie theaters are a thing of the past. We don’t need them anymore, and the ongoing pandemic has made this quite apparent. Services such as Netflix and Disney Plus are thriving, but movie theaters are declining in popularity. According to The Washington Post’s Megan McArdle, “Theater chains are already facing a debt crisis that will become dire if they have to go another year without any significant revenue, as are the shopping malls where many of those theaters are housed.” Eric Wold, a financial analyst, said, “Debt doesn’t go away. Even if they get over the initial hump of getting theaters open again, they have to hope that attendance goes back to normal pretty quickly. They’re going to be using a lot of that cash flow toward interest payments.” In other words, the pandemic has resulted in an incredible loss for movie theaters, and a revival is nearly impossible. Online streaming will inevitably replace movie theaters, just like it did with video rental shops.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Movie theaters are fortunately here to stay. The coronavirus pandemic forced many movie theaters to close, some permanently. However, prospects are now looking good. AMC Chief Executive Adam Aron recently said that “any talk of an imminent bankruptcy for AMC is completely off the table.” The company managed to raise $917 million (W1 trillion) since December to sustain itself through the pandemic, which clearly shows that people aren’t willing to give up watching a blockbuster on the big screen. Aron added, “We are very optimistic about the future of moviegoing once the pandemic is somewhat behind us and once new movie titles are released again, but we’ve been burning through cash as we wait for that bright new day to come. We now have the cash to survive.” Moreover, Mulan bombed in China, and it also grossed only $35.5 million ($39.28 billion) on its opening weekend from Disney Plus subscribers. It’s clear that online streaming is only a supplement to actual moviegoing.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>apparent</b> 분명한, 누가 봐도 알 수 있는
        </p>
        <p>
          <b>debt</b> 빚
        </p>
        <p>
          <b>dire</b> 대단히 심각한
        </p>
        <p>
          <b>revenue</b> (기관의) 수익
        </p>
        <p>
          <b>inevitably</b> 불가피하게
        </p>
        <p>
          <b>prospect</b> (성공할) 전망
        </p>
        <p>
          <b>imminent</b> 임박한
        </p>
        <p>
          <b>bankruptcy</b> 파산 (상태)
        </p>
        <p>
          <b>moviegoing</b> 영화 구경
        </p>
        <p>
          <b>bomb</b> 크게 실패하다
        </p>
        <p>
          <b>gross</b> (세금을 공제하기 전의 액수로 ~의) 수익을 올리다
        </p>
        <p>
          <b>supplement</b> 보충[추가](물)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >영화관은 과거의 산물입니다. 우리는 더 이상 영화관이 필요하지 않고, 현재 진행중인 전염병으로 인해 이 사실이 꽤 분명해졌습니다. 넷플릭스와 디즈니 플러스와 같은 서비스는 번창하고 있지만 영화관의 인기는 떨어지고 있습니다. 워싱턴 포스트의 메건 맥아들에 따르면 “영화관 체인점들이 상당한 수익이 없이 1년을 더 운영해야 한다면 끔찍해질 부채 위기를 눈 앞에 두고 있으며, 많은 극장들이 있는 쇼핑몰도 마찬가지입니다.” 재무 분석가인 에릭 월드는 “부채는 사라지지 않습니다. 영화관들이 다시 개장하고 첫 고비를 극복한다 하더라도 객석 점유율이 꽤 빨리 정상을 돌아올 수 있기를 바래야합니다. 영화관들은 많은 자금을 이자를 내는데 사용할 것입니다.” 라고 말했습니다. 다시 말해, 코로나19의 대유행은 영화관에 엄청난 손실을 초래했고, 부활은 거의 불가능하다는 것입니다. 온라인 스트리밍은 영화관이 비디오 대여점에 그랬던 것처럼 필연적으로 영화관을 대체 할 것입니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >다행스럽게도 영화관은 우리 생활의 일부입니다. 코로나 바이러스 대유행으로 많은 영화관이 문을 닫게 되었고, 일부는 영구적으로 영업을 종료하게 되었습니다. 하지만, 현재 전망은 밝습니다. AMC 최고 경영자 애덤 아론은 “AMC가 파산이 임박했다는 어떤 이야기도 전혀 논의되지 않았습니다.” 라고 말했습니다. AMC는 전염병으로 인해 어려운 시국을 견뎌내기 위해 12월부터 9억 1700만 달러 (한화 1조원)를 모금했으며, 이는 사람들이 대형 스크린에서 블록버스터 영화를 보는 것을 포기하지 않을 것임을 분명히 보여줍니다. 아론은 “전염병이 다소 하락세가 되고 새로운 영화들이 다시 개봉한다면 영화의 미래에 대해선 매우 낙관적입니다. 하지만, 그 밝고 새로운 날이 오길 기다리며 우리는 현금을 빠른 속도로 소진해오고 있습니다. 현재 딱 살아남을 현금만 보유하고 있습니다.” 더욱이 뮬란은 중국에서 대박을 터뜨렸고 개막 주말 디즈니 플러스 가입자로부터 3550만 달러 (3928억 달러)를 벌어 들였다. 온라인 스트리밍은 실제 영화 감상을 보완할 뿐이라는 점이 명백합니다.</td>
        </tr>
      </table>
      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you believe movie theaters should remain open during this pandemic? Why or why not?</li>
          <li>Will movie theaters ever become obsolete? Why do you think so?</li>
          <li>How often do you go to movie theaters?</li>
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

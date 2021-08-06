<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/woman-using-smartphone-social-media-conecpt_53876-40967.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Has Social Media Improved Human Communication?
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
      <td class = "lowertable" >Social media has improved human communication by making it more convenient to do so. People are now able to reach out to new friends, maintain relationships and talk to family members at the touch of a button. According to Insider magazine, 83 percent of teenagers say that social media makes them feel more connected to their friends. Social media also helps businesses to communicate more effectively and in turn acquire more customers for their products. In 2017, a survey found that 69 percent of marketers relied on social media to maintain their customer base and 66 percent of all social media users were more loyal to businesses that they followed online. Social media also has positive effects on mental health. The BBC noted that users of Twitter, especially women, were able to reduce their stress by venting about experiences in their own lives. The positive effects of social media are important to ponder when considering the benefits of the technology.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Social media, although convenient, has damaged human interaction and has negative effects on human communication. Without human interaction, people are unable to develop social skills, which can result in social awkwardness in real life situations. Social media sites like Instagram, have been deemed responsible for developing anxiety and depression in young people. A study published in the journal Computers and Human Behavior found that people who used up to two different social media websites had high levels of anxiety. Research conducted by youth charity, Plan International U.K., found that half of all girls and 40 percent of boys had been victims of bullying online. The health impacts of social media have also been researched, with negative results. Constant use of social media has reduced sleep quality in online users, resulting in tiredness. The risks related to social media seem to outweigh the rewards and online communication is still no substitute for real-life interaction.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>convenient</b> 편리한
        </p>
        <p>
          <b>connect</b> 연결되다
        </p>
        <p>
          <b>customer base</b> 고객층
        </p>
        <p>
          <b>loyal</b> 충성스러운
        </p>
        <p>
          <b>mental health</b> 정신적 건강
        </p>
        <p>
          <b>vent</b> (감정·분통을) 터뜨리다
        </p>
        <p>
          <b>ponder</b> 숙고하다
        </p>
        <p>
          <b>damage</b> 손상시키다
        </p>
        <p>
          <b>responsible for</b> ~에 책임이 있는
        </p>
        <p>
          <b>anxiety</b> 불안
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >소셜 미디어는 소통을 더 편리하게 만들어줌으로써 인간의 의사소통을 향상시켰습니다. 이제 사람들은 버튼 하나로 새로운 친구에게 다가가고 관계를 유지하며 가족 구성원과 대화 할 수 있습니다. Insider 매거진에 따르면 청소년의 83%는 소셜 미디어를 통해 친구들과 더 친밀감을 느낀다고 합니다. 또한 소셜 미디어는 기업이 보다 효과적으로 커뮤니케이션하고 제품에 대한 더 많은 고객들을 확보하는데 도움이됩니다. 2017년 한 설문조사에 따르면 마케팅 담당자의 69%가 고객 기반을 유지하기 위해 소셜 미디어에 의존했고, 전체 소셜 미디어 사용자의 66%가 온라인에서 팔로우한 기업에 대한 충성도가 더 높은 것으로 나타났습니다. 소셜 미디어는 또한 정신 건강에 긍정적인 영향을 미칩니다. BBC는 트위터 사용자들, 특히 여성들이, 자신의 삶의 경험들을 공개함으로써 스트레스를 줄일 수 있었다고 언급했습니다. 소셜 미디어의 긍정적인 효과는 기술의 이점을 고려함에 있어서 중요합니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >소셜 미디어는 편리하지만 사람들 간의 상호 작용에 피해를 주고 의사소통에 부정적인 영향을 미칩니다. 사람들간의 상호작용 없이는 사람들은 사회성을 개발할 수 없으며 이는 현실에서 사회적 어색함을 느끼게 할 수 있습니다. 인스타그램과 같은 소셜미디어 사이트들은 젊은이들의 불안과 우울증을 키운 원인이라고 여겨져 왔습니다. '컴퓨터와 인간 행동' 저널에 게재된 한 연구에 따르면 최대 두 개의 서로 다른 소셜 미디어 웹사이트를 사용하는 사람들은 높은 수준의 불안감을 느꼈습니다. 청소년 자선단체인 Plan International U.K.에서 실시한 연구에 따르면 전체 여학생들의 절반과 40%의 남학생들이 온라인에서 괴롭힘을 당했습니다. 소셜 미디어가 건강에 미치는 영향도 연구되었고 부정적인 결과를 얻었습니다. 소셜 미디어의 지속적인 사용은 온라인 사용자의 수면의 질을 저하시켜 피로가 누적됩니다. 소셜 미디어와 관련된 위험은 보상보다 더 큰 것으로 보이며, 온라인 커뮤니케이션은 여전히 실제 상호 작용을 대체 할 수 없습니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you prefer face-to-face or social media communication?</li>
          <li>How can social media improve human communication?</li>
          <li>What are the downsides of social media?</li>
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

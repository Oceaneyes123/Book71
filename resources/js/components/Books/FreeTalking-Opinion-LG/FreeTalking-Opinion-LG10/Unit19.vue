<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/fried-chicken-with-fries-copy-space_23-2148273064.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Korea Needs A Junk Food Tax
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
        <td class = "lowertable" >Obesity is a growing problem in Korea, and has been a public health threat in the U.S. and U.K. So many programs on Korean TV are about food, resulting in more Koreans overeating and keeping an unhealthy diet. So a junk food tax is needed to alleviate this problem. The Korean Society for the Study of Obesity has found that a “fat tax” can effectively reduce obesity rates and bring in more tax revenue that could be used for social services. Many health experts abroad also favor such a tax, saying obesity is a menace to public health. In Australia, one University of Queensland study found that a 20-percent tax could prevent 16,000 cases of Type-2 diabetes, 4,400 cases of heart disease and more than 1,000 cases of stroke, and rake in hundreds of millions of dollars per year.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >There’s no question that obesity and related diseases are rising in Korea, but application of a junk food tax isn’t the answer. European nations have tried using a “fat tax” to reduce consumption of junk food, with mixed or little success. Denmark had the world’s first fat tax but repealed it in January 2013, 15 months after it was enacted, because it had little effect on the consumption of junk food. The poor also depend on junk food, and raising prices on such food negatively affects them the most.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
  
          <p>
            <b>result in</b> ~을 낳다, 야기하다
          </p>
          <p>
            <b>alleviate</b> 완화하다
          </p>
          <p>
            <b>diabetes</b> 당뇨병
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >비만은 한국에서 증가되는 문제이고, 미국과 영국의 공중 보건에 위협이었다. 그래서 한국에서 많은 티비 프로그램은 음식에 관한 것이었고, 더 많은 한국인들의 과식과 건강하지 않은 식생활을 하게 했다 그래서 정크 푸드 세금은 이 문제를 완화하기 위해 필요하다. 대한비만학회는 “비만세”는 비만률을 효과적으로 줄일 수 있고, 더 많은 세수는 사회 서비스에 사용될 수 있다는 것을 발견했다. 해외의 많은 건강 전문가들 또한 그 같은 세금을 비만이 공중보건에 위협적인 존재라고 말하며 찬성한다. 호주의 한 퀸즈랜드 대학의 연구는 20퍼센트의 세금은 16,000건의 2형 당뇨병, 4,400건의 심장병과 1,000건 이상의 뇌졸중을 줄일 수 있고, 매년 수억 달러를 번다고 밝혔다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >비만 그리고 관련 질환들이 한국에서 증가하고 있다는 것에는 의심의 여지가 없지만, 정크푸드 세금을 적용하는 것은 답이 아니다. 유럽의 국가들은 정크푸드 섭취를 줄이기 위하여 “비만세”를 사용하기도 하였는데, 반쯤의 성공을거두거나 만족스런 성공이 얻어지지 않았다. 덴마크는 세계에서 첫 번째로 비만세를 가졌으나, 정크푸드 섭취에 거의 영향을 주지 못하였기에2013년 1월에 폐지되었는데, 이는 법이 시행된 후 15개월 만이었다. 가난한 사람들은 또한 정크푸드에 의존하였고, 이러한 음식의 가격을 올리는 것은 그들에게 가장 부정적인 영향을 끼친다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Do you think eating junk food contributes to a person becoming obese?</li>
            <li>In your opinion, will having “fat tax” help lessen obesity?</li>
            <li>Will implementing junk food tax affect the people? How so?</li>
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
  
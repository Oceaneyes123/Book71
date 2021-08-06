<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/mortar-board-graduation-diploma_53876-47088.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is a College Degree Necessary?
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
      <td class = "lowertable" >Although the labor market has been brutal to young adults during the ongoing economic recession, people with postsecondary education have fared much better than their less-educated peers. In the United States, as of February 2013, the unemployment rate for high school dropouts was 11.2 percent. For high school graduates, that figure was 7.9 percent. For college graduates, it was just 3.8 percent. People who hold bachelor’s degrees also earn more money. According to the U.S. Census Bureau, adults with bachelor’s degrees earn 85 percent more than adults who hadnot advanced beyond high school.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >College Isn't for everyone. After all, there are many different paths to success. For example, a person who wants to become a firefighter is better off taking courses at a fire academy and getting first hand experience than spending thousands of dollars at a four-year institution. These days, there are more and more jobs that don’t require a college degree. A recent study by Brookings Institution, an American think tank, found that half of all high-tech positions of STEM jobs? Those requiring skills in science, technology, engineering, or math are held by employees without a bachelor’s degree. They made, on average, $53,000 a year.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>recession</b> 경기 후퇴, 불경기, 불황
        </p>
        <p>
          <b>post-secondary</b> 중등 과정 후의 교육 ((총칭))
        </p>
        <p>
          <b>dropouts</b> 중퇴자
        </p>
        <p>
          <b>first-hand</b> 직접의(direct); 직접 (체험에 의해서) 얻은, 직접 구입한
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >계속 되는 경기 후퇴 중에 노동시장이 젊은 사람들에게 잔인 하지만 높은 교육을 받은 사람들이 그렇지 못한 또래보다 기회를 더 얻는다. 2013년 2월까지, 미국에서는 고등학교 중퇴자들의 실업률은 11.2 %였다. 고등학교 졸업자들은 7.9%였고, 대학 졸업자들은 3.8%였다. 대학 학위를 갖고 있는 사람들은 또한 더 많은 돈을 번다. 미국 인구 조사국에 따르면, 대학 학위를 가진 사람들은 고등학교 이상의 교육을 받지 못한 사람들 보다 85 % 정도 수입이 더 많다고 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >대학교는 모든 사람들을 위한 것이 아니다. 결국에는, 성공을 위한 길은 여러 가지 이다. 예를 들어, 소방관이 되고 싶은 사람은 4년의 교육 기관에서 많은 돈을 쓰는 것보다는 소방학교에서 강의를 듣고 직접적인 경험을 하는 것이 더 낫다. 요즘에는, 대학 학위를 요구하지 않는 직업이 더욱 많아지고 있다. 미국의 싱크탱크 브루킹스 연구소의 최근 연구는 과학, 기술, 엔지니어링 혹은 수학의 기술을 필요로 하는 주요 직업들의 최첨단의 위치의 반은 대학 학위가 없는 사람들이 책임을 지고 있다는 것을 발견했다. 그들은 평균 일년에 53,000달러를 번다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think that it’s necessary to have a college degree? Why or why not?</li>
          <li>In your opinion, can not having a college degree affect someone’s success in life?</li>
          <li>Do you think that a person’s unemployment is caused by their lack of bachelor’s degree?</li>
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

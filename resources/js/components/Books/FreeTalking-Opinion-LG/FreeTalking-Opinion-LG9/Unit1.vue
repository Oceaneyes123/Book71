<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/word-english-with-globe-wooden-background_1357-127.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should English Education Be Mandatory in Korea?
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
      <td class = "lowertable" >Entertainment around the world is dominated by American culture. By learning English, you can enjoy movies, books, music, television programs, and much more. Some of the greatest artistic minds are native English speakers, and by learning the language, you will be able to read, watch, and listen to some of the most popular works of literature, film, and music.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The education gap between the rich and poor is growing in Korea. Last year, Statistics Korea reported that the richest 20 percent of households spend about six times more than the poorest 20 percent on private education. This basically means that education levels have a strong correlation with income levels. In addition, the whole English-language system is ineffective and problematic. For example, Koreans learn English from elementary school through university for more than five hours a week, on average. However, there are many Koreans who don’t speak English as fluently as they should, when considering the amount of time, money, and effort they spend. This is because English is rarely used in everyday life. “It’s a problem that Koreans see English as a subject for study, without having an opportunity to learn practical usage,” said Han Hak-sung of Kyunghee University.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>dominated</b> (...의) 가장 중요한[두드러지는] 특징이 되다
        </p>
        <p>
          <b>native</b> (사람이) 태어난 곳의
        </p>
        <p>
          <b>correlation</b> 관계
        </p>
        <p>
          <b>ineffective</b> 실효성이 없는
        </p>
        <p>
          <b>problematic</b> 문제
        </p>
        <p>
          <b>practical</b> 타당한, 현실성 있는, 실현 가능한
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >전 세계의 오락은 미국 문화에 의해 지배 당한다. 영어를 배움으로 인해, 당신은 영화, 도서, 음악, 텔레비전 프로그램, 그리고 그 이상의 것들을 즐길 수 있다. 가장 위대한 예술적 정신을 가진 사람들의 몇몇은 영어를 모국어로 사용하는 사람이고 이 언어를 배움으로 인해, 당신은 가장 인기 있는 문학, 영화, 그리고 음악 작품들을 읽고, 보고, 그리고 들을 수 있을 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >한국에서 부자와 가난한 사람들의 교육 격차는 점차 증가하고 있다. 지난 해, 통계청은 가장 부유한 가정의 20%가 가장 가난 한 가정의 20%가 사교육에 지출하는 돈의 6배가 넘는 돈을 사용한다고 보고했다. 이것은 기본적으로 교육 수준이 수입 수준과 강한 상관관계가 있다는 것을 의미한다. 또한, 전체적인 영어 체제가 비효율적이고 문제가 있다. 예를 들어, 한국인들은 초등학교부터 대학교까지 평균 일주일에 5시간 이상 영어를 배운다. 하지만, 그들이 사용한 시간, 돈, 노력을 생각 했을 때 그만큼의 영어를 구사 하지 못한다. 왜냐하면 영어가 일상생활에서 거의 사용되지 않기 때문이다. “한국인들이 실용적인 영어를 배울 기회를 갖지 못하고 영어를 수업 과목으로만 보는 것이 문제이다”라고 경희대의 한학성은 말했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think that it is necessary to study English? Why or why not?</li>
          <li>For you, what are the advantages of being able to speak and understand English?</li>
          <li>In your opinion, do you think that learning English and not being able to use it on a daily basis is a waste of time? Why or why not?</li>
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

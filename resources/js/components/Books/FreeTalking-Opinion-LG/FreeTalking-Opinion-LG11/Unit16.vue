<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/big-family-with-four-daughters-spend-time-home_1157-28729.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Have Big Families?
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
      <td class = "lowertable" >With China’s repeal of the one-child policy, it is clear that small families have caused social problems. In China, the so-called “Little Emperor Syndrome” has left the next generation full of spoiled, petulant children. In fact, this problem has children being pampered to the point of their parents ‘tying their shoes and wiping their bottoms,’ even at the age of 10. Science has proven that large families are often happier. In a five year study by the Edith Cowan University in Australia, statistics showed that parents in a family with many children found their family to be a large caring network. Families with many children learn to share from an early age. With big families, kids with siblings often have better social skills and these families are often happier. Statistically, 66.8% of households with two adults and 3+ children consider themselves happy. Smaller families are far less happy. With the chance to build a happier generation that is not spoiled and self-entitled, we pave the way to a better future.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Big families are a very bad thing for our world. Despite issues with the one child policy, it actually created a kind of social revolution. In China, girls were often treated as inferior. However, with families limited to one child, girls have been raised to have an education and be treated as equals. The world is only growing and families are getting larger in the developing world. This will lead to overcrowding and pollution. Statistically, the human race is consuming resources at a rate that is 30% more than it should. In order to stay sustainable, we need to limit that number. In 2016, 108 million people in the world went without food. If we have large families, we only create more issues. The world is also growing at an exponential rate, with the global population set to increase to 8 billion by 2020. With large families, problems are numerous. With small families, this world could sustain itself and survive.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>repeal</b> 폐지, 폐기
        </p>
        <p>
          <b>social</b> 사회의, 사회적인
        </p>
        <p>
          <b>so-called</b> 소위, 이른바
        </p>
        <p>
          <b>pamper</b> 소중히 보살피다, 애지중지하다
        </p>
        <p>
          <b>statistics</b> 통계, 통계 자료
        </p>
        <p>
          <b>sibling</b> 형제자매
        </p>
        <p>
          <b>revolution</b> 혁명
        </p>
        <p>
          <b>overcrowding</b> 초만원
        </p>
        <p>
          <b>limit</b> 제한하다
        </p>
        <p>
          <b>exponential</b> 기하급수적인
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >중국의 한 자녀 정책의 폐지로, 소가족이 사회 문제를 일으킨 것은 분명하다. 중국에서, 이른바 “소황제 증후군”은 다음 세대에 망쳐지고 버릇없는 많은 어린이들을 남겼다. 사실, 이 문제는 심지어 10세까지 그들의 부모님들이 ‘그들의 신발을 묶고 그들의 엉덩이를 닦는’ 정도로 애지중지 키워진 어린이들을 만들었다. 과학은 대가족들이 종종 더 행복하다고 증명했다. 호주의 에디스 코완 대학의 5년의 연구는 많은 자녀를 가진 부모들은 그들의 가족이 큰 돌보는 관계가 된다는 것을 통계로 보여주었다. 많은 어린이가 있는 가족은 어린 시절부터 나누는 것을 배운다. 대가족과 형제 자매가 있는 어린이들은 종종 더 나은 사회 기술을 가지고 이 가족들은 종종 더 행복하다. 통계적으로, 2명의 어른과 3명 이상의 어린이가 있는 가정의 66.8퍼센트는 그들을 행복하다고 인지한다. 소가족들은 훨씬 덜 행복하다. 버릇이 없지 않고, 자기 중심적이지 않은 더 행복한 세대를 만들 기회를 가지고, 우리는 더 나은 미래를 위해 길을 조성한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >대가족은 우리의 세계에 매우 나쁜 것이다. 한 자녀 정책의 문제에도 불구하고, 그것은 실제로 사회 혁명의 한 종류를 생성했다. 중국에서 소녀들은 자주 열등하게 취급되었다. 하지만, 가족이 한 자녀로 제한됨에 따라 소녀들은 교육을 받고 동등하게 대우받도록 키워졌다. 세계는 성장하고 있고 개발도상국에서 가족들은 점점 커지고 있다. 이것은 과밀거주와 오염을 낳을 것이다. 통계적으로, 인류는 그래야 하는 것보다 30퍼센트나 더 많은 비율로 자원을 소비하고 있다. 지속 가능하게 유지하기 위해, 우리는 그 수를 제한할 필요가 있다. 2016년에, 세계의 1억 800만 명은 음식이 없이 살았다. 만약 우리가대가족을 가진다면, 문제를 더 만들 뿐이다. 세계 인구가 2020년까지 80억으로 증가할 예정으로 세계는 또한 기하급수적으로 증가하고 있다. 대가족이 있으면, 문제는 매우 많다. 소가족으로, 이 세계는 유지되고 생존할 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How many members are there in your family? Do you wish to be a part of a big family?</li>
          <li>What are some of the problems that big families encounter?</li>
          <li>Are smaller families better than larger families? Explain.</li>
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

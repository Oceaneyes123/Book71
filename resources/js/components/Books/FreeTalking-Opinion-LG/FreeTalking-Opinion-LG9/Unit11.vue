
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/economical-research_1098-15688.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should developing nations prioritize environmental protection over economic development?
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
      <td class = "lowertable" >The greatest threats to planet Earth are environmental. Therefore, developing nations, too, must prioritize environmental protection over economic development. The processes of industrialization have created unsustainable economies in many parts of the world. For example, the levels of air pollution in parts of China are rapidly causing health problems for Chinese citizens. Likewise, developing nations must learn from the mistakes of already developed countries, many of which have historically placed economic development above the protection of the environment. Having a developed economy is pointless if that economy exists on an environmentally devastated planet.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Developing nations must prioritize economic production in order to ensure opportunities for its citizens. It is unfair to force developing countries to limit their economic development due to the unsustainable way in which already developed countries may have developed. The responsibility to protect the environment must fall on those nations that are already developed to such an extent that they can prioritize environmental protection without drastically limiting their economic development. Likewise, developed countries should try to help developing nations by giving them environmentally friendly technology and teaching them environmentally friendly policies. </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>industrialization</b> 산업[공업]화
        </p>
        <p>
          <b>unsustainable</b> (동일한 수준·정도 등으로) 지속 불가능한
        </p>
        <p>
          <b>devastated</b> 엄청난 충격을 받은
        </p>
        <p>
          <b>ensure</b> 반드시 …하게[이게] 하다, 보장하다
        </p>
        <p>
          <b>prioritize</b> 우선순위를 매기다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >지구에 대한 가장 큰 위협은 환경적인 문제이다. 그러므로, 개발 도상국 역시 경제 발전보다 환경 보호를 우선시해야 한다. 산업화의 단계들은 세계의 많은 지역에서 지속할 수 없는 경제를 만들었다. 예를 들면, 중국의 공기 오염 수준은 급속하게 중국 국민들의 건강 문제를 야기하고 있다. 마찬가지로, 개발 도상국들은 역사적으로 환경 보호보다 경제 발전을 우선시 했던, 이미 선진국이 된 나라들의 실수로부터 배워야 한다. 만일 그 경제가 환경적으로 황폐화된 지구에 존재한다면, 발전된 경제를 갖는 것은 무의미하다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >개발 도상국들은 자국민의 기회를 보장하기 위해 경제적인 생산을 우선 순위에 두어야 한다. 이미 선진국들이 발전한 지속할 수 없는 방법 때문에, 개발 도상국들에게 경제 발전을 제한하라고 강요하는 것은 불공정하다. 자국의 경제 발전을 철저하게 제한하지 않고 환경 보호를 우선 순위에 놓을 정도로 발전한 선진국들이 환경을 보호하는 책임을 져야 한다. 마찬가지로, 선진국들은 환경 친화 기술을 전수하고 환경 친화 정책들을 알려주어, 개발 도상국들을 도와야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Which do you think is more important? Environmental development or economic development? Why?</li>
          <li>Should countries that strive for economic development be responsible for environmental development as well? Why or why not?</li>
          <li>Do you think economic development is harmful to our environment? Why or why not?</li>
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

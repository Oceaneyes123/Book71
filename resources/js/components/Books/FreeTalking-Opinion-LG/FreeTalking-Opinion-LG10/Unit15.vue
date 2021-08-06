<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/shot-sun-eye-metropolis-urban_1112-964.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">How high should we go?
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
      <td class = "lowertable" >Many fall in love with high-rise buildings and skyscrapers because they offer breathtaking views of skylines. Tall buildings are also useful for densely populated cities like Seoul and Tokyo since land space is quite limited. Engineers claim that tall buildings are safer than low ones, mostly because tall buildings are known to absorb even the worst shocks from earthquakes, according to The New York Times. While this may be true, high-rise buildings still present numerous potential hazards for people. Ms. Tsubuku, a former tenant of Tokyo’s City Towers Toyosu, goes as far as saying that “high-rise buildings are not designed for people to live in.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Earthquakes have been occurring around the world for centuries. Yes, it’s tragic to hear that South Koreans had to experience a natural disaster without even being prepared for it. However, is it necessary to limit the heights of buildings when we can simply construct them with stronger foundations to withstand such disasters? Especially in a densely populated city like Seoul, putting a limit on buildings could cause other problems, like insufficient accommodations and pricey housing.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>skyscraper</b> 고층 건물
        </p>
        <p>
          <b>limited</b> 제한된
        </p>
        <p>
          <b>hazard</b> 위험
        </p>
        <p>
          <b>natural disaster</b> 자연 재해
        </p>
        <p>
          <b>densely</b> 밀집하여, 빽빽하게
        </p>
        <p>
          <b>accommodations</b> 숙박 시설
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >많은 사람들은 고층 건물들과 마천루들이 숨막히는 듯한 스카이라인 전망을 제공하기 때문에 그것들에 반한다. 고층 빌딩들은 또한 토지 공간이 아주 한정적이기 때문에 서울과 도쿄와 같은 인구과밀도시들에 유용하다. 엔지니어들은 고층건물들이 저층건물들보다 더 안전하다고 주장하고 있는데, 뉴욕타임즈에 따르면 대부분 고층빌딩들이 지진으로부터 최악의 충격을 받아도 그것들을 흡수하는 것으로 알려져 있기 때문이라고 한다. 이것이 사실일지라도, 고층빌딩들은 사람들에게 다수의 잠재적인 위험을 여전히 야기한다. 도쿄 씨티타워 토요수에서 과거 살았던 임차인인 츠브쿠 씨는 심지어 “고층건물들은 사람들이 살도록 디자인된 곳이 아니다”라고 말한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >지진은 수 세기 동안 발생했다. 물론, 한국인들이 자연 재난을 아무런 준비 없이 겪었다는 뉴스를 듣는 것은 비극적이다. 하지만, 그렇다고 해서 그러한 재난들을 견딜 수 있게 하기 위해 건물의 토대를 더욱 강력하게 만들 수 있는 데 빌딩 고도제한을 해야 하겠는가? 특히 인구가 밀집된 서울과 같은 도시에서 빌딩 고도제한을 시행하면 숙소 부족과 비싼 집값 문제와 같은 다른 문제들을 야기시킬 수 있을 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What is the tallest place or building that you have visited?</li>
          <li>Do you think it is safe to go as high as 70 floors for residential buildings?</li>
          <li>Should there be a limit as to how tall can high-rise buildings go?</li>
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

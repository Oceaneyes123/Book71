<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/cctv-security-camera_1359-621.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Can a camera keep us safe?
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
      <td class = "lowertable" >Turn on the news and there is at least one story about surveillance cameras being used as a crucial piece of evidence. They may not look like they're from sci-fi movies, but CCTVs are able to capture precise moments of crime as well as deter both petty and serious crimes from happening. Major cities like London, New York, and Chicago have already installed over 4,000 closed-circuit televisions. Even smaller cities, such as Boston, are looking to set up more CCTVs around the city as “the power of these systems help solve crimes, causing many to call for even more cameras,” according to CNN. Also, Washington, D.C.-based think tank Urban Institute stated, “Cameras were linked to reduced crime, even beyond the areas with camera coverage.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Millions of CCTVs are installed in streets and buildings around the world with the goal of reducing crime and increasing public safety. However, sometimes what’s put in place for good intentions may not always yield the anticipated results. In fact, CCTVs actually “solve very few crimes, and their deterrent effect is minimal,” according to The Guardian. London, for example, is recognized as the world’s leading user of surveillance cameras with about 500,000 of them in the city alone. According to conventional wisdom, it should be the safest city, but it is not. Technology has its limitations, making these cameras generally ineffective.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>crucial</b> 결정적인
        </p>
        <p>
          <b>capture</b> 포착하다
        </p>
        <p>
          <b>call for</b> (공식적으로) 요구하다
        </p>
        <p>
          <b>yield</b> (수익, 결과를) 내다
        </p>
        <p>
          <b>deterrent</b> 제지하는, 억제하는
        </p>
        <p>
          <b>minimal</b> 아주 적은, 최소의
        </p>
        <p>
          <b>limitation</b> (수익, 결과를) 내다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >뉴스를 틀면 소식 중 최소한 1개는 감시카메라가 중요한 단서가 되었다는 내용이다. SF 영화에 나오는 것과는 조금 다르지만, CCTV은 정확히 범죄 현장을 포착하는 것뿐만 아니라 사소하고 심각한 범죄들이 생기는 것을 모두 막을 수 있다. 런던, 뉴욕, 시카고와 같은 주요 도시에는 이미 4천 개 이상의 폐쇄회로 텔레비전들을 설치했다. CNN에 의하면, 그보다 작은 도시인 보스톤은 카메라 시스템이 범죄를 해결하는 데 많은 도움이 되어 CCTV를 더 설치하자는 요구를 할 것”이라고 한다. 또한, 그리고 워싱턴 D.C.에 위치한 싱크탱크 어번인스티튜트는 “카메라가 작동할 수 없는 지역까지도 범죄 행위가 줄었다” 고 하였다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >수백만 대의 CCTV들이 범죄를 줄이고 치안을 확대한다는 목표로 전 세계의  거리들과 빌딩들에 설치되었다. 하지만, 때때로 좋은 의도를 위해 설치되었던 것이 항상 기대했던 결과들을 내놓지는 않는다. 사실, 가디언지에 따르면 CCTV들은 “아주 적은 수의 범죄를 해결했고, 억제 효과는 경미했다”고 한다. 예를 들어, 런던은 그 도시 하나에만 약 50만대의 감시카메라의 사용하고 있어 세계 최고의 감시카메라 국가로 여겨진다. 사회적 관습에 따르면, 런던이 가장 안전한 도시가 되어야 하겠지만 그렇지 않다. 기술은 그 한계가 있어 이러한 카메라들을 일반적으로 효과적이지 않게 만든다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think CCTV cameras are helpful? Why or why not?</li>
          <li>Does a CCTV camera provide security?</li>
          <li>Should everyone have  CCTV cameras installed in their houses?</li>
        </ol>

      </div>

    </div>


  </v-layout>
</v-container>
</div>



</template>



<script>
export default {
  props: ["fontSize"],

  data() {
    return {
      showTitle: false,
    };
  },

  mounted() {
    this.showTitle = true;
  },

  beforeMount() {},

  methods: {},

  watch: {
    fontSize(current, old) {
      console.log(current, "current");
      console.log(old, "previous");
    },
  },
};
</script>

<style scoped lang="css">
</style>

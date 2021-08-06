<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/asian-boy-playing-tablet-his-mother-frustrated_1249-486.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Tablets Replace Textbooks in the Classrooms?
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
      <td class = "lowertable" >The benefits of using tablets as an education tool are endless. Previous studies have found that tablets help students learn more material faster. In addition, according to a survey by the Public Broadcasting Service, 77 percent of teachers found that technology “increases student motivation to learn.” Another advantage is that tablets help students better prepare for an increasingly tech-savvy world.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Using tablet PCs may have several benefits, but there are also many disadvantages as well. Tablets can cause distraction in the classrooms,for example. Students may pay attention to games, emails, and other websites instead of their teachers. A majority of teachers believe that “today’s digital technologies are creating an easily distracted generation with short attention spans.”</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>technology</b> (과학) 기술
        </p>
        <p>
          <b>tech-savvy</b> 테크놀로지, 즉 최신기술에 능통한'
        </p>
        <p>
          <b>distraction</b> 산만하다
        </p>
        <p>
          <b>digital technology</b> 디지털 기술
        </p>
        <p>
          <b>attention span</b> 주의 지속 시간
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >교육적인 도구로써의 태블릿 사용의 혜택은 끝이 없다. 이전의 조사에서 태블릿은 학생들이 수업내용을 더 빨리 배울 수 있게 돕는다고 밝혀졌다. 또한, 공공방송망의 조사에 따르면, 77%의 교사들이 이러한 기술이 학생들의 배우고자 하는 동기부여를 증가시킨다고 한다. 또 다른 장점은 태블릿은 학생들이 점점 더 기술을 능숙하게 사용하는 세상에 잘 대비 할 수 있게 한다는 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >태블릿 PC를 사용하는 것은 여러 가지 장점이 있을 것이다. 하지만 많은 단점도 있다. 태블릿은 예를들면 교실의 산만함을 야기 할 수 있다. 학생들은 선생님 대신 게임, 이메일, 그리고 다른 웹사이트에 집중 할 수 있다. 대부분의 선생님들은 “오늘날의 디지털 기술이 짧은 주의력으로 쉽게 산만해지는 세대를 만들었다”고 믿고 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think using tablets are more advantageous over using textbooks? Why or why not?</li>
          <li>Can you consider using tablets during class as a distraction? Why?</li>
          <li>Should we consider relying on technology more in schools? Why or why not?</li>
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

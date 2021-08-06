<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/hands-with-laptop-virtual-world-map_1232-876.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">The Use of the Internet and Plagiarism
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
      <td class = "lowertable" >Plagiarism is, and has probably always been, an endemic. Although it is more noticeable now that technology - particularly the internet- has been able to catch students out. To give an example, 49 percent of Cambridge University students surveyed by a student paper admitted to having committed some form of plagiarism during their courses. Each of these students would have signed a form promising not to plagiarize (this I know from experience!) during their time at the university. By this token, there is no way that's ban on the use of the internet by students could alleviate the problem, even if it was scrutinized in the same way. Furthermore, such a ban would inevitably create its own plagiarism: students would continue to use internet sources but since they are not allowed, they would plagiarize the information rather than credit it properly.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Certain elements of the internet are permanent, such as news sites and online journal sites, just as various elements of written material such as memos and diaries are impermanent. The problem is a matter of discrimination rather than of the medium. Is it not better to experience these fleeting moments of history then leave them condemned to an eternity in the waste paper basket?</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>plagiarism</b> 표절
        </p>
        <p>
          <b>alleviate</b> 완화하다
        </p>
        <p>
          <b>scrutinized</b> 면밀히 조사하다
        </p>
        <p>
          <b>permanent</b> 영구적인
        </p>
        <p>
          <b>fleeting</b> 순식간의, 잠깐 동안의
        </p>
        <p>
          <b>condemned</b> 유죄 판결을 받다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >그렇다. 표절은 아마도 이전에도 그리고 지금도 고질적인 문제였다. 비록 그것이 특히 인터넷이라는 첨단 기술로 인해 더욱 눈에 띄게 되었다고 해도, 인터넷은 표절을 하는 학생들을 잡아낼 수 있었다. 예를 들면, 캠브리지 대학 학생의 49퍼센트가 시험을 보는 동안 어떤 형태로든 표절을 한 적이 있음을 시인했다. 이 학생들 개개인은 대학시절 동안 표절을 하지 않겠다는 약속을 하는 용지에 서명했을 것이다. (이것은 나도 경험으로 안다!) 이것을 보아도, 이 문제를 경감시킬 수 있는 인터넷을 사용하는 것을 금지할 수 있는 방법은 없다, 비록 같은 방법으로 조사 되었다고 하더라도 말이다. 더군다나, 그러한 금지는 표절을 만들어 낼 수밖에 없다: 학생들은 인터넷 자료를 계속 사용할 것이지만, 그것이 허락되지 않기 때문에 그들은 (그들이 참고한 자료의) 출처를 밝히기 보다는 그 정보를 표절할 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >메모나 다이어리와 같은 종이에 쓰여진 자료들은 영구하지 않지만, 뉴스 사이트나 온라인 잡지 사이트와 같이 어떤 인터넷의 요소들은 영구하다. 문제는 미디어라기 보다 차별의 문제이다. 역사의 순간을 휴지통에 영원히 비난 받게 버려두는 것 보다는 경험하는 것이 낫지 않은가?</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Is the use of internet resources for a research project considered plagiarism? Why or why not?</li>
          <li>Do you think plagiarism should be considered as a crime? Why or why not?</li>
          <li>Is cheating and plagiarism the same?</li>
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

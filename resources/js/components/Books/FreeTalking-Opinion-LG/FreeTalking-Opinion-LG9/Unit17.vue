<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/close-up-student-working-with-laptop-dictionary_23-2148389050.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Electronic dictionaries are better than paper dictionaries
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
      <td class = "lowertable" >Electronic dictionaries are better than paper dictionaries. Electronic dictionaries provide definitions quickly and easily. It takes nearly seven times longer to look up a word in a paper dictionary than an electronic dictionary. That is why electronic dictionaries are particularly useful during conversations in a foreign language. Sometimes we need to quickly search for a word to communicate with the other person. This is only possible with electronic dictionaries. Furthermore, electronic dictionaries are easier to use because they are often already installed on cell phones.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Paper dictionaries are better than electronic dictionaries. Students often pretend like they are using the electronic dictionary on their phones during school. However, they are actually texting with their friends or playing games. Also, it is too easy and quick to search words on electronic dictionaries. Therefore, people do not bother to memorize and learn new words. In comparison, people actually learn new vocabulary when using the paper dictionary because it takes longer to look up words.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>definition</b> (특히 사전에 나오는 단어나 구의) 정의
        </p>
        <p>
          <b>look up</b> (사전·참고 자료·컴퓨터 등에서 정보를) 찾아보다
        </p>
        <p>
          <b>communicate</b> 연락을 주고받다, 의사소통을 하다; (정보 등을) 전달하다
        </p>
        <p>
          <b>install</b> (컴퓨터에 새 프로그램을) 설치하다
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

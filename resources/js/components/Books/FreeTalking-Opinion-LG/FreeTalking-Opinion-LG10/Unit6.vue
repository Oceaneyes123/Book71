<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/beautiful-young-woman-reading-book-train_1301-5332.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">E-books Are The Best Way To Read
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
      <td class = "lowertable" >The digital revolution has transformed the way people read books for the better. Imagine a smartphone or tablet containing a huge library of books that can go wherever the reader wants. No need to go to a library or bookstore, one can just download a desired book. The technology is also eco-friendly in that no paper is needed, thus it helps to save the planet. And what about the fate of used books? They take up space at homes and other facilities, but with e-books, no space is needed. A 2014 study published in the journal Library & Information Science Research also found that tenth graders preferred e-readers, and youths disinterested in reading were attracted to e-books. So the technology can encourage reading. Plus e-readers can be customized to a reader’s tastes like adjusting the font, letter size, and lighting. E-books are also good for people with disabilities.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >While e-books do have advantages, that doesn’t mean they’re better than print books. Small-scale studies have found that people tend to remember more from reading print books than e-books. The turning of pages was found to be a sign of tangible progress for the reader, which raised reading satisfaction. Technology is also why e-readers can pose problems for people. For example, reading an ebook at night can affect the quality of sleep and strain the eyes due to the lighting. A study also found that production of melatonin, a hormone that induces sleep, is negatively affected when an ebook is read at night. In addition, reading online can lead one to skim rather than perform slow reading, meaning an inferior reading experience and lower comprehension. The numerous benefits of slowly reading a print book, per one study, include reducing stress and improving concentration. So in this case, tradition trumps tech.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>download</b> 다운로드하다
        </p>
        <p>
          <b>used book</b> 중고책
        </p>
        <p>
          <b>disinterested</b> 무관심한
        </p>
        <p>
          <b>customized</b> 개개인의 요구에 맞춘
        </p>
        <p>
          <b>taste</b> 기호
        </p>
        <p>
          <b>adjust</b> 조정하다
        </p>
        <p>
          <b>advantage</b> 장점
        </p>
        <p>
          <b>tend</b> ~하는 경향이 있다
        </p>
        <p>
          <b>tangible</b> 분명히 실재하는
        </p>
        <p>
          <b>strain</b> 무리하게 사용하다
        </p>
        <p>
          <b>skim</b> 훑어보다
        </p>
        <p>
          <b>concentration</b> 정신 집중
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >디지털 혁명은 사람들이 책을 읽는 방식을 더 나은 쪽으로 바꾸어 놓았다. 독자가 원하는 어느 곳이든 가지고 갈 수 있는 거대한 책들을 포함한 스마트 폰 혹은 태블릿을 상상해 보십시오. 도서관 혹은 서점에 갈 필요 없이, 사람들은 원하는 책을 다운 받을 수 있다. 그 기술은 종이를 필요로 하지 않고 또한 환경 친화적이어서 지구를 구하는 데 도움을 준다. 그러면 중고책의 운명은 어떻게 되는가? 그것들은 집과 다른 시설들에 자리를 차지하지만, 전자책은 공간이 필요가 없다. 2014년 도서관과 정보 과학 연구 저널에 발표된 연구는 또한 10학년 학생은 전자책을 선호했고, 책에 흥미가 없는 어린 학생들은 전자책에 이끌렸다. 그래서 그 기술은 독서를 권장할 수 있다. 게다가 전자책 독자들은 폰트, 글자 크기, 그리고 밝기 조정과 같이 독자의 기호로 자기 취향에 맞게 바꿀 수 있다. 전자책은 또한 장애를 지닌 이들에게도 또한 좋다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >전자책이 이점이 있긴 하지만, 그것이 종이책보다 좋다는 것을 의미하진 않는다. 소규모의 여러 연구는 사람들이 전자책보다 종이책을 읽는 것으로부터 더 많은 것을 기억할 수 있다고 발견하였다. 페이지를 넘기는 것은 독자에게 명백한 진보의 표시라고 발견되었는데, 이것은 독서로부터 오는 만족을 늘릴 수 있다. 기술은 또한 전자책 단말기가 사람들에게 문제를 일으킬 수 있는 이유이다. 예를 들어, 전자책을 밤에 읽는 것은 수면의 질에 영향을 미치고, 조명으로 인해 눈에 스트레스를 줄 수 있다. 한 연구는 또한 잠을 유도하는 호르몬인 멜라토닌의 생산이 전자책을 밤에 읽을 때 부정적인 영향을 받는다는 것을 발견하였다. 게다가, 온라인으로 읽는 것은 천천히 읽는 것보다 훑어보도록 만드는데, 이것은 질이 낮은 독서 경험과 더 낮은 이해를 의미한다. 한 연구에 따르면, 종이책을 천천히 읽는 수 많은 이점은 스트레스를 줄이고 집중력을 높이는 것을 포함한다. 따라서, 이 문제의 경우, 전통이 기술을 능가한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Are you a fan of reading? What genre do you usually read?</li>
          <li>Do you read books on paperback or use an ebook?</li>
          <li>What are the benefits in reading an ebook?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/social-media-troll-harassing-people-social-media_53876-98441.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Internet Trolls Be Policed?

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
      <td class = "lowertable" >Free speech is one thing, but people are being harassed, threatened, and intimidated online by Internet trolls. This needs to be stopped, especially if people feel like they’re in danger. In 2012, Arizona passed House Bill 2549, which made being annoying, offensive, provocative online illegal. Other countries seem to be following suit. British politicians are debating new laws that would require websites to reveal the identities of trolls, and Italian prosecutors are threatening action against trolls and social media websites.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >People should have the right to say whatever they want without interference from the government. Internet anonymity allows people to exercise their right to free speech, which, in the United States, is protected by the First Amendment of the U.S Constitution.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>free speech</b> 언론의 자유.
        </p>
        <p>
          <b>internet trolls</b> 인터넷 트롤((사소한 문제로 인터넷에서 논쟁하는 사람))
        </p>
        <p>
          <b>provocative</b> 도발적인, 화[부아]를 돋우려는
        </p>
        <p>
          <b>interference</b> 간섭, 참견, 개입, 방해
        </p>
        <p>
          <b>anonymity</b> 익명(성)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >발언권의 자유가 한가지 이유이긴 하지만 사람들이 인터넷의 유해물 때문에 괴롭힘을 당하고, 위협을 당하고 있다. 이것은 멈춰줘야 하고, 특별히 만약 사람들이 그들이 위험에 처해 있다고 느낀다면 더욱 더 그러하다. 2012년, 아리조나는 온라인 상의 짜증스럽거나, 불쾌하거나, 자극적인 것들을 불법화 시키는 법안을 통과 시켰다. 다른 나라들도 이것을 따르는 것 같다. 영국의 정치인들은 유해물을 올린 사람들의 신원을 밝히도록 하자는 새로운 법안에 대해 논의하고 있고, 이탈리아의 검찰은 유해물을 올리는 사람들과 소셜 미디어 사이트들에 대항해 위협적인 태도를 보이고 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >사람들은 정부의 개입 없이 그들이 원하는 것을 말 할 권리가 있다. 인터넷의 익명성은 미국헌법 제 1조에 의해 보호 받는 법인 사람들이 자유롭게 말 할 수 있는 권리를 행사 할 수 있게 허락한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What can you say about the behavior of internet trolls?</li>
          <li>When you hear “free speech” what comes into your mind?</li>
          <li>Do you think we should be responsible for whatever we post online? Why or why not?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/hand-drawn-illustrations-social-media_1134-78.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Social media is harmful
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
      <td class = "lowertable" >Too many students are sharing personal information online. These students are reducing the amount of privacy that they and their families have. Posting so much information has made it easier for bad people to find information about students online. Likewise, students are too obsessed with social media. Many students check Facebook multiple times a day. In addition, the Twitter hashtag has become a part of normal language. All of this is proving that social media is changing society for the worse.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Social media is allowing people to stay connected in a way that was never possible before. Instead of having to call each other, you can log on and chat or see pictures that your friends have posted online. This is very helpful for people who live far away from one another. Likewise, social media has made it possible for older people to reconnect with old friends. Before, people had to hope to run into someone whom they had not seen in many years. Today anyone can go online and see if someone who they remember has a social media account.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>reduce</b> (규모·크기·양 등을) 줄이다[축소하다], (가격 등을) 낮추다[할인/인하하다]
        </p>
        <p>
          <b>obsess</b> (어떤 생각이 사람의 마음을) 사로잡다, … 생각만 하게[…에 집착하게] 하다
        </p>
        <p>
          <b>hashtag</b> 해시태그
        </p>
        <p>
          <b>reconnect</b> 다시 연결되다[하다]
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >너무 많은 학생들이 온라인에서 개인 정보를 공유하고 있다. 이런 학생들은 그들과 가족들이 가지고 있는 사생활의 양을 줄이고 있다. 매우 많은 정보를 게시하는 것은 나쁜 사람들이 학생들에 관한 정보를 온라인에서 더욱 쉽게 찾도록 만들었다. 또한, 학생들은 소셜 미디어에 너무 집착한다. 많은 학생들을 매일 여러 번 페이스북을 확인한다. 게다가, 트위터의 해시태그는 일반 언어의 일부가 되었다. 이 모든 것이 소셜 미디어가 사회를 더 나쁜 방향으로 바꾸고 있다는 것을 증명하고 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >소셜 미디어는 사람들이 전에는 결코 가능하지 않았던 방식으로 연결되도록 한다. 서로에게 전화하는 것 대신, 당신은 로그온하여 채팅을 하거나 당신의 친구들이 온라인에 게시한 사진들을 볼 수 있다. 이것은 서로에게서 멀리 떨어져 사는 사람들에게 매우 도움이 된다. 또한, 소셜 미디어는 나이가 든 사람들이 옛 친구들과 다시 연결되는 것을 가능하게 해준다. 이전에, 사람들은 여러 해 동안 만나지 못했던 사람을 우연히 만나기를 바랬다. 오늘날 누구나 온라인에 접속하여 그들이 기억하는 사람이 소셜 미디어 계정을 가지고 있는지를 알아볼 수 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you have a social media account? If yes, do you think it’s necessary to have one?</li>
          <li>Do you think social media can cause harm to people? Give an example.</li>
          <li>In your opinion, how can we use social media in a positive way?</li>
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

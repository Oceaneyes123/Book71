<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/portrait-beautiful-happy-teenage-girl-surfing-internet-watching-video-online-using-portable-computer-home-while-sad-mother-sitting-her_343059-494.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Filter What We Watch?
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
      <td class = "lowertable" >According to the Washington Post, UCLA’s Higher Education Research Institute recently conducted a study finding 71% of students in a 2015 survey agreed colleges should prohibit racist and offensive speeches on campus. Censorship is a responsibility of those in authority for the common good. It protects people, especially children, from violence and hate. As the world we live in is becoming more connected with the Internet accessibility, people are tuning into current events at a younger age. It is inevitable that the happenings of our world will include information that could be harmful to children. Therefore, producers of content need to be held accountable as they influence the minds of young people around the world.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The United Nations’ official stance on media censorship is this: “Ensuring freedom for the media around the world is a priority. Independent, free and pluralistic media are central to good governance in democracies that are young and old.” It has been agreed upon by representatives from countries all over the world that media censorship should not be encouraged. The media is a necessary part of society, and without it the people have no power against those in authority over them. By being the voice of the world’s citizens, the media keeps governments honest and accountable.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>racist</b> 인종차별주의자
        </p>
        <p>
          <b>common good</b> 공익
        </p>
        <p>
          <b>current</b> 현재의
        </p>
        <p>
          <b>inevitable</b> 불가피한
        </p>
        <p>
          <b>accountable</b> 책임이 있는
        </p>
        <p>
          <b>pluralistic</b> 다원론의, 다원적인
        </p>
        <p>
          <b>governance</b> 통치
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >워싱턴포스트에 따르면, UCLA의 고등교육연구소는 최근 2015년 설문조사에서 71%의 학생들이 대학에서 인종차별적이고 공격적인 연설을 금지해야 한다는 것에 동의했다는 것을 발견한 연구를 실시하였다. 검열은 공공의 이익을 위한 당국의 책임이다. 그것은 사람들, 특히 어린아이들을 폭력과 혐오로부터 보호한다. 우리가 살고 있는 세상이 인터넷 이용을 통해 더욱 연결되어 감에 따라, 사람들은 더 어린 나이에 지금 일어나고 있는 사건을 시청하고 있다. 세상에서 일어나는 일 중에는 어린이에게 해로울 수도 있는 정보가 포함될 것은 불가피하다. 따라서, 콘텐츠 제작자들은 세상 젊은이들의 정신에 영향을 주기 때문에 책임을 물어야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >미디어 검열에 대한 UN의 공식 입장은 이렇다: “세상 미디어의 자유를 보장하는 것은 최우선이다. 독립적이고, 자유롭고, 다원적인 미디어는 젊고 오랜 민주주의에서의 좋은 통치에서 중심이 된다.” 미디어 검열이 권장되지 않아야 한다는 것에 전세계 국가의 대표들이 동의해 왔다. 미디어는 사회의 중요한 부분이고, 미디어 없이는 사람들이 자신에게 권위를 행사할 수 있는 사람들에 대항할 힘이 없다. 세상 시민들의 목소리가 됨으로써, 미디어는 정부가 정직하고 책임감 있게 유지한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you watch television often? What do you usually watch?</li>
          <li>What are the advantages or disadvantages of filtering these shows?</li>
          <li>Do you think movies and TV shows should be censored? Why or why not?</li>
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

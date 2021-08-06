
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/mix-raced-trainees-working-computer-public-library_74855-2048.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Do We Still Need Public Libraries?
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
      <td class = "lowertable" >Public libraries are an essential facility for our society and are a necessary resource for all citizens. Public libraries are more than just a place to find and borrow books. They are important for storing information, important historical documents, and providing a space for people to study. Although the internet has become a great and powerful tool for people to acquire knowledge, there is still a need for libraries to hold physical copies of documents and books for the public to access. Libraries are just as essential to education as schools. They also allow people to continue studying long after they’ve graduated from high school or university. As most libraries are free to use for citizens, the cost of using a library is considerably cheaper than paying for an internet connection. Libraries also conduct important education programs that help people study English, learn new hobbies, or job skills. According to the American Library Association, 73 percent of public libraries in the U.S. assisted people with finding employment. Library programs also increase the community spirit within a neighborhood and encourage people to meet and network in a positive way. This shows that libraries are essential facilities that still play an important role in today’s society.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Due to widespread internet access and technological developments, public libraries are no longer relevant in society. As most information can be found online and from the comfort of one’s own home, there is no need to go to a public library anymore. Through the internet, people are able to find information faster and the information is always up to date. Libraries tend to hold many old books and historical documents. As time goes by, this information can become irrelevant due to the nature of our changing world. This is why information on the internet is far superior to the information held in a library. People also don’t use libraries very often anymore. The U.K. newspaper The Guardian reported a 10 percent drop in visitors to U.K. libraries from 2006 to 2016. As people continue to use the internet for research and information, this number is only set to increase in the future. Although libraries are free for citizens to use, they are not free for the government and its taxpayers who must provide the money to fund them. If we weigh up the cost of libraries with how much they are actually used, it doesn’t seem like a worthy investment. In this day and age, public libraries are no longer necessary.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>powerful</b> 강력한
        </p>
        <p>
          <b>information</b> 정보
        </p>
        <p>
          <b>research</b> 연구
        </p>
        <p>
          <b>necessary</b> 필수적인
        </p>
        <p>
          <b>facility</b> 시설
        </p>
        <p>
          <b>purpose</b> 목적
        </p>
        <p>
          <b>education</b> 교육
        </p>
        <p>
          <b>irrelevant</b> 무관한
        </p>
        <p>
          <b>superior</b> 우수한
        </p>
        <p>
          <b>often</b> 자주
        </p>
        <p>
          <b>taxpayer</b> 납세자
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >공공도서관은 우리 사회의 필수 시설이며 모든 시민에게 필요한 자원입니다. 공공도서관은 단순히 책을 찾고 빌리는 곳 이상의 역할을 합니다. 공공도서관은 정보와 중요한 역사적 문서를 저장하고 사람들이 공부할 수 있는 공간을 제공하는 데 중요한 역할을 합니다. 인터넷이 사람들이 지식을 습득할 수 있는 위대하고 강력한 도구가 되었음에도 불구하고, 도서관은 여전히 대중이 접근할 수 있도록 문서와 책의 물리적 사본을 보관할 필요가 있습니다. 도서관은 학교만큼이나 교육에 필수적입니다. 도서관은 또한 사람들이 고등학교나 대학교를 졸업한 후에도 오랫동안 계속 공부할 수 있도록 합니다. 대부분의 도서관은 시민들이 무료로 이용할 수 있기 때문에, 도서관 이용 비용은 인터넷 연결 비용보다 훨씬 저렴합니다. 도서관은 또한 사람들이 영어 공부, 새로운 취미 또는 직업 기술을 배우는 데 도움이 되는 중요한 교육 프로그램을 제공합니다. 미국 도서관 협회에 따르면, 미국 공립 도서관의 73%가 사람들의 취업을 도왔습니다. 도서관 프로그램은 또한 이웃 내에서 공동체 정신을 향상시키고 사람들이 긍정적인 방식으로 만나고 네트워크를 형성하도록 장려합니다. 이것은 도서관이 오늘날 사회에서 여전히 중요한 역할을 하는 필수 시설임을 보여줍니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >광범위한 인터넷 접근과 기술 발전으로 인해 공공도서관은 더 이상 사회와 관련이 없습니다. 대부분의 정보는 집에서 편안하게 온라인으로 찾을 수 있으므로 더 이상 공공도서관에 갈 필요가 없습니다. 인터넷을 통해 사람들은 정보를 더 빨리 찾을 수 있고 인터넷에서 제공되고 있는 정보는 항상 업데이트가 되고 있습니다. 도서관에는 오래된 책과 역사 문서가 많이 보관되는 경향이 있습니다. 시간이 지남에 따라, 이러한 정보는 변화하는 세상의 특성으로 인해 무의미해질 수 있습니다. 이것은 인터넷에 있는 정보가 도서관에 있는 정보보다 훨씬 우수한 이유입니다. 사람들은 또한 더 이상 도서관을 자주 이용하지 않습니다. 영국 신문 더 가디언즈는 2006년에서 2016년 사이 영국 도서관 방문객이 10% 감소했다고 보도했습니다. 사람들이 연구와 정보를 위해 인터넷을 계속 사용하고 있기 때문에 도서관 방문객 감소율은 앞으로 더 늘어날 것입니다. 비록 도서관은 시민들이 무료로 사용할 수 있지만, 도서관 운영에 필요한 자금을 제공해야 하는 정부와 납세자들에게는 무료가 아닙니다. 도서관의 비용과 실제 사용량을 비교해보면 가치 있는 투자는 아닌 것 같습니다. 이 시대에 공공도서관은 더 이상 필요하지 않습니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you like going to public libraries? How often do you go there?</li>
          <li>What effect has the internet had on public libraries? Is it still necessary to have physical libraries?</li>
          <li>Will public libraries become obsolete? Why or why not?</li>
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

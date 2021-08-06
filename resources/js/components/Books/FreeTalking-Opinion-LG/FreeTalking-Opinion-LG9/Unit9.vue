<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/business-situation-job-interview-concept-job-seeker-present-resume-managers_1421-78.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">A college degree is a must for getting a job
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
      <td class = "lowertable" >A college degree is a must for getting a job. In order to have a successful career, it is essential to graduate from college. All the best and highest-paying jobs require a college degree and some professions require even more education, such as doctors and lawyers. Also, all our education until high school is general. College is where we learn knowledge about a specific subject. It is where we gain the tools and knowledge to work in a certain field.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >A college degree is not a must for getting a job. There are many great jobs that do not require college degrees in the United States. What would we do if we did not have bakers to make delicious breads and cakes, construction workers to build structures, or dancers to perform at theaters? All these people contribute greatly to society. Korea has too many college graduates, and it cannot offer jobs to all of them. More people should pursue careers that do not require a college degree.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>essential</b> 본질[근본]적인
        </p>
        <p>
          <b>profession</b> (특히 많은 교육이 필요한 전문적인) 직업[직종]
        </p>
        <p>
          <b>contribute</b> 기부[기증]하다
        </p>
        <p>
          <b>pursue</b> 추구하다, (어떤 일을 어느 정도의 기간을 두고) 밀고 나가다[해 나가다]
        </p>
       </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >대학교 학위는 직업을 갖기 위해 반드시 있어야 한다. 성공적인 직업을 가지기 위해서는, 대학교를 졸업하는 것이 필수이다. 가장 좋고 가장 보수가 많은 모든 직업은 대학교 학위를 요구하고 의사나 변호사 같은 어떤 직업은 훨씬 더 높은 교육을 요구한다. 또한, 고등학교까지의 모든 교육은 보편적이다. 대학은 우리가 구체적인 과목에 대해 지식을 배우는 곳이다. 그것은 우리가 특정한 분야에서 일하기 위해 필요한 도구와 지식을 얻는 곳이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >대학교 학위는 직업을 갖기 위해 반드시 있어야 하는 것은 아니다. 미국에는 대학교 학위를 요구하지 않는 많은 멋진 직업이 있다. 맛있는 빵과 케이크를 만드는 제빵사, 건물을 짓는 공사장 인부, 또는 극장에서 공연하는 댄서들이 없다면 우리는 어떻게 할 것인가? 이 모든 사람들은 사회에 엄청나게 기여한다. 한국은 너무 많은 졸업생이 있고, 그들 모두에게 직업을 제공할 수는 없다. 더 많은 사람들이 대학교 학위를 요구하지 않는 직업을 찾아야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Should a degree in college be the basis for hiring a person for a job? Why?</li>
          <li>In your opinion, what professions don’t require a college degree?</li>
          <li>Do you agree that a college degree defines a person’s success on their chosen career path? Why or why not?</li>
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

<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/woman-kid-playing-tennis_23-2148218656.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Students should be required to play extracurricular sports
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
        <td class = "lowertable" >Students should play extracurricular sports. Sports are not only fun to play, but also beneficial because students can learn alot from participating on a sports team. These benefits can range from getting exercise to meeting friends. In addition, sports are a healthy way for students to engage in competition. When students have a healthy way to compete with each other, they fight less at school. Competition also teaches students to work hard to succeed.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Students should not be forced to play on sports teams after school. Today, students are too busy to waste time playing sports. Instead,students could spend time learning at private academies. Learning is more important than playing sports. In addition, many students do not like to play sports. Forcing students to play a sport that they do not want to play will not make the students have fun. This will also be bad for the students that dowish to play sports.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
          <p>
            <b>extracurricular</b> 과외의
          </p>
          <p>
            <b>beneficial</b> 유익한
          </p>
          <p>
            <b>participate</b> 참여하다
          </p>
          <p>
            <b>engage in</b> ~에 참여하다
          </p>
          <p>
            <b>waste</b> 낭비하다
          </p>
          <p>
            <b>succeed</b> 성공하다
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >학생들은 과외활동 스포츠를 해야 합니다. 스포츠는 하는데 즐겁고, 유익합니다. 왜냐하면 학생들은 스포츠 팀에 참여함으로부터 많은 것을 배울 수 있습니다. 이 장점들은 운동을 하는 것으로부터 친구들을 만나는 것까지 포함 할 수 있습니다. 게다가, 스포츠는 경쟁에 참여하는데 학생들을 위해서 건강한 방법입니다. 학생들이 서로 각자 경쟁을 하는 건강한 방법을 가질 때, 그들은 학교에서 적게 싸웁니다. 경쟁은 또한 학생들에게 성공을 위해서 일을 열심히 하는 것을 가르칩니다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >학생들은 학교 이후에 스포츠 팀을 하는 것에 강요되어지지 않아야 합니다. 오늘날, 학생들은 스포츠를 하는 것에 시간을 낭비하는데 매우 바쁩니다. 대신에, 학생들은 학원에서 배우는 것에 시간을 보낼 수 있습니다. 배우는 것이 스포츠 하는 것 보다 더 중요합니다. 게다가, 많은 학생들은 스포츠를 하는 것을 좋아하지 않습니다. 학생들에게 그들이 하기를 원하지 않는 스포츠를 하도록 강요하는 것은 학생들을 신나게 만들어 줄 수 없을 것입니다. 이것은 또한 스포츠를 하기를 소망하는 학생들에게도 나쁩니다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Did you take part in extracurricular activities when you were still in school?</li>
            <li>Should students be required to participate in extracurricular activities?</li>
            <li>Why are extracurricular sports so important?</li>
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
  
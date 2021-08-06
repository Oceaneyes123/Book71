<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/student-class-looking-course_23-2148888810.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Online Classes Versus Traditional Classes
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
        <td class = "lowertable" >Online classes are better than traditional classes, especially during this trying time. Although new cases are gradually declining, it is safer to stay indoors. There are still many asymptomatic carriers of COVID-19, so it would be highly irresponsible to send a child to school, where hundreds of people congregate. Jang Eun-gi, an 18-year-old student, told one broadcaster, “I have been thinking about whether the government can come up with a better solution than this, but this feels like the best choice for now.” Also, one recent government survey revealed that 66 percent of parents support the idea of online classes. La Dale Johnson, a parent of two from the U.S. who lives in Daegu, said, “I absolutely will not send my children back right away. I will wait longer to see how everyone is doing first. I have no idea what social distance other families are abiding by, and I don’t want to put my kids at risk.” We should make do with what we have.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Nothing can beat traditional classes. Online classes rely on a steady internet connection, so errors and other issues are inevitable. According to koreabizwire.com, “Some schools and students complained of delayed connections.” The site added, “Parents of young pupils, particularly those unfamiliar with smart devices, complained that they had to be with their children throughout the online classes to extend assistance.” Thus, not only are online classes shaky, but they’re also quite burdensome to the parents of schoolchildren. One mother even had to take a day off to assist her 9-year-old son. Moreover, according to thediplomat.com, “85,000 students are in need of devices such as tablets or laptops to take online classes. Yet the government is only able to provide about 38,000 devices.” Therefore, those who are less privileged may have a difficult time taking online classes. One politician stated, “If the government pushes ahead with unprepared policies and measures, in the end, students, parents, and teachers will suffer.”</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
          <p>
            <b>trying</b> 괴로운, 힘든
          </p>
          <p>
            <b>asymptomatic</b> 증상이 없는
          </p>
          <p>
            <b>irresponsible</b> 무책임한
          </p>
          <p>
            <b>congregate</b> 모이다
          </p>
          <p>
            <b>broadcaster</b> 방송사[국]
          </p>
          <p>
            <b>abide by</b> 따르다, 준수하다
          </p>
          <p>
            <b>make do with</b> (만족스럽지는 않지만 ~으로) 견디다[만족하다]
          </p>
          <p>
            <b>steady</b> 안정된
          </p>
          <p>
            <b>inevitable</b> 불가피한
          </p>
          <p>
            <b>pupil</b> 학생
          </p>
          <p>
            <b>burdensome</b> 부담스러운
          </p>
          <p>
            <b>privileged</b> 특권[특전]을 가진
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >온라인 수업은 전통적인 수업보다 더 나은데, 특히 이런 힘든 시기 중에 그렇다. 비록 신규 확진 사례가 점차 감소하고 있지만, 실내에 머무르는 것이 더 안전하다. 여전히 COVID-19 자각증상이 없는 보균자가 다수 존재하므로, 수백 명이 모이는 학교에 아이를 보내는 것은 매우 무책임한 일일 것이다. 18세의 장은기 학생은 한 방송사에 “정부가 이것보다 더 나은 해결책을 제시할 수 있을까에 대하여 고민했지만, 현재로써는 이것이 최선의 선택인 것 같다”고 말했다. 또, 최근의 한 정부 조사는 학부모의 66 퍼센트가 온라인 수업이라는 아이디어를 지지한다고 밝혔다. 대구에 살고있는 미국 출신의 두 아이 부모 라 데일 존슨(La Dale Johnson)씨는 “나는 내 아이들을 절대 바로 돌려보내지 않을 것이다. 나는 일단 더 오래 기다리며 다들 어떻게 지내는지 볼 것이다. 나는 다른 가족들이 어떤 사회적 거리 두기를 따르고있는지 전혀 모르며, 내 아이들을 위험에 빠뜨리고 싶지 않다”고 말했다. 우리는 우리가 가진 것으로 만족해야 한다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >어떤 것도 전통 수업을 이길 수 없다. 온라인 수업은 안정적인 인터넷 연결에 의존하기 때문에 오류 및 다른 문제들이 불가피하다. 코리아비즈와이어(koreabizwire.com)에 따르면, “일부 학교들과 학생들이 지연된 접속을 호소하였다”고 한다. 이 사이트는, “어린 학생들의 부모들, 특히 스마트 기기에 익숙하지 않은 학생들의 부모들은 온라인 수업 내내 도움을 제공하기 위하여 아이들과 함께 있어야 한다는 불만을 토로하였다”고 덧붙였다. 따라서 온라인 수업은 불안정할 뿐만 아니라 학생들의 부모들에게도 상당한 부담이 된다. 심지어 한 어머니는 9살짜리 아들을 돕기 위해 하루 휴가를 내야 했다. 또한, 더디플로맷(thediplomat.com)에 따르면 “8만 5천명의 학생들이 온라인 수업을 듣기 위하여 태블릿 또는 노트북과 같은 기기를 필요로 한다. 하지만 정부는 3만 8천여 대의 기기만 제공할 수 있다”고 말했다. 따라서, 보다 혜택 받지 못한 이들은 온라인 수업을 듣는데 어려움을 겪을 수도 있다. 한 정치인은, “만약 정부가 준비되지 않은 정책과 조치를 밀어붙이면 결국 학생과 학부모, 교사들이 피해를 볼 것이다”고 말했다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Which is more likely to be beneficial for students? Online or traditional classes?</li>
            <li>Is it necessary for all schools to provide online classes? Why?</li>
            <li>What are the pros and cons of traditional classes?</li>
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
  
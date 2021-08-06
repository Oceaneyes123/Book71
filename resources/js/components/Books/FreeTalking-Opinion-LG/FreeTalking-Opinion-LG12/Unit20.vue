<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/happy-kids-elementary-school_53876-46934.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Should Students Stop Dissecting Animals?
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
        <td class = "lowertable" >Animal dissections in classes should be banned. They are simply unnecessary. Nedim Buyukmihci, a professor at the University of California at Davis, said, “As one who did not dissect in high school, and who now is a veterinarian and trains doctors-to-be, I can unequivocally state that the experience of dissection is totally unnecessary for the biologically minded pre college student.” Moreover, according to the Physicians Committee for Responsible Medicine (PCRM), a non-profit research organization, dissections are not required for students to learn about science. In fact, PCRM found that no medical schools in the U.S. use animals to train new physicians. Revered medical programs at schools such as Stanford, Yale, and Harvard use alternative methods. According to abcnews.com, synthetic frogs that have the same visual and textural qualities as real frogs are already being used in some schools. They come with skeletons, muscles, skin, and organs, including a reproductive system with eggs. We need to put an end to this pointless form of cruelty.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Animal dissection should not be done away with. It provides students with more learning opportunities. According to edulab.com, “The learning that occurs courtesy of a dissection is vastly different to that afforded by a lecture or textbook lesson.” The hands-on approach of dissecting a real animal allows students to see and touch various organs, strengthening their comprehension of biological systems. The site also says that dissections can improve fine motor skills and hand-eye coordination. In addition, the American Psychological Association stated that animal dissection “engenders creativity, original thought, critical thinking, and problem-solving skills.” Plus, dissection can encourage students to pursue careers in science. The whole experience can be very inspiring. Vicki Besack, a U.S. high school science teacher, said, “Dissection is an amazing hands-on experience that has the power to cause a student to change how they think about science and possibly what they may pursue as a career.” Dissection is a crucial part of biology class.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
          <p>
            <b>unequivocally</b> 모호하지 않게, 명백히
          </p>
          <p>
            <b>alternative</b> 대체 가능한, 대안적인
          </p>
          <p>
            <b>synthetic</b> 인조의
          </p>
          <p>
            <b>reproductive</b> 생식[번식]의
          </p>
          <p>
            <b>pointless</b> 무의미한
          </p>
          <p>
            <b>cruelty</b> 학대
          </p>
          <p>
            <b>do away with</b> ~을 없애다[끝내다]
          </p>
          <p>
            <b>courtesy of</b> ~ 덕분에[결과로]
          </p>
          <p>
            <b>vastly</b> 대단히, 엄청나게
          </p>
          <p>
            <b>comprehension</b> 이해력
          </p>
          <p>
            <b>fine motor skill</b> 소근육 운동
          </p>
          <p>
            <b>engender</b> 불러일으키다
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >동물 해부 수업들은 금지되어야 한다. 해부는 단순하게 생각해도 필요하지 않은 부분이다. 캘리포니아 대학교 데이비스의 교수, 네딤 부육미히치는 말했다, “고등학교에서 해부를 공부하지 않고도 현재 수의사가 되었고 의사가 될 수 있는 사람을 훈련시키는 사람으로서, 해부라는 경험이 생물학적으로 대학교 입학을 하지 않은 학생에게는 전혀 불필요한 요소라고 생각한다.” 더 나아가서, 비영리 연구 기관인 PCRM (Responsible Medicine for Physicians Committee for Responsible Medicine)에 따르면, 학생들이 과학에 대해 배우기 위해서는 해부가 필요하지 않다. 실상, PCRM은 미국의 의과 대학에서도 새로운 의사를 훈련하기 위해 동물을 쓴다는 그 어떤 선례로 찾아볼 수 없었다. 스탠포드, 예일, 그리고 하버드 같은 학교에서 촉망있는 의과 교육 과정들은 다른 대체 방안들을 차용한다. ABC 뉴스 웹사이트에 따르면, 같은 시각적 그리고 조직 요소들이 유사한 실제 개구리들과 같은 가짜 개구리들이 몇몇 학교에서 활용된다고 한다. 그들은 난자가 있는 생식 기관을 포함한 골격, 근육, 피부 및 기관들을 가진다. 우리는 불필요한 잔혹행위를 이제 끝내야 한다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >동물 해부는 존속되어야 한다. 이는 학생들에게 더 많은 배움의 기회를 준다. Edulab(에듀랩) 사이트에 따르면, “해부에서 배우는 것은 수업 또는 교과서 수업에서 배울 수 있는 것과 큰 차이가 있다.” 직접 진짜 동물들을 해부하는 것은 학생들이 다양한 장기들을 보고 만지며 그들의 생물학 시스템 이해를 강화할 수 있게 해준다. 또한 해부는 세밀한 운동 기술과 손과 눈의 조화를 발전시켜준다고 언급한다. 더 나아가서, 미국 심리 학회 (American Psychological Association)는 동물의 해부가 “창의성, 독창적 사고, 비판적 사고 및 문제 해결 기술을 제공한다”고 밝혔다. 또한, 해부는 학생들이 과학 분야와 관련된 경력을 쌓을 수 있는 토대를 제공한다. 이러한 모든 해부 행위는 상당히 고무적으로 작용한다. 미국 고등학교 과학 교사인 비키 배삭은 “해부학은 학생들이 과학에 대한 사고방식을 포함해 그들이 쌓을 수 있는 경력을 바꿀 만한 놀라운 실습 경험입니다.”라고 덧붙였다. 해부는 생물학 수업에서 중요한 부분이다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Have you ever tried to dissect animals in class? How did you feel at the time?</li>
            <li>What is the importance of dissecting animals?</li>
            <li>Should animal dissections be banned in schools? Explain.</li>
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
  
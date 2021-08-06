<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/tired-businesswoman-covering-her-eyes-with-drawn-eyes-paper_23-2148813192.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Are You Burnt Out?
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
        <td class = "lowertable" >This is a definite yes. A burn-out is defined as giving up on everything as a result of intensive stress. With so much pressure from our daily lives we are stressed at school, home and pretty much everywhere we go. In addition to the already compact lifestyle there are far too many things to read and study. No matter how we organize our schedules this is something we just can’t avoid. Yes, burn-outs happen to just about everyone.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Sure, when a person reads more than usual, he or she can easily be stressed. However it doesn’t cause trauma. Those who oppose, describe burn-out as a state of chaos. When you exercise on a treadmill you get burnt out. They are simply two words to describe a state, a condition or a situation of a person. Please take into consideration that some people actually like reading and studying for extra information. Wouldn't It be wrong to argue that such people are clinically depressed?</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
  
          <p>
            <b>burn-out</b> (신체적 또는 정신적인) 극도의 피로
          </p>
          <p>
            <b>compact lifestyle</b> 아담한 생활 방식
          </p>
          <p>
            <b>trauma</b> 충격적인 경험
          </p>
          <p>
            <b>clinically depressed</b> 우울증 진단을 받은
          </p>
           
 
 

        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >확실히 그렇다. 과부하란 극도의 스트레스의 결과로 모든 것을 포기하는 것이라고 정의된다. 일상생활의 너무 많은 압박으로 인해 우리는 학교, 집 그리고 우리가 가는 곳 대부분에서 스트레스를 받는다. 이미 바쁜 생활 이외에도 읽고 공부할 것이 너무 많다. 아무리 스케줄 조정을 잘 한다고 해도 우리는 이러한 것을 피할 수 없다. 그렇다, 과부하라는 것은 누구에게나 발생하는 일이다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >확실히, 평상시 보다 더 많은 것을 읽으면, 그들은 쉽게 스트레스를 받을 수 있다. 하지만 그것은 트라우마를 유발하지는 않는다. 그러한 의견에 반대하는 사람은 극도로 피로한 것을 카오스(혼돈)상태로 설명한다. 당신이 러닝머신에서 운동할 때 당신은 피로해진다. 이라는 단어는 어떤 사람의 상태나 위치를 설명하는 간단한 두 단어이다. 어떠한 사람들은 실제로 정보를 얻기 위해 읽고 공부하는 것을 좋아한다는 사실을 생각해 보아라. 그러한 사람들이 임상적으로 우울하다고 주장하는 것은 잘못된 것이 아닐까?</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Have you ever felt like you were burnt out? For what reason?</li>
            <li>What did you do to be able to regain your strength?</li>
            <li>Do you think the feeling of being burnt out is similar to being stressed? Why or why not?</li>
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
  
<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/pretty-young-girls-gossiping-together_23-2148431547.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPW1">~에 대해서는 전혀 몰라.
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPW1">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;" class = "korean">

                 <h2>Pattern 15 |  </h2>
                  <br />
                  <h3>I don’t know anything about…</h3>
                    <br />
                    <p>
                    어떤 것에 대해 전혀 아는 바가 없을 때는 anything을 이용해서 이렇게 말해보자. 설사 조금은 알고 있더라도 모른다고 시치미를 뗄 때 사용하기도 한다.
                    </p>
                    <br />

<h2 class = "border-SPW1">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Who’s that guy with Carla?<br />
            B : I don’t know.<br />
            A : Do you think he’s her boyfriend?<br />
            B : I’m not sure. <b>난 칼라의 연애생활에 대해서는 아무것도 몰라</b>
          </p>
          <p style="line-height: 2;">
            A : 칼라랑 같이 있는 저 남자 누구지?<br />
            B : 모르겠는데.<br />
            A : 그 애 남자친구 같니?<br />
            B : 잘 모르겠어. <mark style="background-color: #a7d7c5; color: #d9e7cd;">I don’t know anything about Carla’s love life.</mark>
          </p>
          <br />


</div>

<h2  class = "border-SPW1">Pattern Practice
</h2>

<div style="padding-top : 10px; padding-bottom : 0px;">

        <br />

        <p>
          &rarr; 우리말을 보고 순식간에 영어로 말할 수 있을 때까지 반복하세요!
        </p>
        <br />

        <p>
          <b>113</b> 그것에 대해서는 전혀 몰라. ( it ) <br />
        </p>
        <p>
          <b>114</b> 난 너에 대해 아는 게 하나도 없어. ( you ) <br />
        </p>
        <p>
          <b>115</b> 정치에 대해서는 전혀 몰라요. ( politics ) <br />
        </p>
        <p>
          <b>116</b> 칼라의 연애생활에 대해서는 아무것도 몰라. ( love life ) <br />
        </p>
        <p>
          <b>117</b> 난 그 사람의 과거에 대해 아무것도 몰라. ( past ) <br />
        </p>
        <p>
          <b>118</b> 나는 축구에 대해 아무것도 모른다. ( football ) <br />
        </p>
        <p>
          <b>119</b> 나는 운전하는 것에 대해 아무것도 모른다.( driving ) <br />
        </p>
        <p>
          <b>120</b> 나는 컴퓨터에 대해 아무것도 모른다.( computers ) <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              113 I don’t know anything about it.<br />
              114 I don’t know anything about you.<br />
              115 I don’t know anything about politics.<br />
              116 I don’t know anything about Carla’s love life.<br />
              117 I don’t know anything about his past.<br />
              118 I don't know anything about football.<br />
              119 I don't know anything about driving.<br />
              120 I don't know anything about computers.<br />
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
  </v-container>

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


    }

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

<style lang="css">

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}

body{

  font-size: 16px;
}

</style>

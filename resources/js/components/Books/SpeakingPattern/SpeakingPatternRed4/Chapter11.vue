<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/beautiful-bride-with-her-husband-park_1157-19036.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPR4">놀람 표현하기
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPR4">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 71 |  </h2>
                  <br />
                  <h3>I was surprised to…</h3>
                    <br />
                    <p>
                    I was surprised to.. 는 놀란 이유에 대해서 이야기할 때 쓸 수 있는 표현으로, 상황이 끝난 후에 ‘휴, 사실은 ~해서 놀랐지 뭐야’와 같은 맥락에서 자주 사용된다..
                    </p>
                    <br />

<h2 class = "border-SPR4">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Did you hear that Jason got married?<br />
            B : Yeah I did.<br />
            <b>A : 그 소식 듣고 놀랐어.</b><br />
            B : Same here.
          <p style="line-height: 2;">
            A : 제이슨이 결혼한 거 들었어?<br />
            B : 응.<br />
            <b>A : I was surprised to hear the news.</b><br />
            B : 나도 그래.
          </p>
          <br />


</div>

<h2  class = "border-SPR4">Pattern Practice
</h2>

<div style="padding-top : 10px; padding-bottom : 0px;">

        <br />

        <p>
          &rarr; 우리말을 보고 순식간에 영어로 말할 수 있을 때까지 반복하세요!
        </p>
        <br />

        <p>
          <b>561</b> 그 소식 듣고 놀랐어 <br />
        </p>
        <p>
          <b>562</b> 그 사람이 거기 있는 걸 알고 놀랐지. <br />
        </p>
        <p>
          <b>563</b> 결과를 보고 놀라버렸어 <br />
        </p>
        <p>
          <b>564</b> 제가 선택돼서 놀랐습니다. <br />
        </p>
        <p>
          <b>565</b> 나는 그 애가 여자랑 함께 있는 것으로 보고 놀랐어. ( see, girl ) <br />
        </p>
        <p>
          <b>566</b>  <br />
        </p>
        <p>
          <b>567</b>  <br />
        </p>
        <p>
          <b>568</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              561 I was surprised to hear the news.<br />
              562 I was surprised to find him there.<br />
              563 I was surprised to see the results.<br />
              564 I was surprised to be selected.<br />
              565 I was surprised to see you with a girl.<br />
              566 I was surprised to hear from you again.<br />
              567 I was surprised to see you out here alone.<br />
              568 I was surprised to find out what happened.<br />
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
  </v-container>
        <br />
  <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#FFE7FF">
            <v-card-text class="px-10">

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

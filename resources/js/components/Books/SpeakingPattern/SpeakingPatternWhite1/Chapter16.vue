<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/front-view-siblings-doing-homework-together_23-2148355242.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPW1">Do you know?  ~를 아니?
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPW1">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;" class = "korean">

                 <h2>Pattern 16 |  </h2>
                  <br />
                  <h3>Do you know?</h3>
                    <br />
                    <p>
                    상대방이 어떤 사실이나 사람을 아는지 물을 때 쓰인다. ‘혹시 ~를 아니? 라고 물으려면 Do you happen to know…? 하면 되고, ‘~을 알고 있었니?’ 처럼 과거에 알았는지 물을 때는 Did you know…? 를 이용하면 된다.
                    </p>
                    <br />

<h2 class = "border-SPW1">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Do we have any assignments for tomorrow?<br />
            B : I’m not sure. I’ll have to check.<br />
            A : Okay. I’ll have to check.<br />
            B : Sure. <b>내 휴대폰 번호 알아?</b>
          </p>
          <p style="line-height: 2;">
            A : 우리 내일까지 해야 하는 과제 있어?<br />
            B : 모르겠네. 확인해봐야겠다.<br />
            A : 알았어. 그럼 내가 나중에 전화할게<br />
            B : 그래. <mark style="background-color: #a7d7c5; color: #d9e7cd;">Do you know my cell phone number?</mark>
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
          <b>121</b> 내 휴대폰 번호 알아? ( cell phone number )  <br />
        </p>
        <p>
          <b>122</b> 서로 아는 사이야? ( each other ) <br />
        </p>
        <p>
          <b>123</b> 그 남자 약혼한 거 알고 있어? ( engage ) <br />
        </p>
        <p>
          <b>124</b> 그 사람에 대해 아는 게 좀 있니? ( anything, about ) <br />
        </p>
        <p>
          <b>125</b> 너 내 이메일 주소 알아? ( e-mail address ) <br />
        </p>
        <p>
          <b>126</b> 당신은 이 단어의 뜻을 알고 있나요? ( meaning, word )  <br />
        </p>
        <p>
          <b>127</b> 안전벨트 매는 법 아세요? ( fasten, seat belt ) <br />
        </p>
        <p>
          <b>128</b> 컴퓨터를 다룰 줄 아세요? ( manipulate, computer ) <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              121 Do you know my cell phone number?<br />
              122 Do you know each other?<br />
              123 Do you know he’s engaged?<br />
              124 Do you know anything about him?<br />
              125 Do you know my e-mail address?<br />
              126 Do you know the meaning of this word?<br />
              127 Do you know how to fasten your seat belt?<br />
              128 Do you know how to manipulate a computer?<br />
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

<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/business-leader-interviewing-job-candidate_74855-1146.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPY2">~하려면 어떤 방법이 가장 좋을까요?
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPY2">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 40 | </h2>
                  <br />
                  <h3>What’s the best way to…?</h3>
                    <br />
                    <p>
                     Best는 ‘최선의, 가장 좋은’ 이라는 뜻으로, 상대방에게 어떤 방법에 대한 조언을 구하고 싶을 때 what’s the best way to….? 패턴을 유용하게 쓸 수 있다.
                    </p>
                    <br />

<h2 class = "border-SPY2">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Thank you for the interview.<br />
            B : <b>당신에게 연락하려면 어떻게 하는 게 가장 좋나요?</b><br />
            A : You can call my cell phone.<br />
            B : I’ll do that.
          </p>
          <p style="line-height: 2;">
            A : 인터뷰 해주셔서 감사합니다.<br />
            B : <mark style="background-color: #a7d7c5; color: #d9e7cd;">What’s the best way to get in touch with you?</mark><br />
            A : 제 휴대폰으로 전화하세요.<br />
            B : 그럴게요.
          </p>
          <br />


</div>

<h2  class = "border-SPY2">Pattern Practice
</h2>

<div style="padding-top : 10px; padding-bottom : 0px;">

        <br />

        <p>
          &rarr; 우리말을 보고 순식간에 영어로 말할 수 있을 때까지 반복하세요!
        </p>
        <br />

        <p>
          <b>313</b> 살을 빼려면 어떤 방법이 가장 좋을까요? ( lose weight ) <br />
        </p>
        <p>
          <b>314</b> 돈을 어떻게 관리하는 게 가장 좋을까요? ( manage ) <br />
        </p>
        <p>
          <b>315</b> 거기까지 가려면 어떤 방법이 가장 좋을까요? ( get, there ) <br />
        </p>
        <p>
          <b>316</b> 당신에게 연락하려면 어떻게 하는 게 가장 좋나요? (  get in touch ) <br />
        </p>
        <p>
          <b>317</b> 더 빨리 물을 끓일 방법이 있어. (boil, water) <br />
        </p>
        <p>
          <b>318</b>  <br />
        </p>
        <p>
          <b>319</b>  <br />
        </p>
        <p>
          <b>320</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              313 What’s the best way to lose weight?<br />
              314 What’s the best way to manage money?<br />
              315 What’s the best way to get there?<br />
              316 What’s the best way to get in touch with you?<br />
              317 What’s the best way to make them laugh?<br />
              318 What’s the best way to improve my skills?<br />
              319 What’s the best way to learn English?<br />
              320 What’s the best way to study for an exam?<br />
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
  </v-container>
        <br />
 

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

<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/young-couple-car-trip_23-2147935697.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPB5">~에 감사드려요.
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPB5">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 97 | </h2>
                  <br />
                  <h3>I appreciate…</h3>
                    <br />
                    <p>
                    보통 Thank you.는 “고마워.”라고 해서 단독으로 쓰일 수 있지만, appreciate는 구체적으로 ‘~해서 고마워’라고 이유를 덧붙일 때 더 많이 사용된다. 참고로 “진심으로 감사합니다.”라고 할 때는 Thank you. I appreciate it. 처럼 두 표현을 함께 사용한다.
                    </p>
                    <br />

<h2 class = "border-SPB5">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : What’s wrong?<br />
            B : I need to go to the airport, but I missed my bus.<br />
            A : Don’t worry about it. I’ll give you a ride.<br />
            B : Really? <b>친절하게 대해줘서 고마워.</b>
          </p>
          <p style="line-height: 2;">
            A : 무슨 일이야?<br />
            B : 공항에 가야 하는데 버스를 놓쳤어.<br />
            A : 걱정 마. 내가 태워다줄게.<br />
            B : 정말? <mark style="background-color: #a7d7c5; color: #d9e7cd;">I appreciate your kindness</mark><br />
            <br />
            *give ~a ride  ~를 태워주다.<br />
          </p>
          <br />


</div>

<h2  class = "border-SPB5">Pattern Practice
</h2>

<div style="padding-top : 10px; padding-bottom : 0px;">

        <br />

        <p>
          &rarr; 우리말을 보고 순식간에 영어로 말할 수 있을 때까지 반복하세요!
        </p>
        <br />

        <p>
          <b>769</b> 도와주셔서 감사드려요. ( help ) <br />
        </p>
        <p>
          <b>770</b> 전화 주셔서 감사드립니다. ( call ) <br />
        </p>
        <p>
          <b>771</b> 친절하게 대해줘서 고마워. ( kindness ) <br />
        </p>
        <p>
          <b>772</b> 걱정해주셔서 감사드려요. ( concern ) <br />
        </p>
        <p>
          <b>773</b> 시간 내주셔서 감사드립니다. ( time ) <br />
        </p>
        <p>
          <b>774</b>  <br />
        </p>
        <p>
          <b>775</b>  <br />
        </p>
        <p>
          <b>776</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              769 I appreciate your help.<br />
              770 I appreciate your call.<br />
              771 I appreciate your kindness.<br />
              772 I appreciate your concern.<br />
              773 I appreciate your time.<br />
              774 I appreciate the gesture.<br />
              775 I appreciate your presence.<br />
              776 I appreciate this very much.<br />
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

<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/aerial-view-business-data-analysis-graph_53876-13390.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPR4">~에 만족해
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPR4">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 66 |  </h2>
                  <br />
                  <h3>I’m happy with…</h3>
                    <br />
                    <p>
                    Happy는 ‘행복한, 만족한’ 이라는 뜻으로,  I’m happy with…는 어떤 것에 만족하거나 뭔가로 인해 기분이 좋을 때 자주 사용하는 패턴이다.
                    </p>
                    <br />

<h2 class = "border-SPR4">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : I love the new business plan.<br />
            B : Thank you. We worked very hard.<br />
            A : Well, <b>나도 성과에 만족합니다.</b><br />
            B : It should raise our profits.
          </p>
          <p style="line-height: 2;">
            A : 새로운 사업 기획안이 아주 맘에 드는군요.<br />
            B : 고맙습니다. 저희가 아주 열심히 했습니다.<br />
            A : 음, <mark style="background-color: #a7d7c5; color: #d9e7cd;">I’m happy with the outcome.</mark><br />
            B : 당연히 저희 이익이 올라갈 겁니다.
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
          <b>521</b> 그 성과에 만족하고 있어. ( outcome ) <br />
        </p>
        <p>
          <b>522</b> 난 새로 하게 된 일이 맘에 들어. ( new job ) <br />
        </p>
        <p>
          <b>523</b> 난 결과에 만족해. ( result ) <br />
        </p>
        <p>
          <b>524</b> 너희들 모두한테 만족해. ( all of you ) <br />
        </p>
        <p>
          <b>525</b> 자네의 실적에 만족하고 있네. ( performance ) <br />
        </p>
        <p>
          <b>526</b>  <br />
        </p>
        <p>
          <b>527</b>  <br />
        </p>
        <p>
          <b>528</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              521 I’m happy with the outcome<br />
              522 I’m happy with my new job.<br />
              523 I’m happy with the result.<br />
              524 I’m happy with all of you.<br />
              525 I’m happy with your performance.<br />
              526 I’m happy with what we have.<br />
              527 I’m happy with my choice.<br />
              528 I’m happy with what you’ve accomplished.<br />
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

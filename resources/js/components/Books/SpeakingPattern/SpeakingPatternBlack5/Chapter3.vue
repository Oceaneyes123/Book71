<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/louvre-museum-sunset_1361-124.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPB5">난 ~에 빠졌어
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPB5">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 83 |  </h2>
                  <br />
                  <h3>I’m into… </h3>
                    <br />
                    <p>
                    I’m into…는 무언가에 깊이 몰두해 있고 푹 빠져 있는 것을 표현하기에 좋은 패턴이다. 아주 깊이 빠져 있다고 강조하려면 I’m really into… ‘~는 별로야’라고 하려면 I’m not into…를 사용해보자.
                    </p>
                    <br />

<h2 class = "border-SPB5">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : We’re going to Paris this summer.<br />
            B : Lucky you. I’d love to see the Louvre.<br />
            A : Really?<br />
            B : Oh, yeah. <b>난 르네상스 예술에 빠졌거든.</b>
          </p>
          <p style="line-height: 2;">
            A : 이번 여름에 우린 파리에 갈 거야.<br />
            B : 좋겠다. 난 루브르를 보고 싶어.<br />
            A : 정말?<br />
            B : 응, 그럼. <mark style="background-color: #a7d7c5; color: #d9e7cd;">I’m into Renaissance art.</mark>
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
          <b>657</b> 난 빵,과자 굽는 것에 빠졌어. ( baking ) <br />
        </p>
        <p>
          <b>658</b> 난 영어 공부에 빠졌어. ( study, English ) <br />
        </p>
        <p>
          <b>659</b> 난 얼터너티브 록 음악에 빠졌어. ( alternative, rock music ) <br />
        </p>
        <p>
          <b>660</b> 난 르네상스 예술에 빠졌어. ( Renaissance art ) <br />
        </p>
        <p>
          <b>661</b> 난 스쿠버 다이빙에 빠졌어. ( scuba diving ) <br />
        </p><p>
          <b>662</b>  <br />
        </p><p>
          <b>663</b>  <br />
        </p><p>
          <b>664</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              657 I’m into baking.<br />
              658 I’m into studying English.<br />
              659 I’m into alternative rock music.<br />
              660 I’m into Renaissance art. <br />
              661 I’m into scuba diving.<br />
              662 I’m into extreme sports lately.<br />
              663 I’m into non-fiction books.<br />
              664 I’m into sci-fi movies.<br />
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

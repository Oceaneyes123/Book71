<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/wistful-male-teenager-sitting-ground-with-arms-crossed_23-2148205461.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPW1">~를 알아
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPW1">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;" class = "korean" >

                 <h2>Pattern 11 |  </h2>
                  <br />
                  <h3>I know…</h3>
                    <br />
                    <p>
                    I know…는 알고 있는 바를 이야기할 때뿐만 아니라. “네 마음 내가 잘 알아.” 처럼 상대방의 말이나 감정에 공감을 표현할 때도 자주 쓰인다.
                    </p>
                    <br />

<h2 class = "border-SPW1">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Tom really misses his family<br />
            B : We should cheer him up.<br />
            A : Okay, but how?<br />
            B : Leave it to me. <b>난 어떻게 해야 톰을 웃길 수 있는지 알아.</b>
          </p>
          <p style="line-height: 2;">
            A : 톰이 가족을 정말 그리워해<br />
            B : 그 애한테 힘을 좀 줘야겠는데.<br />
            A : 좋아, 근데 어떻게 해야하지?<br />
            B : 나한테 맡겨둬. <mark style="background-color: #a7d7c5; color: #d9e7cd;">I know how to make Tom laugh</mark>.
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
          <b>081</b> 내가 이 지역은 꽉 잡고 있지 ( area, well ) <br />
        </p>
        <p>
          <b>082</b> 내가 무슨 짓을 했는지 다 알아 ( what, do ) <br />
        </p>
        <p>
          <b>083</b> 어떻게 해야 톰을 웃길 수 있는지 알아. ( how, laugh ) <br />
        </p>
        <p>
          <b>084</b> 네 기분이 어떤지 알아. ( how, feel ) <br />
        </p>
        <p>
          <b>085</b> 난 네가 내 여동생을 사랑했다는 거 알아. (love, sister) <br />
        </p>
        <p>
          <b>086</b> 사랑이 뭔지 알아요. (what, love) <br />
        </p>
        <p>
          <b>087</b> 두 분 다 잘 알고 있습니다. (both, well) <br />
        </p>
        <p>
          <b>088</b> 그녀가 농담하는 거 알아요. (she, joke) <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              081 I know this area very well<br />
              082 I know what you did.<br />
              083 I know how to make Tom laugh.<br />
              084 I know how you feel.<br />
              085 I know that you loved my sister.<br />
              086 I know what love is.<br />
              087 I know you both well.<br />
              088 I know she is joking.<br />
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

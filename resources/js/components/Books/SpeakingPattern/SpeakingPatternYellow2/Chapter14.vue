<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/coffee-machine-filling-cup_1286-228.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPY2">~하는 사람 있어?
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPY2">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 34 |  </h2>
                  <br />
                  <h3>Is there anyone who…</h3>
                    <br />
                    <p>
                    여러 사람들 가운데 특정한 사람을 찾을 때 이 표현을 사용해보자. Who 다음에는 찾고자 하는 anyone을 설명하는 내용이 와야 한다.
                    </p>
                    <br />

<h2 class = "border-SPY2">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Do you know how to go to Espresso Café?<br />
            B : No, I don’t<br />
            A : <b>거기에 어떻게 가는지 아는 사람 있어</b><br />
            B : Why don’t you ask Phil?
          </p>
          <p style="line-height: 2;">
            A : 익스프레소 카페에 어떻게 가는지 알아?<br />
            B : 아니,<br />
            A : <mark style="background-color: #a7d7c5; color: #d9e7cd;">Is there anyone who knows how to get there?</mark><br />
            B : 필한테 한번 물어봐.
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
          <b>265</b> 이거 고칠 수 있는 사람 있나요? ( fix ) <br />
        </p>
        <p>
          <b>266</b> 거기에 어떻게 가는지 아는 사람 있어? ( know, get ) <br />
        </p>
        <p>
          <b>267</b> 이탈리아에 가본 사람 있니? ( has been to ) <br />
        </p>
        <p>
          <b>268</b> 일본어 할 줄 아는 사람 있어요? ( speak, Japanese ) <br />
        </p>
        <p>
          <b>269</b> 무슨 일이 일어났는지 본 사람 있나요? ( see, what happened ) <br />
        </p>
        <p>
          <b>270</b>  <br />
        </p>
        <p>
          <b>271</b>  <br />
        </p>
        <p>
          <b>272</b>  <br />
        </p>

        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              265 Is there anyone who can fix this?<br />
              266 Is there anyone who knows how to get there?<br />
              267 Is there anyone who has been to Italy?<br />
              268 Is there anyone who can speak Japanese?<br />
              269 Is there anyone who has seen what happened?<br />
              270 Is there anyone who would like to try?<br />
              271 Is there anyone you would like to meet?<br />
              272 Is there anyone out there?<br />
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

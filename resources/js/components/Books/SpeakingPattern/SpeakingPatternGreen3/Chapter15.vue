<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://pm1.narvii.com/6015/fbbe82a7c8b0edab53e3b698d9d2710fd2228ee7_hq.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPG3">~하는 게 좋겠어
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPG3">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 55 |  </h2>
                  <br />
                  <h3>We’d better…</h3>
                    <br />
                    <p>
                    이 패턴 역시 뭔가를 제안하는 말이지만, 제안대로 하지 않으면 뭔가 안 좋은 일이 일어날 거라는 전제가 깔려있다. 즉 강한 권고의 표현이다.
                    </p>
                    <br />

<h2 class = "border-SPG3">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Wow, there are a lot of people here.<br />
            B : <b>줄을 서는 게 좋겠어.</b><br />
            A : What if we can’t get concert tickets?<br />
            B : We’ll just have to try.
          </p>
          <p style="line-height: 2;">
            A : 와, 여기 사람들 많네.<br />
            B : <mark style="background-color: #a7d7c5; color: #d9e7cd;">We’d better get in line.</mark><br />
            A : 우리가 표를 못 구하면?<br />
            B : (그래도 구할 수 있나) 노력해봐야겠지.
          </p>
          <br />


</div>

<h2  class = "border-SPG3">Pattern Practice
</h2>

<div style="padding-top : 10px; padding-bottom : 0px;">

        <br />

        <p>
          &rarr; 우리말을 보고 순식간에 영어로 말할 수 있을 때까지 반복하세요!
        </p>
        <br />

        <p>
          <b>433</b> 준비를 하는 게 좋겠어. ( get prepared ) <br />
        </p>
        <p>
          <b>434</b> 예약을 하는 게 좋겠어. ( make a reservation ) <br />
              *make a reservation  예약하다. <br />
        </p>
        <p>
          <b>435</b> 줄을 서는 게 좋을 것 같아. ( get in line ) <br />
              *get in line 줄을 서다.<br />
        </p>
        <p>
          <b>436</b> 두 눈 똑바로 뜨고 있는 게 좋겠어.( keep our eyes open ) <br />
        </p>
        <p>
          <b>437</b> 우리 이제 서로 만나지 않는 게 좋겠어. ( stop, see, each, other ) <br />
        </p>
        <p>
          <b>438</b>  <br />
        </p>
        <p>
          <b>439</b>  <br />
        </p>
        <p>
          <b>440</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              433 We’d better get prepared.<br />
              434 We’d better make a reservation.<br />
              435 We’d better get in line.<br />
              436 We’d better keep our eyes open.<br />
              437 We’d better stop seeing each other.<br />
              438 We’d better hurry before the rain pours.<br />
              439 We’d better fix this mess.<br />
              440 We’d better go home.<br />
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

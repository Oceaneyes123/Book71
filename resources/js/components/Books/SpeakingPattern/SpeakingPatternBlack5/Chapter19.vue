<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/cheerful-woman-gesturing-talking-friend_23-2148143246.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPB5">~해주시니 정말 ~하세요
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPB5">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;">

                 <h2>Pattern 99 |  </h2>
                  <br />
                  <h3>It’s very ~of you to…</h3>
                    <br />
                    <p>
                    Thank you  만으로는 고마운 마음이 충분히 전달된 것 같지 않을 때 덧붙이기 좋은 패턴이다. It’s very 다음에 kind, nice, good 등의 형용사를 써서 감사의 마음을 전해보자
                    </p>
                    <br />

<h2 class = "border-SPB5">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : What are you doing tomorrow?<br />
            B : Nothing. Why?<br />
            A : Do you want to come over to my place for dinner?<br />
            B : Sure. <b>초대해줘서 고마워.</b>
          </p>
          <p style="line-height: 2;">
            A : 내일 뭐 해?<br />
            B : 아무것도 안 해. 왜?<br />
            A : 우리 집에 저녁 먹으러 올래?<br />
            B : 그래. <mark style="background-color: #a7d7c5; color: #d9e7cd;">It’s very nice of you to invite me.</mark><br />
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
          <b>785</b> 그렇게 말해주셔서 정말 감사합니다. ( say, so ) <br />
        </p>
        <p>
          <b>786</b> 저를 초대해주셔서 정말 감사드려요. ( invite ) <br />
        <p>
          <b>787</b> 배웅해주셔서 정말 감사드려요. ( send off ) <br />
                    *see~off  ~를 배웅하다.<br />
        </p>
        <p>
          <b>788</b> 꽃을 보내주시다니 정말 사려 깊으세요. ( send, flower ) <br />
        </p>
        <p>
          <b>789</b> 그 노부인을 도와드리다니 정말 생각이 깊구나. ( help, old woman ) <br />
        </p>
        <p>
          <b>790</b>  <br />
        </p>
        <p>
          <b>791</b>  <br />
        </p>
        <p>
          <b>792</b>  <br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              785 It’s very kind of you to say so.<br />
              786 It’s very nice of you to invite me.<br />
              787 It’s very good of you to see me off.<br />
              788 It’s very thoughtful of you to send flowers.<br />
              789 It’s very thoughtful of you to help the old woman.<br />
              790 It’s very generous of you to give us these materials.<br />
              791 It’s very kind of you to help us in this project.<br />
              792 It’s very helpful of you to do the laundry.<br />
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

<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://image.freepik.com/free-photo/front-view-happy-friends-showing-tongues_23-2148270960.jpg">

        <v-layout
        align-end
        fill-height
        pa-2
        black--text
      >
     <h1 class="upper-header-SPY2">~가 무척 많아
  </h1>
      </v-layout>
    </v-img>


          <h2 class="lower-header-SPY2">Today's topic</h2>

  <hr width="60%">
               <div style="padding : 10px; line-height: 200%;" class = "korean">

                 <h2>Pattern 22 |  </h2>
                  <br />
                  <h3>There are so many~</h3>
                    <br />
                    <p>
                    여러 개가 있다고 할 때는 There is가 아니라 There are를 써야 한다. 뭔가가 굉장히 많을 때는 There are so many… 너무 많아서 문제가 있거나 짜증스러울 때는 There are too many…를 써서 말해보자.
                    </p>
                    <br />

<h2 class = "border-SPY2">Dialogue
</h2>

<div style="padding-top : 10px; padding-bottom : 2px;">

          <br />
          <p style="line-height: 2;">
            A : Let’s have a drink tonight.<br />
            B : I wish I could, but I can’t<br />
            A : Why not?<br />
            B : <b>오늘 할 일이 무척 많거든.</b>
          </p>
          <p style="line-height: 2;">
            A : 오늘 밤에 한잔 하자<br />
            B : 그러고는 싶은데 안 되겠어.<br />
            A : 왜 안 되는데?<br />
            B : <mark style="background-color: #a7d7c5; color: #d9e7cd;">There are so many things to do today.</mark>
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
          <b>169</b> 자동차 몇 대가 주차되어 있어. ( party ) <br />
        </p>
        <p>
          <b>170</b> 남은 표가 별로 없어. ( left ) <br />
        </p>
        <p>
          <b>171</b> 오늘 할 일이 무척 많거든. ( things ) <br />
        </p>
        <p>
          <b>172</b> 이건 문제가 너무 많아.  ( problem, this ) <br />
        </p>
        <p>
          <b>173</b> 여기는 볼 것이 참 많아. ( things, see, here ) <br />
        </p>
        <p>
          <b>174</b> 행복해야 할 많은 아름다운 이유들이 있습니다. ( beautiful, reason ) <br />
        </p>
        <p>
          <b>175</b> 오늘은 구름이 많이 끼었어요. (many,clouds) <br />
        </p>
        <p>
          <b>176</b> 세상에는 매우 다양한 그룹들이 있습니다. (different, groups)<br />
        </p>
        <v-container grid-list-md text-xs-left>
      <v-layout row wrap>


          <v-flex xs12>
          <v-card light color="#a7d7c5">
            <v-card-text class="px-10" style="color:#d9e7cd;">
              169 There are a few cars parked.<br />
              170 There are only a few tickets left.<br />
              171 There are so many things to do today.<br />
              172 There are too many problems with this.<br />
              173 There are so many things to see here.<br />
              174 There are so many beautiful reasons to be happy.<br />
              175 There are so many clouds today. <br />
              176 There are so many different groups out there.<br />
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

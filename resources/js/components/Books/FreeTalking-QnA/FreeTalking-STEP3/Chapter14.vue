<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://marketplace.canva.com/MADGvmGpZ2I/7/screen_2x/canva-fashionable-woman-MADGvmGpZ2I.jpg" class="cover-photo-FTQNA3" >

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
      >
        <h1 class="upper-header-FTQNA3">Fashion</h1>
      </v-layout>
    </v-img>


          <h3 class="border-FTQNA3">Q &amp; A</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       Why does fashion change so quickly?
     </li>
     <br />
     <li class="mb-2">
        Why does fashion go in cycles?
        <ul>
        <li class="mt-2"> Why do clothes go out of fashion and then come back in again?</li>
        </ul>
     </li>
     <br />
     <li class="mb-2">
        Do you like to wear the same as your friends?
        <ul>
        <li class="mt-2"> Why? Why not?</li>
        </ul>
     </li>
     <br />
     <li class="mb-2">
          Do you wear ‘brand’ clothes?
        <ul>
        <li class="mt-2"> Why? Why not?</li>
       </ul>
     </li>
     <br />
     <li class="mb-2">
        Can you tell someone’s personality by their clothes?
        <ul>
        <li class="mt-2"> Support your opinion. Give some examples.</li>
       </ul>
     </li>
   </ol>



</div>

<h3 class="border-FTQNA3">Translation</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       패션은 왜 이렇게 빨리 변할까요?
     </li>
     <br />
     <li class="mb-2">
        왜 패션은 순환하는 것일까요?
        <ul>
        <li class="mt-2">왜 옷은 유행이 지난 후에 다시 돌아오는 걸까요?</li>
        </ul>
     </li>
     <br />
     <li class="mb-2">
        여러분은 친구들과 똑같이 입는 것을 좋아하나요?
        <ul>
        <li class="mt-2">왜 그런가요? 왜 그렇지 않나요?</li>
        </ul>
     </li>
     <br />
     <li class="mb-2">
          당신은 '브랜드' 옷을 입나요?
        <ul>
        <li class="mt-2">왜 그런가요? 왜 그렇지 않나요?</li>
       </ul>
     </li>
     <br />
     <li class="mb-2">
        옷으로 성격을 알 수 있나요?
        <ul>
        <li class="mt-2">당신의 의견을 지지해보세요. 몇 가지 예를 들어 보세요.</li>
       </ul>
     </li>
   </ol>



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

<style scoped lang="css">

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}



body{

  font-size: 16px;
}

ul {
  list-style-type: none;
}

ul > li:before {
  content: "–"; /* en dash */
  position: absolute;
  margin-left: -1.1em;
}


</style>

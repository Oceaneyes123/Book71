<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://marketplace.canva.com/MADGx6br8Ws/4/screen_2x/canva-aerial-view-of-city-buildings-MADGx6br8Ws.jpg" class="cover-photo-FTQNA3" >

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
      >
        <h1 class="upper-header-FTQNA3">Modern Life</h1>
      </v-layout>
    </v-img>


          <h3 class="border-FTQNA3">Q &amp; A</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       What do you like about the modern world?
       <ul>
       <li class="mt-2"> What don't you like about the modern world?</li>
       </ul>
     </li>
     <br />
     <li class="mb-2">
        How can we deal with global warming?
     </li>
     <br />
     <li class="mb-2">
       Could you live without electricity?
     </li>
     <br />
     <li class="mb-2">
       What is the biggest problem in the world today?
     </li>
     <br />
     <li class="mb-2">
       If you could travel back in time, which year would you choose to visit?
       <ul>
       <li class="mt-2"> Who would you like to meet?</li>
       </ul>
     </li>
   </ol>



</div>

<h3 class="border-FTQNA3">Translation</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       현대 세계의 어떤 점이 마음에 드세요?
       <ul>
       <li class="mt-2">현대 세계의 어떤 점이 마음에 들지 않나요?</li>
       </ul>
     </li>
     <br />
     <li class="mb-2">
        지구 온난화에 어떻게 대처해야 할까요?
     </li>
     <br />
     <li class="mb-2">
       전기 없이 살 수 있나요?
     </li>
     <br />
     <li class="mb-2">
       오늘날 세계에서 가장 큰 문제는 무엇입니까?
     </li>
     <br />
     <li class="mb-2">
       만약 당신이 시간을 거슬러 여행할 수 있다면, 몇 년도에 방문하겠습니까?
       <ul>
       <li class="mt-2">누구를 만나고 싶습니까?</li>
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

<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

  <v-layout column>
    <v-img
           src="https://marketplace.canva.com/CxOw8/MADx6NCxOw8/1/s2/canva-person-doing-crochet-MADx6NCxOw8.jpg" class="cover-photo-FTQNA3" >

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
      >
        <h1 class="upper-header-FTQNA3 ">Hobbies</h1>
      </v-layout>
    </v-img>


          <h3 class="border-FTQNA3">Q &amp; A</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       What are you hobbies?
     </li>
     <br />
     <li class="mb-2">
        With whom do you enjoy your hobbies?
     </li>
     <br />
     <li class="mb-2">
       Are there any hobbies you would like to try soon?
     </li>
     <br />
     <li class="mb-2">
       Are there any hobbies you have given up? Why?
     </li>
     <br />
     <li class="mb-2">
       Did you ever recommend that family members share your hobbies with you?
     </li>
   </ol>



</div>

<h3 class="border-FTQNA3">Translation</h3>
               <div style="padding : 16px;">

   <ol style="margin: 12px;">
     <li class="mb-2">
       취미가 뭐예요?
     </li>
     <br />
     <li class="mb-2">
       당신은 누구와 함께 취미를 즐기나요?
     </li>
     <br />
     <li class="mb-2">
       조만간 해보고 싶은 취미가 있나요?
     </li>
     <br />
     <li class="mb-2">
       포기한 취미가 있나요? 왜요?
     </li>
     <br />
     <li class="mb-2">
       당신은 가족 구성원들과 당신의 취미를 공유하려고 추천한 적이 있나요?
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

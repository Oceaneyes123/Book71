<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://image.freepik.com/free-photo/diy-equipment-paintbrush-clothespin-needle-safety-pins-acrylic-paint-tube-buttons-diy-blocks-measuring-tape-isolated-white-backdrop_23-2148125312.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <transition name="slide-fade">
        <h1 v-if="showTitle" class="upper-header-lg">[08/24] DIY Versus Professional Services
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class="line-top-lg">
  </div>

  <h3  class = "lower-header-lg white--text">Topic</h3>
  <div style = "padding : 16px; line-height: 1.6;">

    <table style = "border-collapse: collapse;">

    <tr>
      <td class = "uppertable" ><b>Jane :</b></td>
      <td class = "lowertable" >Nowadays, people prefer DIY projects over receiving professional help. Since you are personally making something, you have complete control and customizing is limitless. If you hire someone else to do the work, you never know what to expect.</td>
    </tr>
    <tr style="color:#1565C0;">
      <td class = "uppertable" ><b>Tom :</b></td>
      <td class = "lowertable" >DIY projects can be great, but there are some things that should be left for professionals. For example, if you need to install an electrical outlet, it is much safer to call an electrician instead of trying yourself.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>nowadays</b> 요즘에는 
        </p>
        <p>
          <b>prefer</b> 선호하다 
        </p>
        <p>
          <b>receive</b> 받다 
        </p>
        <p>
          <b>personally</b> 직접 
        </p>
        <p>
          <b>complete</b> 완전한 
        </p>
        <p>
          <b>control</b> 통제 
        </p>
        <p>
          <b>limitless</b> 제한이 없는 
        </p>
        <p>
          <b>hire</b> 고용하다 
        </p>
        <p>
          <b>expect</b> 예상하다 
        </p>
        <p>
          <b>electrical outlet</b> 콘센트 
        </p>
        <p>
          <b>electrician</b> 전기 기사 
        </p>

      </div>

      <div class = "line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>
      <div style="padding : 16px;">

        <table style = "border-collapse: collapse;">

          <tr>
            <td class = "uppertable" ><b>제인 :</b></td>
            <td class = "lowertable" >요즘 사람들은 전문적인 도움을 받는 것보다 DIY를 선호해. 네가 개인적으로 무언가를 만들고 있기 때문에 너는 완전한 통제권을 가지고 있으며, 무한대로 맞출 수 있어. 만약 네가 작업을 수행하기 위해 다른 사람을 고용하는 경우에는 무엇을 기대해야 할 지 몰라.</td>
          </tr>
          <tr style="color:#1565C0;">
            <td class = "uppertable" ><b>탐 :</b></td>
            <td class = "lowertable" >DIY는 훌륭하지만 전문가들에게 맡겨야만 하는 일들이 있어. 예를 들어 만약 네가 전기 콘센트를 설치해야 하는 경우 직접 시도하는 대신 전기 기술자에게 문의하는 것이 훨씬 안전하지.</td>
          </tr>
      
          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>
            Do you like making or assembling things (like IKEA furniture)? Why or why not?
          </li>
          <li>Which do you prefer - doing it yourself or getting a professional service? Why?</li>
          <li>What are the advantages and disadvantages of DIY and professional services?</li>
        </ol>

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
      showTitle:false


    }

  },

mounted(){
  this.showTitle=true
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



</style>

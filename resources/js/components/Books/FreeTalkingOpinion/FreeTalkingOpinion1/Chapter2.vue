<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://images.pexels.com/photos/708440/pexels-photo-708440.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <transition name="slide-fade">
        <h1 v-if="showTitle" class="upper-header-opinion1">Should We Look For Chances To Compliment Others?
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class="line-top-opinion1">
  </div>

  <h3  class = "lower-header-opinion1 white--text">Topic</h3>


  <div style = "line-height: 1.6;">
    <div style="padding : 16px;">

    <table class="standard-table">

    <tr>
      <td class = "uppertable" ><b>A :</b></td>
      <td class = "lowertable" >I recently completed a project. It was about how we should all do more.
      By taking action through community activities.
      During our discussions, I just said ideas without thinking!
      I was so embarrassed to even talk about it to be honest.
      But a teammate spoke highly of me even when I said something really stupid.</td>
    </tr>
    <tr style="color:#1565C0;">
      <td class = "uppertable" ><b>B :</b></td>
      <td class = "lowertable" >I guess that is the key in good social relations.
      Even when you find that something is stupid, you should look for chances to compliment others!</td>
    </tr>

    </table>

      <p>
        Do we need to find chances to compliment others?
      </p>

    </div>

      <div class="line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>chance</b> 기회, 가능성 
        </p>

        <p>
          <b>compliment</b> 칭찬하다
        </p>

        <p>
          <b>recently</b> 최근에
        </p>

        <p>
          <b>action</b> 행동
        </p>

        <p>
          <b>discussion</b> 논의, 상의
        </p>

        <p>
          <b>embarrassed</b> 어색한, 당황스런
        </p>

        <p>
          <b>stupid</b> 멍청한, 바보 같은 
        </p>

        <p>
          <b>social</b> 사회적인
        </p>

        <p>
          <b>relation</b> 관계, 관계[관련], 친척
        </p>


      </div>

      <div class="line-opinion1">
      </div>
      <h3 class = "border-translate-opinion1 white--text">해석</h3>
      <div style="padding : 16px;">

                      <p class = "korean">
                        <b>
                        우리는 다른 사람들을 칭찬하는 기회를 찾아야만 할까요?
                        </b>
                      </p>

                      <table class="standard-table">

                       <tr>
                        <td class = "uppertable" ><b>A :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >최근에 학교 프로젝트를 끝냈어.
                        그것은 어떻게 우리 모두가 커뮤니티 활동을 통해서 조치를 취하여 더 일을 해야 하는지에 대해서였어.
                        토론하는 동안, 나는 생각하지 않고 아이디어들을 그냥 말했어!
                        솔직히 심지어 그것에 대해서 이야기하기가 몹시 당황스러웠어.
                        그렇지만 팀의 친구는 내가 진짜 바보 같은 말을 했을 때도 나를 칭찬해줬어.</td>
                      </tr>
                      <tr style="color:#1565C0;">
                        <td class = "uppertable" ><b>B :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >그것은 좋은 사회적 관계에서의 핵심이라고 생각해.
                        심지어 네가 무언가 바보 같은 걸 찾았을 때에도, 너는 다른 사람들을 칭찬할 기회를 찾아야만 해!</td>
                      </tr>

                      </table>

                  


      </div>
     <div class="line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Questions</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How honest are you in giving compliments?</li>
          <li>Is it necessary to compliment other people?  Why or why not?</li>
          <li>Which do you find easier, giving compliments or receiving compliments? Why?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://image.freepik.com/free-photo/laptop-surrounded-by-pictures_23-2148019165.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <transition name="slide-fade">
        <h1 v-if="showTitle" class="upper-header-opinion1">Should a Celebrity's Private Life Be Open To The Public?
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class="line-top-opinion1">
  </div>

  <h3  class = "lower-header-opinion1 white--text">Topic</h3>
  <div style = "line-height: 1.6;">
    <div style="padding : 16px;">   

    <table class = "standard-table">

    <tr>
      <td class = "uppertable" ><b>A :</b></td>
      <td class = "lowertable" >Fans of celebrities want to know everything about them.
      If celebrities want to become more famous, they shouldn't be afraid of opening their private lives to the public.
      They also need to learn to take criticism.</td>
    </tr>
    <tr style="color:#1565C0;">
      <td class = "uppertable" ><b>B :</b></td>
      <td class = "lowertable" >People should admire a celebrity's talent, not his or her private life.
      Celebrities need some privacy, just like normal people.
      Also, even if they earn a lot of money, that doesn't mean their private lives should be exposed to everyone..</td>
    </tr>

    </table>

    </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>afraid</b> 두려워하는
        </p>
        <p>
          <b>public</b> 일반 사람들, 대중
        </p>
        <p>
          <b>criticism</b> 비난
        </p>
        <p>
          <b>admire</b> 감탄하며 바라보다
        </p>
        <p>
          <b>talent</b> 재능
        </p>
        <p>
          <b>privacy</b> 사생활
        </p>
        <p>
          <b>normal</b> 평범한
        </p>
        <p>
          <b>earn</b> (돈을) 다
        </p>
        <p>
          <b>expose</b> 드러내다
        </p>

      </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-translate-opinion1 white--text">해석</h3>
      <div style="padding : 16px;">

                      <p class = "korean">
                        <b>
                        유명인의 사생활이 대중들에게 공개되어야만 하나요?
                        </b>
                      </p>

                      <table class = "standard-table">

                       <tr>
                        <td class = "uppertable" ><b>A :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >유명 인사의 팬은 자신에 대한 모든 것을 알고 싶어합니다.
                          유명 인사가 더 유명 해지고 싶다면 대중에게 사생활을 개방하는 것을 두려워해서는 안됩니다.
                          그들은 또한 비판을 받는 법을 배울 필요가 있습니다.</td>
                      </tr>
                      <tr style="color:#1565C0;">
                        <td class = "uppertable" ><b>B :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >사람들은 그들의 사생활이 아닌 유명인의 재능에 감탄해야 합니다.
                          유명 인사는 평범한 사람들처럼 사생활이 필요 합니다.
                          또한, 그들이 돈을 많이 벌더라도,
                          그것이 그들의 사생활이 모든 사람들에게 노출되어야 한다는 것을 의미하지는 않습니다..</td>
                      </tr>

                    
                      </table>


      </div>
     <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Questions</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think famous people have the right to a private life? Why or Why not?</li>
          <li>In your opinion, what are the possible pros and cons of being a celebrity?</li>
          <li>Which celebrity would you like to meet? What would you do if you could spend a day with this person in public?</li>
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

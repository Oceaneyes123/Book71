<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://image.freepik.com/free-photo/generative-robot-animation_183364-25024.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <transition name="slide-fade">
        <h1 v-if="showTitle" class="upper-header-opinion1">Should We Build Military Robots?
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
      <td class = "lowertable" >I think it is a wonderful idea! If we can put robots into combat, humans no longer have to live in fear of war.
      Even if a war breaks out, no one will die or be injured.
      Besides, no one will have to be drafted to the army against his will.</td>
    </tr>
    <tr style="color:#1565C0;">
      <td class = "uppertable" ><b>B :</b></td>
      <td class = "lowertable" >That is idealistic. However, how can we be sure that governments around the world won't use them against civilians?
      There's only a fine line between a combat robot and a killer robot.</td>
    </tr>

    </table>

    </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>serve</b> (군대에서) 복무하다
        </p>
        <p>
          <b>military</b> 군대
        </p>
        <p>
          <b>combat</b> 전투
        </p>
        <p>
          <b>fear</b> 두려움
        </p>
        <p>
          <b>drafted</b> 징집되다
        </p>
        <p>
          <b>idealistic</b> 이상주의적인
        </p>
        <p>
          <b>government</b> 정부
        </p>
        <p>
          <b>against</b> ~ 에 반대하여, 맞서
        </p>
        <p>
          <b>civilian</b> 민간인
        </p>
        <p>
          <b>fine</b> 미세한
        </p>
        <br />
        <p style="color: #56AAFF;">
          <b>breaks out 발발하다</b>
        </p>
        <p style="color: #56AAFF;">
          <b>fine line 종이 한 장 차이</b>
        </p>

      </div>

      <div class = "line-opinion1">
      </div>
      <h3 class = "border-translate-opinion1 white--text">해석</h3>
      <div style="padding : 16px;">


                      <p class = "korean">
                        <b>
                        해석 군사용 로봇을 제작해도 괜찮을까?
                        </b>
                      </p>

                      <p class = "korean">
                        <b>
                        나는 멋진 생각이라고 생각해!
                        </b>
                      </p>

                      <table class = "standard-table">

                       <tr>
                        <td class = "uppertable" ><b>A :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >우리가 로봇을 전투에 투입할 수 있다면,
                        인간은 더 이상 전쟁의 공포 속에서 살지 않아도 된다 전쟁이 일어나도 아무도 죽거나 다치지 않을 꺼야 게다가,
                        아무도 그의 의지에 반하여 군대에 징집될 필요가 없을 거야</td>
                      </tr>
                      <tr style="color:#1565C0;">
                        <td class = "uppertable" ><b>B :</b></td>
                        <td class = "lowertable" style = "word-break: keep-all" >그것은 이상주의적인 거야. 그러나 전 세계의 정부가 민간인을 상대로 그들을 사용하지 않을 것이라고 어떻게 확신 할 수 있니?
                        전투 로봇과 킬러 로봇 은 종이 한 장 차이야.</td>
                      </tr>

                    
                      </table>

      

      </div>
     <div class = "line-opinion1">
      </div>
      <h3 class = "border-opinion1 white--text">Questions</h3>
      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think it is a good idea to build military robots instead of humans? Why?</li>
          <li>Will military robots be more effective compared to humans? How?</li>
          <li>Would a robot be a better leader in the future?</li>
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

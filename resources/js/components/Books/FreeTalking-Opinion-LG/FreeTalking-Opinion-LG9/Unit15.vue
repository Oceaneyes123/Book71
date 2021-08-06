<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/grayscale-sad-girl-being-cyberbullied-social-media_53876-98440.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Cyberbullying should be considered a crime
      </h1>
      </transition>
    </v-layout>
  </v-img>

  <div class = "line-top-lg">
  </div>
  <h3  class = "lower-header-lg white--text">Topic</h3>

  <div style = "padding : 16px; line-height: 1.6;">

    <table class = "standard-table">

    <tr>
      <td class = "uppertable" ><b>David :</b></td>
      <td class = "lowertable" >Cyberbullying should be illegal. If you have spent any time online, you will know how hurtful people can be online. They are even more critical online than in person. Some people have even killed themselves because of the cyberbullying. The government should outlaw cyberbullying.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Cyberbullying should not be made illegal. Even though it is a tragedy that some people killed themselves, people are still free to say what they want to say. We live in a free society, so we have to be able to deal with the good and the bad things that we hear. We cannot limit people’s speech just because of a few extreme cases.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>cyberbullying</b> 사이버 폭력
        </p>
        <p>
          <b>critical</b> (앞으로의 상황에 영향을 미친다는 점에서) 대단히 중요한[중대한]
        </p>
        <p>
          <b>outlaw</b> (특히 옛날 범죄를 저지른) 도망자, 범법자; 법의 보호를 받지 못하는 사람
        </p>
        <p>
          <b>tragedy</b> 비극(적인 사건)
        </p>
         
          
         
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >사이버 왕따는 불법으로 다루어 져야 한다. 만일 당신이 온라인에서 시간을 보낸다면, 당신은 사람들이 얼마나 온라인에서 상처를 받을 수 있는지를 알 것이다. 그들은 개인보다 온라인에서 더 비판적이다. 어떤 사람들은 사이버 왕따 때문에 자살하기까지 한다. 정부는 사이버 왕따를 금지해야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >사이버 왕따는 불법으로 다루지 말아야 한다. 비록 일부 사람들이 자살을 했다는 비극이 있지만, 사람들은 아직도 그들이 원하는 것을 자유롭게 말할 수 있다. 우리는 자유 사회에 살고 있으므로 우리가 듣는 좋은 것들과 나쁜 것들을 다룰 수 있어야 한다. 몇 가지 극단적인 경우 때문에, 우리는 사람들의 발언을 제한할 수 없다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think cyberbullying should be considered a crime? Why or why not?</li>
          <li>What are the differences between freedom of speech and stating an opinion from cyberbullying?</li>
          <li>Do you think that cyberbullying should be illegal? Why or why not?</li>
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

</style>

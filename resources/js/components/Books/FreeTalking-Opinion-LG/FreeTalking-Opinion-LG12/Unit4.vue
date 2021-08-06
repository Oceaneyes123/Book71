<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://img.freepik.com/free-photo/copy-space-headphones-laptop-air-concept_23-2148695261.jpg?size=338&ext=jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Are Headphones Bad for Your Ears? </h1>
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
      <td class = "lowertable" >Headphones can damage your ears. You should limit the volume and how long you listen to something, but many people aren’t aware of these precautions. Prof. David McAlpine, director of research at the Australian Hearing Hub, said, “We are very concerned. Most people who are working or traveling are now wearing ear buds, but they don’t necessarily know the sound levels they’re exposing themselves to.” According to audiorecovery.com, earphones for the iPhone “can hit noise levels of 112 decibels for the wearer, leading to hearing damage in minutes.” Plus, according to the World Health Organization, more than 1 billion teenagers are in danger of hearing loss from portable audio devices, such as smartphones. In addition, using headphones frequently can lead to more than just hearing loss. It can cause tinnitus, which is a ringing sensation in the ears. Australian DJ Elizabeth Rose said, “After gigs, I would just hear a constant fuzz.” Thus, headphones should be used in moderation.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Headphones are safe for your ears as long as you use them properly. Listening to music with headphones at maximum volume for extended periods can cause damage to your hearing. However, any loud sound can cause this. For instance, concerts feature loud music blasting from enormous speakers. According to audiorecovery.com, rock concerts can cause damage to your hearing in less than a minute. Even listening to highway traffic for more than an hour can cause temporary hearing loss. According to many audiologists, you should follow the “60-60 rule.” It involves listening to something at 60 percent of the max volume for no longer than 60 minutes. Furthermore, some headphones are safer than others. According to Prof. McAlpine, “You should think about getting some noise-cancelling headphones, because they stop you from increasing the sound level of your audio to get above the background noise.” In conclusion, it’s unreasonable to blame hearing loss on headphones.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>aware</b> 알고 있는
        </p>
        <p>
          <b>precaution</b> 예방책
        </p>
        <p>
          <b>tinnitus</b> 귀울림
        </p>
        <p>
          <b>sensation</b> 느낌
        </p>
        <p>
          <b>gig</b> 공연
        </p>
        <p>
          <b>constant</b> 끊임없는
        </p>
        <p>
          <b>in moderation</b> 적당히
        </p>
        <p>
          <b>maximum</b> 최대의
        </p>
        <p>
          <b>extended</b> 긴
        </p>
        <p>
          <b>temporary</b> 일시적인
        </p>
        <p>
          <b>audiologist</b> 청각학자
        </p>
        <p>
          <b>valid</b> 타당한
        </p>
  </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >헤드폰은 청력을 손상시킬 수 있다. 음량과 듣는 시간을 제한시켜야 하지만, 많은 사람들은 이러한 예방책들을 알지 못한다. 호주 청력 허브의 연구소장인 데이비드 맥알파인 교수는 “우리는 매우 우려합니다. 일을 하거나 여행을 하는 대부분의 사람들이 이제 초소형 헤드폰을 착용하지만 그들은 그들이 자신들을 노출시키는 음량의 수준에 대해서 반드시 알지는 못합니다.” 라고 말했다. audiorecovery.com에 따르면, 아이폰을 위한 이어폰은 “착용한 사람에게 112 데시벨의 소음 수준까지 미칠 수 있는데, 이것은 몇 분 안에 청력 손상을 일으킬 수 있다.” 게다가 세계보건기구에 따르면, 10억명이 넘는 10대들이 스마트폰과 같은 휴대 가능한 오디오기기로부터의 청력 상실의 위험에 있다. 게다가 헤드폰을 자주 사용하는 것은 청력 상실 이상의 결과를 가져올 수 있다. 그것은 귓 속에 울리는 느낌인 이명을 발생시킬 수 있다. 호주의 DJ인 엘리자베스 로즈는 “공연 후에는 저는 계속해서 지직거리는 소리가 그냥 들려요.” 라고 말했다. 그러므로 헤드폰은 적당히 사용해야 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >헤드폰은 그것을 적절히만 쓴다면 당신의 귀에 안전하다. 긴 시간 동안 헤드폰으로 최대의 음량으로 음악을 듣는 것은 당신의 청력에 손상을 발생시킬 수 있다. 그러나 어떤 큰 소리도 이것을 발생시킬 수 있다. 예를 들어 콘서트는 거대한 스피커에서 쾅쾅 울리는 큰 음악을 포함한다. Audiorecovery.com에 따르면, 록 콘서트는 1분도 안 돼서 당신의 청력에 손상을 일으킬 수 있다. 심지어 고속도로의 교통 소리를 한 시간 이상 듣는 것도 일시적인 청력 손상을 일으킬 수 있다. 많은 청력학자에 따르면 당신은 “60-60 법칙”을 따라야만 한다. 그것은 60분 이내에 최대 음량의 60퍼센트로 듣는 것과 관련이 있다. 게다가 일부 헤드폰은 다른 것보다 더 안전하다. 맥알파인 교수에 따르면 “소음제거 헤드폰을 구입하는 것을 고려해봐야 하는데, 이것은 그것이 주변 소음 이상으로 음량 수준을 올리는 것을 방지하도록 하기 때문이다. 결론으로, 헤드폰에 청력 상실 탓을 하는 것은 불합리하다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How often do you use headphones?</li>
          <li>Are headphones harmful for ears?</li>
          <li>Which do you think is more convenient: using wired headphones or wireless headphones?</li>
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

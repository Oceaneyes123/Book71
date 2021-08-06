<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/detail-plastic-bottles-recycling_150588-105.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Bottled water has done more harm than good
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
      <td class = "lowertable" >The massive amount of bottled water being produced today is doing more harm than good. Many places in the world are very far behind Korea when it comes to recycling. The amount of trash that is produced by people who drink bottles of water every day is extremely huge. Bottles also take up a large amount of space in garbage and recycling centers. It would be much better if all people used reusable bottles and water filters in order to minimize the amount of plastic that gets discarded every day.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Bottled water has made cold and clean water readily available. Water is a very important substance, so anything that increases its availability is a good thing. Likewise, bottled water has allowed many people to have clean drinking water even if the natural sources of water around them are polluted or unsafe to consume. This means that bottled water has been an effective way of reducing waterborne illnesses across the globe.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>possible</b> 가능한
        </p>
        <p>
          <b>be delivered</b> 배달되다
        </p>
        <p>
          <b>produce</b> 생산하다
        </p>
        <p>
          <b>when it comes to</b> ~에 관해서
        </p>
        <p>
          <b>discard</b> 버리다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >오늘 날 생산되는 병에 든 물의 막대한 양은 득보다 실이 많습니다. 재활용에 관해서, 전세계의 많은 곳은 한국보다 훨씬 뒤쳐져 있습니다. 매일 병에 든 물을 마시는 사람들에 의해 생산되는 폐기물의 양은 너무나 거대합니다. 병들은 또한 쓰레기장과 재활용 센터에서 많은 공간을 차지합니다. 만일 모든 사람들이 매일 버려지는 플라스틱의 양을 최소화하기 위해, 재사용할 수 있는 병들과 물 필터를 사용한다면 훨씬 더 좋을 것입니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >병에 든 물로 인해 차갑고 깨끗한 물을 쉽게 이용할 수 있게 되었습니다. 물은 매우 중요한 물질이므로, 물을 더 많이 사용할 수 있도록 하는 모든 일이 좋은 일입니다. 이와 같이, 병에 든 물로 인해, 비록 천연 수원(水源)이 오염되거나 마시기에 안전하지 않더라도 사람들이 깨끗한 물을 마실 수 있게 되었습니다. 이것은 병에 든 물이 전세계에 걸쳐 물에 의해 퍼지는 병들을 감소시키는 효과적인 방법이라는 것을 의미합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>How often do you drink bottled water?</li>
          <li>Do you believe bottled water is safe to drink?</li>
          <li>What effect does bottled water have on the environment?</li>
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

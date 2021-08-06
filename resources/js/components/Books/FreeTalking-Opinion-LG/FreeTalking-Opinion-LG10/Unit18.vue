<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/red-hot-hibiscus-tea-glass-mug-concrete-with-dry-hibiscus-petals_114579-4164.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Stop Taking Cold Medicines?
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
      <td class = "lowertable" >Fall and winter are peak seasons for common colds, and as a result, a lot more people visit drug stores around this time of year at the first notice of a sniffle or a sore throat. Colds can be quite a distraction to daily tasks and routines and cause feelings of discomfort. And somehow, the misconception that cold medicines work has been engraved in today’s modern society, causing people to mindlessly take all sorts of cold medication without clearly knowing the benefits or side effects.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >According to The Independent, colds can be very dangerous. They also say that babies and the elderly have higher chances of catching colds and that they are the ones largely responsible for spreading them. Taking medication for the common cold serves as a precautionary measure to prevent it from spreading. In addition, ignoring the common cold and not doing anything about it can lead to pneumonia, an infection in the lungs. </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>sniffle</b> 훌쩍거림
        </p>
        <p>
          <b>sore throat</b> 인후염
        </p>
        <p>
          <b>mindlessly</b> 의식이 없이, 지성이 없이
        </p>
        <p>
          <b>side effects</b> 부작용
        </p>
        <p>
          <b>lead to</b> ~로 이어지다
        </p>
        <p>
          <b>pneumonia</b> 폐렴
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >가을과 겨울은 감기에 제일 많이 걸리는 계절이고, 그 결과로서, 더 많은 사람들은 이 맘 때쯤 재채기나 혹은 인후염의 첫 증상을 보일 무렵 약국을 방문한다. 감기는 일상적인 업무와 일상에 대단히 방해가 될 수 있고, 불편한 느낌을 불러일으킬 수 있다. 그리고 어쨌든, 감기약이 효험이 있다는 오해는 오늘날의 현대 사회에 깊이 새겨져 있어서, 사람들이 유익이나 혹은 부작용을 정확하게 알지 못하고 의식 없이 모든 종류의 감기약을 복용하게 만들고 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >인디펜던트지에 의하면, 감기는 정말 위험할 수 있다고 한다. 또한 아이들과 어르신들이 감기에 걸릴 확률이 더 높고, 그들이 다른 사람들에게 가장 많이 옮긴다고 한다. 감기약을 복용하는 것은 더 이상 병을 옮기지 않도록 미리 대처하는 것이다. 게다가, 감기를 무시하고 아무것도 하지 않으면 오히려 폐의 감염으로 발생하는 폐렴으로 이어질 수 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you often get colds? How do you treat it?</li>
          <li>What kind of medication do you prefer to take when you have colds?</li>
          <li>Do you think colds can be dangerous? Why or why not?</li>
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

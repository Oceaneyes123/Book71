<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/colorful-plastic-tableware-turquoise-background_23-2148309740.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Ban The Production Of New Plastic?
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
      <td class = "lowertable" >Our world’s overuse of plastic has reached outrageous proportions. Individually wrapped miniature snacks and bottles of soft drinks fill the many landfills of our planet. At least 48% of the world’s trash is made up of plastic bags, lids, and beverage bottles. The world’s largest landfill, Puente Hills, takes in 12,000 tons of garbage a day and currently holds 3.7 million tons. With the discovery of plastic-eating worms, and the invention of biodegradable plastics, it makes sense for us to stop creating new plastic. We should focus on recycling and reusing plastic. Statistically speaking, recycling one ton of plastic can save 5,774 kWh of energy, 1,000-2,000 gallons of gasoline, 685 gallons of oil, 30 cubic yards of landfill space, and 48,000 gallons of water. When we see statistics like this, isn’t it clear that we can recycle our plastics and start reducing the amount of plastic pollution in the environment? </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >As bad as plastic pollution is, it is worse when we consider how hard it is to recycle. A study carried out in the UK found that the amount of packaging in a regular shopping basket that cannot be effectively recycled ranged from 21% to 40%. There are a variety of reasons for this, but the main reason is that there are a number of substances present in processed plastic such as dyes, fillers, and other additives. This makes it difficult for recycling plants to properly break down the plastic and reuse it. In addition, the use of factories which recycle plastic may save energy, but due to some highly durable plastics and the overall amount of waste created, it is actually more expensive to break them down. Until a proper solution for plastic recycling or degradation is found, a ban on new plastic will leave companies scrambling to find a way to cleanly bottle, package, and store essential items such as drinks and food.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>ban</b> 금지하다
        </p>
        <p>
          <b>overuse</b> 남용, 남발
        </p>
        <p>
          <b>landfill</b> 쓰레기 매립지
        </p>
        <p>
          <b>biodegradable</b> 생분해[자연분해]성의
        </p>
        <p>
          <b>statistically</b> 통계상으로
        </p>
        <p>
          <b>gallon</b> 갤런
        </p>
        <p>
          <b>packaging</b> 포장
        </p>
        <p>
          <b>additive</b> 첨가물, 첨가제
        </p>
        <p>
          <b>degradation</b> 악화
        </p>
        <p>
          <b>item</b> 품목
        </p>
       </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >우리 세상의 과도한 플라스틱 사용은 터무니없는 비율에 이르렀다. 각각 하나씩 포장된 작은 스낵과 음료수의 뚜껑은 지구의 많은 매립지를 채웠다. 세상의 적어도 48퍼센트의 쓰레기는 비닐 봉지, 뚜껑, 그리고 음료수 병으로 만들어져 있다. 세상의 가장 큰 매립지인 푸엔트 힐스는 매일 1만 2,000톤의 쓰레기를 받고, 현재 370만 톤을 유지하고 있다. 플라스틱을 먹는 벌레와 생분해성 플라스틱의 발견으로, 우리가 새로운 플라스틱의 생산을 멈추는 것은 일리가 있다. 우리는 플라스틱의 재활용과 재사용에 집중해야만 한다. 통계학적으로 말해서, 1톤의 플라스틱을 재활용하면 5,774킬로와트의 에너지, 1000-2000갤런의 가솔린, 석유에서 685갤런의 기름을, 매립지에서 30입방 야드와 물에서 4만 8,000갤런을 절약할 수 있다. 우리가 이와 같은 통계를 본다면, 우리가 플라스틱을 재활용하고 환경에서 플라스틱 오염의 양을 줄이는 것은 분명하지 않은가?</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >플라스틱 오염만큼 심각하지만, 고려해 볼 때 그것을 재활용하기 얼마나 어려운지는 더 심각하다. 영국에서 시행된 한 연구는 효과적으로 재활용 될 수 없는 보통 쇼핑 바구니에 있는 (품목들의) 포장재의 양이 21%에서 40%에 걸쳐 있음을 발견하였다. 이에 대한 다양한 이유가 있지만, 주요한 이유는 염료, 충전제들 그리고 다른 첨가물과 같은 가공된 플라스틱에 존재하는 수많은 물질이 있다는 것이다. 이것은 재활용품 처리 공장이 적절히 플라스틱을 분해하고 재사용하는 것을 어렵게 만든다. 게다가, 플라스틱을 재활용하는 공장의 사용은 에너지를 아낄 수 있지만 몇몇 극도로 내구성이 좋은 플라스틱과 만들어지는 쓰레기의 전체적인 양으로 인해 그것들을 분해하기 더 비싸다. 플라스틱 재활용과 분해에 대한 적절한 해결안을 찾기 전까지 새로운 플라스틱 제조의 금지는 회사들이 깨끗하게 병, 포장재를 재활용하고 음료와 음식과 같은 중요한 품목을 저장하는 방법을 서둘러 찾게 할 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are the advantages of plastic bags?</li>
          <li>What are the downsides of using plastic bags?</li>
          <li>How can banning the production of new plastic affect the environment?</li>
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

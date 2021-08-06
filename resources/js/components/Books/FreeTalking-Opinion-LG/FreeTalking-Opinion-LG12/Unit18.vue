<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/men-casual-fashion-outfit-wooden-table-top-view_1357-155.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">New Goods Versus Used Goods
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
      <td class = "lowertable" >New items are undoubtedly much better than used items. First, they are less likely to have any defects. For instance, used blankets may have stains and missing patches of fabric. New blankets, however, are aesthetically more pleasing and are more hygienic. Moreover, it is difficult ? and sometimes even impossible ? to buy a used item with a warranty. A typical warranty only lasts for a few years, so you’re out of luck if your used item breaks or stops working altogether. In addition, according to Wes Moss, a writer for thebalance.com, you should buy new computer software because there is “a very good chance that used software package you see online is pirated.” Humidifiers should be new as well. Moss also wrote, “Many pieces of protective equipment are designed to withstand one impact. Since you can’t know the item’s true history, always buy new protective gear. The risk to you or your kids isn’t worth saving a few bucks.” I agree!</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Used goods are infinitely better. First of all, they are cheaper than new goods. Some used items cost half of the original price, and some are even less expensive than that. Online, a new air conditioner costs around W500,000, but refurbished versions of the same product are only W250,000 each. However, this does not mean that they are of lower quality. Refurbished items are usually products that were returned in near perfect condition. There’s something called the Diderot effect, though. It’s a social phenomenon that makes people want only the latest and greatest products. The Diderot effect makes people neglect what they already possess. We need to control our urge to buy new things and try to open up our minds and accept the fact that used items are just as good as new ones. Also, you should buy used baby clothes unless you’re going to keep them forever. Be smart and buy used goods.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>undoubtedly</b> 의심할 여지없이, 확실히
        </p>
        <p>
          <b>defect</b> 결함
        </p>
        <p>
          <b>stain</b> 얼룩
        </p>
        <p>
          <b>aesthetically</b> 미적으로
        </p>
        <p>
          <b>warranty</b> (제품의) 품질 보증서
        </p>
        <p>
          <b>pirated</b> 불법 복제된
        </p>
        <p>
          <b>humidifier</b> 가습기
        </p>
        <p>
          <b>withstand</b> 견뎌 내다
        </p>
        <p>
          <b>infinitely</b> 대단히, 엄청
        </p>
        <p>
          <b>refurbish</b> 새로 꾸미다[재단장하다]
        </p>
        <p>
          <b>phenomenon</b> 현상
        </p>
        <p>
          <b>possess</b> 소유하다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >새 제품은 의심할 여지 없이 중고제품보다 훨씬 낫다. 우선, 그들은 결함을 가지고 있을 가능성이 적다. 예를 들어, 중고 담요에는 얼룩이나 없어진 천 조각이 있을 수도 있다. 하지만, 새 담요는 미관상 더 보기가 좋고 보다 위생적이다. 게다가, 보증서가 있는 중고 제품을 구매하기는 어려우며, 때로는 심지어 불가능하기까지 하다. 일반적인 보증서는 몇 년 동안만 지속되므로, 만약 중고 제품이 고장 나거나 아예 작동을 멈추면 당신은 운을 다한 것이다. 또한 thebalance.com(더 밸런스)의 저술가인 웨스 모스(Wes Moss)에 따르면 “온라인에서 볼 수 있는 중고 소프트웨어 패키지는 불법 복제(해적판)되었을 가능성이 매우 높기” 때문에 새 컴퓨터 소프트웨어를 구입해야 한다고 한다. 가습기도 새 제품이어야 한다. 모스는 또한 “많은 보호 장비들이 한번의 충격을 견딜 수 있도록 설계되어 있다. 그 물건의 실제 역사를 알 수 없으므로, 항상 새로운 보호 장비를 구매하라. 당신이나 당신의 자녀들에게 닥칠 위험은 몇 푼을 아낄 가치가 없다”라고도 썼다. 나는 동의한다!</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >중고 제품이 훨씬 더 낫다. 우선, 그들은 새 제품보다 더 싸다. 어떤 중고제품들은 원래 가격의 반값이고, 어떤 것들은 심지어 그보다 더 싸다. 온라인에서, 새 에어컨의 가격은 한화 약 50만 원이지만, 같은 제품의 리퍼 버전은 각각 단 25만 원 밖에 되지 않는다. 그러나, 이것은 그들의 질이 낮다는 것을 의미하지 않는다. 리퍼 상품은 보통 거의 완벽한 상태로 반품된 제품들이다. 하지만, 디드로 효과(Diderot effect)라 불리는 것이 존재한다. 이는 사람들이 가장 최신의 가장 최고 제품만을 원하게 만드는 사회적 현상이다. 디드로 현상은 사람들이 이미 소유하고 있는 것들을 방치하도록 만든다. 우리는 새로운 것을 사고 싶은 충동을 억제하고, 마음을 열고자 노력하며, 중고 제품도 새 제품 못지 않게 좋다는 사실을 받아들여야 한다. 또한, 아기 옷을 영원히 간직할 생각이 아니라면 중고 아기 옷을 사야한다. 현명해 지라, 그리고 중고 제품을 사라.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are the advantages of buying new goods?</li>
          <li>Have you tried purchasing things at a flea market?</li>
          <li>What are the disadvantages of buying used goods?</li>
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

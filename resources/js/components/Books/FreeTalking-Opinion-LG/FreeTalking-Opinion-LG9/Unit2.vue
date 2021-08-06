
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/child-playing-home_1328-1121.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Ads Targeting Children Be Restricted?
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
      <td class = "lowertable" >In 2005, the Institute of Medicine released a report stating that television advertising strongly influences what children 12 years old and younger eat. “The foods advertised are predominantly high in calories and low in nutrition the sort of diet that puts children’s long-term health at risk,” said J. Michael McGinnis, the chairman of the report committee. The researchers concluded that the food industry should spend its advertising budget on nutritious food and drinks, a sentiment echoed by Iowa Senator Tom Harkin. “We like to think that Sponge Bob Square Pants and Shrek are likable, kid-friendly characters, but they’re being used to manipulate vulnerable children,” he said. “The industry must stop pushing junk food on our kids.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Although children should not be blitzed with junk food advertisements on a constant basis, at the end of the day, parents are ultimately responsible for what their children eat. When children become adults, they will be wise enough to make their own decisions about eating habits. However, when they are young, parents should instill positive eating habits and encourage healthy eating. Blaming the advertising industry is just bad, lazy parenting.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>influence</b> (사람의 행동사고에) 영향을 주다[미치다]
        </p>
        <p>
          <b>predominantly</b> 두드러진, 뚜렷한
        </p>
        <p>
          <b>manipulate</b> (흔히 교묘하고 부정직하게 사람·사물을) 조종하다
        </p>
        <p>
          <b>vulnerable</b> (~에) 취약한, 연약한(신체적·정서적으로 상처받기 쉬움을 나타냄)
        </p>
        <p>
          <b>blitzed</b> 기습 공격
        </p>
        <p>
          <b>instill</b> 한 방울씩 떨어뜨리다
        </p>
      </div>
       
      
      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >2005년, 의학 연구소는 텔레비전 광고는 12살이하의 어린이들이 먹는 것에 큰 영향을 끼친다는 보고를 발표했다. “광고되는 음식들은 장기적인 아이들의 건강을 위협하는 칼로리가 높고 영양이 낮은 음식들이다”라고 J. Michael McGinnis 위원회 보고의 회장은 말했다. 연구원들은 음식 산업은 그들의 광고 예산을 영양이 있는 식품과 음료에 써야 한다고 연구원들은 결론 지었는데, 이점에 관해 아이오아 출신 미 상원의원 Tom Harkin도 동의하고 있다. “우리는 스폰지밥 네모바지와 슈렉이 호감이 가고 아이들과 친화적인 캐릭터라고 생각하지만 그것들이 취약한 아동들을 조종하는 데 사용되고 있다”고 그는 말했다. “이 산업은 불량 식품을 아이들에게 강요하는 것을 멈춰야 한다.”</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >아이들이 불량 식품 광고에 지속적으로 공격을 받아서는 안되지만, 아이들이 무엇을 먹는지에 관해서는 결국에는 부모님에게 책임이 있다. 아이들이 성인이 되면, 그들은 식습관에 관해 결정 할 수 있을 만큼 현명해 질 것이다. 하지만 그들이 어릴 때에는, 부모들이 긍정적인 식습관이 스며들도록 해야 하고 건강한 식습관을 기를 수 있도록 해야 한다. 광고를 비난하는 것은 단지 옳지 않고 게으른 방법으로 부모 노릇을 하는 것일 뿐이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think advertisements have a lot of impact on audiences? Why or why not?</li>
          <li>Do you think some advertising companies purposely target children? Why?</li>
          <li>Should parents monitor what their kids watch on TV? Why?</li>
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

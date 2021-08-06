<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/young-mother-playing-with-her-little-baby-bed_273609-13611.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Housewives vs. Career Mothers
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
      <td class = "lowertable" >We are debating the obvious. Housewives can be both educated and uneducated but the fact that they spend more time with their children means that they put in a greater effort, and since they are not preoccupied with their job they pay the close attention needed to keep their children out of trouble. A busy mother will be humming about maybe losing the promotion to her arch enemy!</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >All this attention can be suffocating. Children need space to grow. Traditionally housewives had many children, therefore each child had the room to grow individually and independently-Attention was divided. Now people have fewer children and mothers can be overly involved in their little ones’ lives. This makes it difficult for children to develop the useful skills of independence required to ultimately stand on their own feet, make friends etc. A housewife is usually busy tending to the house or doing the more practical jobs of raising children, such as feeding them, rather than actually spending time with them and being loving / affectionate.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>educated</b> 많이 배운, 학식 있는
        </p>
        <p>
          <b>preoccupied</b> (어떤 생각·걱정에) 사로잡힌
        </p>
        <p>
          <b>traditional</b> 전통
        </p>
        <p>
          <b>affectionate</b> 애정
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >우리는 너무 뻔한 것을 토론하고 있다. 전업주부들은 잘 교육을 받고 교육을 받지 못할 수도 있지만 그들이 아이들과 더 많은 시간을 보내는 사실은 그들이 더 많은 노력을 하고, 그들이 일에 사로잡혀있지 않기 때문에 아이들을 궁지에서 구해주기 위해 세심한 주의를 기울인다는 것을 의미한다. 바쁜 엄마는 아마도 그녀의 최대의 적에게 승진을 뺏길지도 모른다며 흥얼거릴 것이다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >모든 이러한 관심은 숨이 막힐 수 있다. 어린이들은 성장할 공간이 필요하다. 전통적으로 전업주부들은 많은 아이들을 가지고 있다, 따라서 각 아이는 개인적으로 독립적으로 자랄 공간이 있다-관심은 나뉜다. 현재 사람들은 그들의 작은 아이들의 삶에 전적으로 관여될 수있다. 이는 아이들이 그들만의 힘으로 결국 설 수 있는데 필요한 독립성을 위한 유용한 기술을 개발하는 것을 어렵게 한다. 전업주부는 보통 집안일을 하거나 아이들을 키우는 더 현실적인 일을 하는 것으로 바쁘다, 실제로 그들과 함께 시간을 보내고 애정 어리게 하기 보다 아이들에게 식사를 챙기는 것과 같은.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What can you say about women who choose to become a housewife? How about those who opted to be a career mother?</li>
          <li>Do you think there is a difference with the way a child grows up if their mom is a housewife? Why?</li>
          <li>Would you choose to be a housewife or a career mother? Why?</li>
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

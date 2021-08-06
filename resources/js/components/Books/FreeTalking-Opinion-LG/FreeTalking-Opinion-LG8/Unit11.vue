
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/young-boy-wearing-suit-as-his-dream-job_53876-94584.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Children Must Work Too?
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
      <td class = "lowertable" >Working teaches children valuable skills. Children who work learn such valuable life skills as self responsibility, independence and the relationship between time and money. Quite simply, children need money too. Not all parents can afford to give their children good lives. Some can’t even afford to keep them fed and clothed properly. Children should have the opportunity to make money to improve their quality of life.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >There are better ways besides sending a child to work to learn life skills. Self responsibility and independence can be taught through homework and study. This will teach children to effectively manage their own time. It is something that parents need to demonstrate to their children. This would be much more effective than merely shipping their children off to a place of employment.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>self-responsibility</b> 자기 책임으로 하다
        </p>
        <p>
          <b>independence</b> 독립
        </p>
        <p>
          <b>life skill</b> 기술
        </p>
        <p>
          <b>demonstrate</b> (행동으로) 보여주다
        </p>
         
         
         
         
        
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >일하는 것은 아이들에게 가치 있는 능력을 가르친다. 일하는 어린이들은 자기 책임, 독립 그리고 시간과 돈 사이의 관계와 같은 그러한 가치 있는 삶의 능력을 배운다. 간단히 말해, 어린이들 역시 돈이 필요하다. 모든 부모들이 전부 아이들에게 편안한 삶을 제공해 줄 여유가 없다. 일부 부모들은 그들에게 계속해서 먹을 것을 주고 적절히 옷을 입힐 수 없다. 어린이들은 삶의 질을 개선하기 위해 돈을 벌 기회를 가져야만 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >삶의 기술을 터득하기 위해 아이를 직장에 보내는 것 외에 더 좋은 방법들이 있다. 자기 책임과 독립은 숙제와 공부를 통해 배울 수 있다. 이는 아이들에게 그들만의 시간을 효율적으로 관리하도록 가르칠 것이다. 부모들이 아이들에게 설명할 필요가 있는 것이다. 이는 단지 직장에 아이들을 보내는 것보다 훨씬 더 효과적일 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think children should be given an opportunity to work? Why?</li>
          <li>What kinds of jobs do you think should be allowed for a child?</li>
          <li>At what age do you think we can allow children to work? Why?</li>
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

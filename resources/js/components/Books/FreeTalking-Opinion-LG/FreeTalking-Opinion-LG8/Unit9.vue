<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/mother-children-playing_1398-4994.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">How Do You Feel about Nannies?
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
      <td class = "lowertable" >In many cases, it can be beneficial for a child to be cared for by someone other than his or her parents. Many families need two sources of income and mothers with large families need help. Yet, sometimes parents just want a break. We should take the view that what's right for the parents will, in most cases, be right for their children.If a mother works a few hours a week to keep her CV fresh, or simply to be around other adults, then she will most likely go back to caring for her child with a renewed enthusiasm. Meanwhile, it’s not such a bad thing for the child to spend time at a daycare center, allowing them to socialize with his or her own age group.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Having children requires sacrifices. That may mean having less money or even sacrificing a career. After all, we’re talking about the development of a human being at the most vulnerable and influential stage of their lives. Mistakes at this point will cause the child problems for years, if not decades, to come. Parents should understand and be willing to make the necessary sacrifices for their child’s upbringing.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>nanny</b> 보모
        </p>
        <p>
          <b>renew</b> 결의를 새롭게 하다
        </p>
        <p>
          <b>vulnerable</b> 연약하다
        </p>
        <p>
          <b>influential</b> 영향력이 있다
        </p>
        <p>
          <b>upbringing</b> 양육, 훈육, (가정) 교육
        </p>
         
       </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >대부분의 경우, 아이들의 부모님들보다 누군가가 보살피는 것이 아이에게 이로울 수 있다. 많은 가족들은 소득의 두 가지 공급원이 필요하고 대가족의 어머니는 도움을 필요로 한다. 하지만, 이따금 부모들은 휴식을 원한다. 우리는 부모를 위한 권리가 대부분의 경우 아이의 권리가 될 것이라는 견해를 취해야 한다. 만약 어머니가 이력서를 지키기 위해 일주일에 몇 시간 일하거나 다른 어른들과 함께 한다면, 그녀는 새로워진 열정과 함께 아이를 보살피는 것을 뒷전으로 할 것이다. 반면, 또래 집단과 어울리는 것을 허락하면서, 아이를 위해 탁아소에서 시간을 보내는 것은 안 좋다. </td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >아이를 갖는 것은 희생을 요구한다. 돈을 덜 쓰거나 경력을 희생시킬지도 모른다. 결국, 우리는 인생에서 가장 연약하고 영향력이 큰 단계의 인간의 성장에 대해 얘기하고 있다. 이 시점에서의 실수는 10년이 아니더라도 수년간 아이들에게 문제를 일으킬 것이다. 부모들은 이해해야만 하고 아이들의 양육에 필요한 희생을 기꺼이 할 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What can you say about having a nanny taking care of your children?</li>
          <li>Do you think getting a nanny is helpful? Why or why not?</li>
          <li>Would you consider getting a nanny or just hire a baby-sitter?</li>
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

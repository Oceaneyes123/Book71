<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/man-using-scotch-tape-box-secure-it-moving-out_23-2148647470.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">People should move out of their family's house before marriage
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
      <td class = "lowertable" >People should move out of their family’s house before marriage. When you live with your family, your parents generally provide you with all the basic necessities, such as food, shelter, and water. However, after you become an adult, it is good to learn how to provide these necessities for yourself. Learning how to do this makes you independent. Also, living independently means that you will have to make many decisions alone. This will teach you how to be a responsible and mature adult.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >People should not move out of their family’s house before marriage. Time with your family is precious. Once you get married, you will have your own house and family to care for. Therefore, it is better to live at home until you get married. Furthermore, moving out of the family home before marriage can be expensive. It is better to save money by living with your parents. This way, when you get married, you will have money to support your new life with your spouse.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>necessity</b> 필수품
        </p>
        <p>
          <b>independent</b> (사람이) 태어난 곳의
        </p>
        <p>
          <b>responsible</b> 관계
        </p>
        <p>
          <b>precious</b> 귀중한
        </p>
        <p>
          <b>spouse</b> 짝, 배우자
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >결혼 전에 부모님으로부터 독립해 살아야 한다. 가족과 함께 살면, 일반적으로 부모님이 음식, 집, 그리고 물과 같은 기초 필수품을 제공해 줄 것이다. 하지만, 어른이 되고 나면, 이러한 필수품을 스스로 얻는 법을 배우는 것이 좋다. 이렇게 하는 방법을 배우는 것은 당신을 독립적으로 만들어 준다. 또한, 독립적으로 산다는 것은 당신이 많은 결정을 혼자서 해야 한다는 것을 의미한다. 이것은 당신이 책임감 있고 성숙한 어른이 되는 법을 가르쳐 줄 것이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >결혼 전에 부모님으로부터 독립해 살면 안 된다. 가족과의 시간은 소중하다. 결혼을 하고 나면, 당신은 당신이 돌보아야 할 집과 가족이 생긴다. 따라서, 결혼 전까지 집에 사는 것이 더 낫다. 게다가, 결혼 전에 독립해서 사는 것은 돈이 많이 들 수 있다. 부모님과 함께 살면서 돈을 절약하는 것이 더 낫다. 이렇게 하면, 당신이 결혼할 때, 당신의 배우자와 함께 새 삶을 지원할 돈이 있을 것이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>At what age do you think it is ideal for a person to move out of their parent’s house?</li>
          <li>Do you think moving out before marriage is necessary? Why or why not?</li>
          <li>In your opinion, what are the advantages or disadvantages of moving out?</li>
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

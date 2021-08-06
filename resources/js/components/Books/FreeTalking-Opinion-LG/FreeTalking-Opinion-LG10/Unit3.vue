
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/young-businessman-happy-expression_1194-2043.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should pets be allowed to enter public spaces?
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
      <td class = "lowertable" >Pets should be allowed to enter public spaces. Pet owners cannot just lock up their pets at home all the time. Some animals such as dogs actually develop health problems if they do not exercise every day. Therefore, owners need to take their dogs out to public places where they can move around enough inside. Furthermore, public spaces like parks and playgrounds are free spaces open to everyone. We cannot prohibit pets from public spaces just because some people do not like them.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Pets should not be allowed to enter public spaces. I am allergic to dogs. I cannot stop sneezing whenever I am around them. I hate going to public spaces where there are dogs. I cannot enjoy my time with my friends and family when there are animals around. Pet owners should be considerate of people who have allergies to animals. They should enjoy their pets in the privacy of their own homes. Why do they need to bring them to public places? Not everyone likes animals!</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>allergic</b> 알레르기가 있는
        </p>
        <p>
          <b>develop</b> (병이) 생기다
        </p>
        <p>
          <b>prohibit</b> 금지하다
        </p>
        <p>
          <b>sneeze</b> 재채기하다
        </p>
        <p>
          <b>considerate</b> 사려 깊은
        </p> 
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >애완 동물이 공공 장소에 출입할 수 있어야 한다. 애완동물 주인들은 자신의 동물들을 항상 집 안에 가두어 놓을 수는 없다. 개와 같은 어떤 동물들은 실제로 매일 운동을 하지 않으면 건강상의 문제를 일으킬 수 있다. 따라서, 주인들은 개들이 그 안에서 충분히 돌아다닐 수 있는 공공 장소에 데려가야 한다. 게다가, 공원이나 운동장과 같은 공공 장소는 누구에게나 열려 있는 자유로운 공간이다. 어떤 사람들이 동물을 좋아하지 않는다고 해서 우리가 애완 동물들의 공공장소 출입을 금지할 수는 없다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >애완 동물이 공공장소에 출입하면 안 된다. 나는 개에게 알러지가 있다. 나는 주변에 개가 있을 때마다 재채기를 멈출 수가 없다. 나는 개가 있는 공공 장소에 가는 것을 싫어한다. 나는 주변에 동물이 있으면 내 친구들, 가족들과 즐거운 시간을 보낼 수 없다. 동물 주인들은 동물에게 알러지가 있는 사람들을 배려해야 한다. 그들은 자신의 집에서 개인적으로 동물들과 놀아야 한다. 그들이 왜 동물들을 공공 장소에 데려와야 하나? 모두가 동물을 좋아하지는 않는다!</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do  you like pets? Have you ever had one?</li>
          <li>Do you think pets should be allowed in public places? Why or why not?</li>
          <li>What are the disadvantages of allowing pets in public places?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/funny-beautiful-housewife-doing-housework-isolated-blue-space_155003-21194.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Homemakers should be paid for their work
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
      <td class = "lowertable" >Homemakers should be paid for their work. My mother is a homemaker. Our family calls her “superwoman” because she does so many things. She wakes up early in the morning to pack us lunches for school. Then she cleans the house, runs errands, and helps my grandparents throughout the day. However, her work day does not end in the evening. She cooks dinner, washes the dishes, and helps us with our homework at night. There is no end to her responsibilities.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Homemakers should not be paid for their work. Who will pay the homemakers? The government? The family? The homemaker’s responsibilities are part of his or her role as a member of the family. It is not an official job that is done to make money. Homemakers work because of their love and sense of responsibility to their families. Also, salaries are usually paid by a boss. But who is the boss of a homemaker? Paying homemakers does not make any sense.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>homemaker</b> (전업) 주부
        </p>
        <p>
          <b>errand</b> 심부름, (다른 사람을 대신해서 해 주는) 일
        </p>
        <p>
          <b>official</b>  (책임자가 공인한) 공식적인, 공인된, 정식의
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >가정주부는 가사업무에 대하여 급여를 받아야 한다. 우리 어머니는 주부이다. 어머니는 정말 많은 일을 하기 때문에, 우리 가족은 어머니를 “수퍼우먼”이라고 부른다. 어머니는 우리가 학교에서 먹을 도시락을 준비하기 위해 아침 일찍 일어난다. 그리고 어머니는 집을 청소하고, 심부름을 하고, 하루 종일 할아버지 할머니를 도와드린다. 하지만, 어머니의 일은 저녁에도 끝나지 않는다. 어머니는 저녁식사를 요리하고, 설거지를 하고, 밤에 우리의 숙제를 도와준다. 어머니의 책임에는 끝이 없다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >가정주부는 가사업무에 대하여 급여를 받으면 안 된다. 누가 주부에게 급여를 지급해야 하는가? 정부인가? 가족인가? 주부의 책임은 가족 구성원으로서 자신의 역할이다. 그것은 돈을 벌기 위해 행해지는 공식적인 직업이 아니다. 주부는 가족을 향한 사랑과 책임감 때문에 일하는 것이다. 또한, 급여는 보통 상사가 지급한다. 하지만 누가 주부의 상사인가? 가정주부에게 급여를 지급하는 것은 말이 되지 않는다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What do you think homemakers do on a daily basis?</li>
          <li>Do you think being a homemaker should be considered a job? Why?</li>
          <li>Based on the amount of things that they need to do, do you think homemaker’s should be paid?</li>
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

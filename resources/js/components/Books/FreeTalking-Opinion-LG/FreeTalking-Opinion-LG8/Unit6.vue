<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/groom-putting-ring-bride-s-finger_1157-338.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Is It Better to Get Married Earlier or Later?
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
      <td class = "lowertable" >Getting married is a matter of personal choice. No one should be able to dictate when a person can or cannot get married, although unfortunately, this is not the case for many girls and women in some cultures. Nevertheless, if a 21-year old couple believes they’re ready for marriage, who are we to stop them?</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Too much attention is given to age, especially in Asian cultures. At the end of the day, age is irrelevant, and marriage shouldn't require a big bank account or a prestigious career. Rather,it requires maturity, commitment, and a passion to share your lives and grow with one another. If those conditions are met, it doesn't matter at what age you get married. Conversely, one should not get married until those conditions are met.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>dictate</b> (특히 듣는 사람이 기분 나쁘게) 지시하다
        </p>
        <p>
          <b>culture</b> (한 국가나 집단의) 문화
        </p>
        <p>
          <b>irrelevant</b> 무관하다
        </p>
        <p>
          <b>prestigious</b> 명망 있는, 일류의
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >결혼은 개인적인 선택이다. 물론 몇몇의 문화의 여성들은 제외 되기는 하지만 어느 누구도 개인이 결혼하는 것에 대해 명령 할 수 없다. 그럼에도 불구하고, 21살의 부부가 그들이 결혼 할 준비가 돼 있다고 한다면 누가 그것을 막을 수 있겠는가?</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >나이에 너무 많이 집중 돼 있다, 특히 아시아 문화에서는 더욱 그렇다. 결국 나중에는, 나이는 무관한 것이고, 결혼은 돈을 위한 것이라거나 명성 있는 직업을 요구하는 것이 아니라는 것이다. 오히려, 그것은 성숙함, 헌신, 그리고 당신의 삶을 나누는 열정을 필요로 하고 서로 성장하는 것이다. 이러한 조건들이 충족 되면, 당신이 결혼하는 나이는 중요하지 않다. 반대로, 이 조건들이 충족 되지 않는다면 결혼을 해선 안 된다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>In your opinion, how old do you think a person should start thinking of getting married? Why?</li>
          <li>Do you think marrying early has its advantages? How about marrying late?</li>
          <li>What do you think are the things a couple should consider before getting married?</li>
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

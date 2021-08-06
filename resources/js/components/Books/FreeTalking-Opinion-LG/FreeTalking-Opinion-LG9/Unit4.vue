<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/top-view-wi-fi-router-with-copy-space_23-2148779248.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should the Internet Be Censored?
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
      <td class = "lowertable" >The majority of people who surf the web do not want to encounter vulgar,inappropriate or disturbing language or images. This is why censorship is relevant. Censorship is not wrong. In fact, it keeps us immune from things we do not wish to see and makes our online experience safer and more comfortable, especially for children and teenagers.
        </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >A BBC World Service poll, which was conducted between November 2009 and February 2010, found that “despite worries about privacy and fraud, people around the world see access to the Internet as their fundamental right… and most don’t want governments to regulate it.” The poll surveyed almost 28,000 adults in 26 countries around the world. A whopping 78 percent of people responded that the Internet brought them greater freedom, and 53 percent agreed that “the Internet should never be regulated by any level of government anywhere.” </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>vulgar</b> 상스러운, 음탕한
        </p>
        <p>
          <b>disturbing</b> 충격적인, 불안감을 주는
        </p>
        <p>
          <b>censorship</b> 검열
        </p>
        <p>
          <b>fraud</b> 사기(죄)
        </p>
        <p>
          <b>fundamental</b> 핵심적인, 필수적인
        </p>
         
  </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >인터넷 정보를 검색하는 대부분의 사람들은 저속하고 적절하지 못하거나 충격적인 언어 혹은 이미지를 접하는 것을 원치 않는다. 이것이 검열이 적절한 이유이다. 검열이 잘못된 것이 아니다. 사실, 그것은 우리가 보길 원치 않는 것들을 면하게 해주고, 우리가, 특히 아이들과 청소년들이 더 안전하고 편안한 인터넷 경험을 할 수 있게 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >많은 나라의 인구가 나이를 먹고 있다. 사람들은 더 오래 살고 있다. 사람들을 퇴직하게 하는 것은 단순히 연금 수령자의 경제적 부담을 가중시킬 뿐이다. 노동인구에 의존해 사는 인구 비율은 증가하고 있으며, 의무 정년제는 이 문제를 악화시키는 불필요한 수단이다. 대신에, 우리는 계속 일 할 수 있는 사람들을 적극적으로 격려해야 한다.</td>
          </tr>
          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you think that the internet should be censored? Why or why not?</li>
          <li>Should there be a limitation as to what a person can post on the internet?</li>
          <li>Do you think the internet is child-friendly? Why or why not?</li>
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

<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/business-people-using-internet_53876-90850.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">The Internet is a good resource for information
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
      <td class = "lowertable" >The Internet is a good resource for information. A single search can come up with many different web pages. It is true that some web pages do not contain reliable information. However, users must learn how to differentiate between websites that contain false information and those that can be trusted. I still claim that the Internet is a good resource for information because it allows people to search for their answers in a quick and efficient way.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The Internet is not a good resource for information. People are increasingly dependent on it to find information. However, anyone can post anything online! This means that someone can post completely falsified information and pass it off as a fact. People often encounter exaggerated or unproven claims online. However, most do not know how to differentiate between a fact and a fiction. Therefore, itis better for people to rely on books, encyclopedias, newspapers,or teachers to find answers to their questions.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>web pages</b> 웹 페이지(웹사이트를 구성하는 문서)
        </p>
        <p>
          <b>reliable</b> (옳을 것으로) 믿을 만한
        </p>
        <p>
          <b>false information</b> 허위 정보 
        </p>
        <p>
          <b>unproven</b> 증명[입증]되지 않은
        </p>
        <p>
          <b>rely</b> 의지하다; 신뢰하다, 믿다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >인터넷은 좋은 정보 원천이다. 한 번의 검색으로 수많은 웹 페이지를 찾을 수 있다. 어떤 웹 페이지는 신뢰할 수 있는 정보를 포함하고 있지 않다는 것은 사실이다. 하지만, 사용자들은 잘못된 정보를 포함하고 있는 웹 사이트와 믿을 수 있는 웹 사이트를 구별하는 법을 반드시 배워야 한다. 나는 인터넷이 사람들이 빠르고 효율적인 방법으로 자신들의 답을 찾을 수 있도록 하기 때문에 그것이 좋은 정보 원천이라고 여전히 주장한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >인터넷은 좋은 정보의 원천이 아니다. 사람들은 정보를 찾기 위해 그것에 점점 의존적이다. 하지만, 누구라도 인터넷에 무엇이든지 올릴 수 있다! 이것은 어떤 사람들이 완전히 잘못된 인포메이션을 올리고 그것이 사실인 듯 넘길 수 있다는 것을 의미한다. 사람들은 종종 과장되거나 증명되지 않은 주장을 온라인에서 접하게 된다. 하지만, 대부분은 사실과 허구를 구별하는 법을 알지 못한다. 따라서, 사람들은 자신들의 질문에 대한 답을 찾기 위해 책, 백과사전, 신문, 또는 선생님에게 의존하는 것이 낫다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you use the internet on a daily basis? Why or why not?</li>
          <li>Do you think the internet is a reliable source of information?</li>
          <li>Do you easily believe the things you see on the internet?</li>
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

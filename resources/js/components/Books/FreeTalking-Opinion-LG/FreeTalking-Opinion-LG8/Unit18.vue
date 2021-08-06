<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/old-retro-tv-by-placing-flower-vases-books_1150-19423.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Television VS Books
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
      <td class = "lowertable" >It is very important to be taught how to read because so many things rely on it. Signs, creating and interpreting documents at work, legal things you go through in life (like buying a house), filling out forms all require you to read, it is vital that children be able to read. This has traditionally led to a concentration on books because a student can have their own book and carry it around easily. However With increasing technology it is possible to teach people to read using other mediums. TV is not very well suited for people learning at their own pace. Television is becoming the past of people's lives and you can even watch TV on your phone.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >The demand for reading may be high because people want to learn, relax, and be entertained. TV is superior in all of these categories and more. It is a multimedia format that can easily be paused and replayed via DVR. The same multimedia presentation can be distributed on a smartphone, tablet or pc through a cd, DVD or jump drive, YouTube or InternetTV. I agree that reading is a vital skill that will most likely be needed throughout life. Teaching a child or adult to read can easily be done via this type of presentation as well as the information on buying a house and other legal matters.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>vital</b> 대모한
        </p>
        <p>
          <b>mediums</b> (특정한 목적을 위한) 도구
        </p>
        <p>
          <b>multimedia</b> 다중 매체의, 멀티미디어의
        </p>
        <p>
          <b>superior</b> 거만한
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >읽는 법을 배우는 것은 매우 중요한데 많은 것들이 읽는 것에 의존하기(달려있기) 때문이다. 서명하는 것, 직장에서 문서를 만들고 해석하는 것, 살면서 겪을 법률적인 문제들(집을 사는 것과 같은), 당신이 읽어야 하는 서류를 작성하는 것, 어린이들이 읽을 줄 알아야 하는 것은 매우 중요한 문제이다. 학생들은 쉽게 책을 가질 수 있고 들고 다닐 수 있기 때문에 전통적으로 책에 집중하게 했다. 그러나 기술의 발달로 사람들에게 다른 매개체를 이용하여 읽는 것을 가르치는 것이 가능해졌다. 텔레비전은 사람들 개개인의 속도에 따라 배우는데 있어서 적합하지 않다. 텔레비전은 사람들의 일상에서 과거가 되고 있으며 당신은 심지어는 전화기로도 텔레비전을 볼 수 있다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >사람들은 배우고 싶어하고, 쉬고 싶어하며 즐거워하기를 원하기 때문에 책을 읽는 것에 대한 수요는 높을지 모른다. 텔레비전은 이러한 모든 것들과 그 이상에 있어서 우수하다. 텔레비전은 DVR을 통해서 쉽게 정지할 수 있고 재생할 수 있는 멀티미디어 형식이다. 같은 멀티미디어 프레젠테이션이 스마트폰, CD를 통한 휴대용 컴퓨터, DVD 또는 점프 드라이브, 유투브 또는 인터넷 티비를 통해 유통될 수 있다. 나는 읽는 것이 인생에 있어서 가장 필요할 중요한 기술이라는데 동의한다. 어린이나 성인에게 읽는 것을 가르치는 것은 집을 사거나 다른 법률적인 문제를 처리하는 정보 뿐 아니라 이러한 종류의 멀티미디어 프레젠테이션을 통해 쉽게 할 수 있다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>While growing up, did you enjoy reading books? Why or why not?</li>
          <li>Do you think it’s necessary for a person to read a book at least once a month? Why or why not?</li>
          <li>Would you rather watch TV or read a book? Why?</li>
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

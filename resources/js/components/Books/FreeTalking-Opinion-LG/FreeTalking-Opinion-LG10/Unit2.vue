
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/joyful-multiethnic-friends-taking-funny-group-selfie_1262-21109.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should there be more kid-free zones in public places?
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
      <td class = "lowertable" >There should be more kid-free zones in public places. Can you imagine eating dinner at a nice restaurant and listening to the sound of children crying? Kid-free zones were created because children often bother other people in public places. Some parents do not discipline their misbehaving children. Therefore, kids make a lot of ruckus and commotion in public places, such as restaurants, museums, or concert halls. Kids can also make a mess. This is a big disturbance to other people.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >There should be no kid-free zones in public places. This is discrimination against kids to prohibit them from entering certain places. I have a much better idea! Public places, such as restaurants, cafes, or museums, should become more kid-friendly. Restaurants and cafes should offer activities, like coloring, to occupy children. Also, museums should offer kid zones with games and exhibits especially for children. Kid-free zones are a pain for parents because they are not able to go to certain places with their children.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>bother</b> 괴롭히다, 귀찮게 하다
        </p>
        <p>
          <b>discipline</b> 꾸짖다
        </p>
        <p>
          <b>misbehave</b> 못된 짓을 하다
        </p>
        <p>
          <b>ruckus</b> (=commotion) 소란, 소동
        </p>
        <p>
          <b>make a mess</b> 엉망으로 만들다
        </p>
        <p>
          <b>disturbance</b> 방해
        </p>
        <p>
          <b>discrimination</b> 차별
        </p>
        <p>
          <b>prohibit</b> 금지하다
        </p>
        <p>
          <b>exhibit</b> 전시(품)
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >노키즈존이 더 많아져야 한다. 당신은 멋진 레스토랑에서 저녁식사를 하며 아이들이 우는 소리를 듣는 것을 상상할 수 있나? 노키즈존은 아이들이 종종 공공 장소에서 다른 사람들을 귀찮게 하기 때문에 만들어졌다. 어떤 부모들은 잘못된 행동을 하는 자신의 아이를 훈육하지 않는다. 따라서, 아이들은 레스토랑이나 박물관, 또는 콘서트장과 같은 공공 장소에서 많은 소란을 일으킨다. 아이들은 또한 난장판을 만들 수 있다. 이것은 다른 사람들에게 큰 방해이다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >노키즈존이 있으면 안 된다. 이것은 아이들이 특정 장소에 들어가는 것을 금지하는, 아이들에 대한 차별이다. 나에게 더 좋은 생각이 있다! 식당이나 카페, 또는 박물관과 같은 공공 장소가 아이들에게 더 특화되어야 한다. 레스토랑과 카페는 아이들이 시간을 보낼 수 있는 색칠 공부와 같은 활동을 제공해야 한다. 또한, 박물관은 특히 아이들을 위한 게임과 전시가 있는 키즈존을 제공해야 한다. 부모들이 아이와 함께 특정 장소에 갈 수 없기 때문에 노키즈존은 부모에게 고통이다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Have you ever been to a kid-free establishment? How was it?</li>
          <li>Do you think there should be more kid-free establishments? Why or why not?</li>
          <li>Would you prefer to visit a kid-free establishment? Why or why not?</li>
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

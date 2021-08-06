<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/young-man-with-tv-remote-woman-with-book-sofa_23-2148020305.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Reading books should be better than watching TV 
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
        <td class = "lowertable" >Reading books is better than watching TV. Books challenge readers to use their imagination to visualize the story. Readers can also easily look up vocabulary words, write notes in the margins, refer back to earlier chapters. Books allow readers to engage with a story in many different ways. Watching TV is much easier than reading a book. People often mindlessly watch TV like zombies. People get smarter when they read books and less intelligent when they watch TV.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Watching TV is better than reading books. It is so much easier to watch TV than read a book. For example, you can watch TV while exercising, cooking, eating, or even painting! TV allows viewers to see the actions, characters, and scenery. This is much more interesting than simply reading lines out of a book. Also, it is easy to watch different shows at the same time. It is much harder to switch books especially if the book becomes boring.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
  
          <p>
            <b>visualize</b> 마음속에 그려 보다, 상상하다
          </p>
          <p>
            <b>mindlessly</b> 아무 생각이 없는, 특별한 이유가 없는
          </p>
          <p>
            <b>scenery</b> 경치, 풍경
          </p>
          <p>
            <b>switch</b>  전환되다, 바뀌다; 전환하다, 바꾸다
          </p>
           
 
 

        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >독서가 TV 시청보다 좋다. 책은 독자들이 상상력을 동원해서 이야기를 시각화하도록 도전하게 한다. 독자들은 또한 쉽게 단어를 찾아볼 수 있고, 여백에 글을 쓸 수도 있고, 이미 읽었던 장으로 돌아갈 수도 있다. 책은 독자들이 다양한 방법으로 이야기에 빠져들게 해 준다. TV시청은 독서보다 훨씬 쉽다. 사람들은 아무 생각 없이 좀비처럼 TV를 본다. 사람들은 독서를 할 때 더 똑똑해지고 TV를 시청할 때 덜 똑똑해진다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >TV시청이 독서보다 좋다. TV시청이 독서보다 훨씬 더 쉽다. 예를 들어, 당신은 운동을 하거나, 요리를 하거나, 먹거나, 또는 심지어 그림을 그리면서도 TV를 볼 수 있다! TV는 시청자들이 행위와 인물과 경치를 보게 해 준다. 이것은 단순히 책의 줄들을 읽는 것보다 훨씬 더 재미있다. 또한, 동시에 다른 프로그램을 보는 것도 쉽다. 책이 재미없어질 경우엔 특히 책을 바꾸기가 훨씬 어렵다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Do you like reading books? When was the last time that you read a book?</li>
            <li>Do you make time to watch TV at home? Why or why not?</li>
            <li>What do you think is the benefit of reading a book? How about watching TV?</li>
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
  
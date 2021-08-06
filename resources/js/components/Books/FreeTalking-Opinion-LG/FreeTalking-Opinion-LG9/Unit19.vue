<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/family-moving-using-boxes_1157-35481.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Families Should Have Only One Child
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
        <td class = "lowertable" >Adults should have only one child. These days, raising kids requires a lot of time and money. As our society has developed technologically, more and more education is needed in order to prepare people for future careers. All of this additional education is not cheap. Parents have to spend so much on their children’s education, otherwise they risk their children falling behind their peers. Another benefit of having only one child is that parents can devote themselves to that one child. That will make the child feel special.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >I think that having multiple kids is the better alternative. If people have only one child, then that child will be lonely. By having siblings, kids will be able to play with a family member who is their approximate age. This will also make children more gregarious. That will better prepare them for their academic, work, and social lives. Finally, kids who have siblings will be better supported throughout their lives. Parents usually pass away before their children, so if kids have siblings, they will have a support network later in their lives.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
  
          <p>
            <b>devote</b> 바치다
          </p>
          <p>
            <b>alternative</b> 대안, 선택 가능한 것
          </p>
          <p>
            <b>approximate</b> 거의 정확한, 근사치인
          </p>
          <p>
            <b>gregarious</b> 남과 어울리기 좋아하는, 사교적인
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >성인들 한 아이만을 가져야 한다. 요즘에는, 아이를 기르는 것이 많은 시간과 돈을 요구한다. 우리 사회가 기술적으로 발전하는 것처럼, 미래의 진로를 준비하는 사람들을 위해 점점 더 많은 교육이 필요하다. 이 모든 부가적인 교육은 결코 싸지 않다. 부모님들은 아이들의 교육에 많은 돈을 써야 한다, 그렇지 않으면 부모님들은 그들의 아이들이 동료들에게 뒤처지는 위험부담을 가지게 된다. 한 아이만 있을 때의 또 하나의 혜택은 부모님들은 오직 한 아이에게 헌신할 수 있다. 그것은 그 아이를 특별하게 느끼도록 만들 것이다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >나는 많은 아이를 가지는 것은 더 나은 대안이라고 생각한다. 만약 사람들이 한 아이만 가지면, 그 아이는 외로울 것이다. 형제자매가 있음으로써, 아이들은 비슷한 나이를 가지고 있는 가족구성원과 놀 수 있다. 이것은 또한 아이들이 더욱 사교적이게 만들 것이다. 그것은 아이들이 학업, 일, 그리고 사회 생활을 준비하는데 좋을 것이다. 마지막으로, 형제자매를 가진 아이들은 그들의 삶을 통해 더 나은 삶을 살 것이다. 부모님들께서는 대개 그들의 아이들 보다 먼저 돌아가시기 때문에, 만약 아이들이 형제자매가 있다면, 그들은 나중에 일상생활에서 지원할 수 있는 네트워크를 형성할 수 있다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>What do you think is the ideal number of kids in a family?</li>
            <li>Do you think having more than one kid is ideal? Why or why not?</li>
            <li>Is having one kid a better option? Why?</li>
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
  
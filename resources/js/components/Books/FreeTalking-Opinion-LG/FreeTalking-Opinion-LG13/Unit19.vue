<template>

    <div :style = "{fontSize: fontSize + 'px'}">
  
      <v-container fluid ma-0 pa-0>
  
        <v-layout column>
          <v-img src="https://image.freepik.com/free-photo/portrait-little-girl-with-her-beautiful-dog_1157-36401.jpg" style="max-width: 100%; display:block; height: auto;">
  
          <v-layout
          align-end
          fill-height
          pa-0
          white--text
          >
  
          <transition name="slide-fade">
          <h1 v-if="showTitle" class = "upper-header-lg">Children should own a pet
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
        <td class = "lowertable" >Children should be encouraged to own pets. Owning a pet teaches responsibility. A child has to feed, bathe, and ensure the general health of a pet. This analysis applies to having a pet of any different species. In order to have a pet, a child must plan a feeding schedule and time for play. In addition, many young children develop a strong bond with pets.This is an emotional development that helps to teach a child how to love and take care of another being. Usually, the pets respond by showing affection to the child, which also aids in their development.</td>
      </tr>
      <tr class = "second-dialog-lg">
        <td class = "uppertable" ><b>Victoria :</b></td>
        <td class = "lowertable" >Having a pet is too much of a responsibility for young children. To raise a pet, you have to feed it, give it exercise, and make sure that it always has access to water. Likewise, anyone that owns a pet has to make sure that the pet is comfortable. Also, many animal rights activists have spoken out about owning pets. These individuals argue that the ownership of pets is unethical.The activists that argue that the ownership of pets is unethical are arguing that no human person should be in complete control over another animal.</td>
      </tr>
  
      </table>
  
        <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Vocabulary</h3>
  
        <div style="padding : 16px;">
          <p>
            <b>raise</b> 기르다
          </p>
          <p>
            <b>development</b> 발달
          </p>
          <p>
            <b>unethical</b> 비윤리적인
          </p>
          <p>
            <b>responsibility</b> 책임(감)
          </p>
          <p>
            <b>analysis</b> 분석
          </p>
          <p>
            <b>apply to</b> ~에 적용되다
          </p>
          <p>
            <b>species</b> 종(種)
          </p>
          <p>
            <b>affection</b> 애정
          </p>
          <p>
            <b>comfortable</b> 편안
          </p>
          <p>
            <b>complete</b> 완벽한
          </p>
          <p>
            <b>control</b> 통제
          </p>
        </div>
  
        <div class ="line-lg">
        </div>
        <h3 class = "border-translate-lg white--text">해석</h3>
  
        <div style="padding : 16px;">
  
          <table class = "standard-table">
  
            <tr>
              <td class = "uppertable" ><b>David :</b></td>
              <td class = "lowertable" >어린이들에게 애완동물을 키우도록 권장해야 합니다. 애완동물을 기르는 것은 책임감을 가르쳐줍니다. 어린이들은 애완동물을 먹이고, 목욕시키고 애완동물의 일반적인 건강을 돌봐야 합니다. 이러한 분석은 다른 종류의 애완동물을 소유하는 것에 적용됩니다. 애완동물을 기르기 위해서, 아이는 먹이를 주는 일정과 노는 시간을 정해야만 합니다. 게다가, 많은 어린 아이들은 애완동물과의 강한 유대관계를 발전시킵니다. 이것은 아이들에게 어떻게 동물들을 사랑하고 다른 존재를 돌보는지를 가르치는데 도움을 주는 감정적인 발달입니다. 보통, 애완동물들은 아이에게 애정을 보여줌으로써 반응을 보이고, 이것은 또한 그들의 발달에 도움이 됩니다.</td>
            </tr>
            <tr class = "second-dialog-lg">
              <td class = "uppertable" ><b>Victoria :</b></td>
              <td class = "lowertable" >애완동물을 키우는 것은 어린 아이들에게 너무나 큰 의무입니다. 애완동물을 키우려면, 애완동물에게 먹이를 주고 운동을 시키고 반드시 애완동물이 항상 물에 접근할 수 있도록 해야 합니다. 마찬가지로, 애완동물을 소유하는 사람은 반드시 그 애완동물이 편하도록 해주어야 합니다. 또한, 많은 동물 권리 보호활동가들은 애완동물을 키우는 것에 대해 공개적으로 말해 왔습니다. 이런 개인들은 애완동물의 소유가 비윤리적이라고 주장합니다. 애완동물의 소유가 비윤리적이라고 주장하는 활동가들은 어떠한 인간도 다른 동물을 완전히 통제해서는 안된다고 주장합니다.</td>
            </tr>
  
            </table>
  
  
        </div>
  
      <div class = "line-lg">
        </div>
        <h3 class = "border-lg white--text">Questions</h3>
  
        <div style="padding : 16px;">
  
          <ol style="margin: 12px;">
            <li>Do you own a pet? If so, what exactly is it? If not, do you plan on getting one?</li>
            <li>What are the advantages and disadvantages of owning a pet?</li>
            <li>Should children own a pet? Why or why not?</li>
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
  
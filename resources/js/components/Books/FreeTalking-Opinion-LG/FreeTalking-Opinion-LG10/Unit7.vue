<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/routine-check-puppy-s-health_329181-14492.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">What is a life worth?
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
      <td class = "lowertable" >Although one could argue animal testing provides a great deal of benefit to humankind, society must acknowledge the life of any animal is precious and sacred. Mahatma Gandhi once said, “The greatness of a nation can be judged by the way its animals are treated.” Animals are often victims of torture, imprisonment, and eventual death. There are strong moral and ethical concerns in animal testing because, simply, animals suffer. This raises serious questions about how society can justify the torment of any animal for humans’ personal gain.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Countless people around the world, including our loved ones, suffer from numerous incurable diseases. Although animal testing for scientific research may be considered morally and ethically wrong, the positive outcomes it entails towards preserving the human population simply cannot be ignored. According to the California Biomedical Research Association, “Nearly every medical breakthrough in the last 100 years has resulted directly from research using animals.” Based on the pattern of these outcomes, without proper testing on animals, it would be impossible for researchers to produce any necessary treatments to heal and save human lives. Also, it is proven that animal testing is highly regulated with laws in place to protect them from mistreatment. Researchers have further stated that stressed and crowded laboratories produce unreliable results. This means it is in the best interest of science not to neglect the welfare of animal subjects. </td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>acknowledge</b> 인정하다
        </p>
        <p>
          <b>sacred</b> 신성한
        </p>
        <p>
          <b>imprisonment</b> 감금
        </p>
        <p>
          <b>breakthrough</b> 획기적인 발견, 돌파구
        </p>
        <p>
          <b>mistreatment</b> 학대
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >비록 동물 실험이 인류에게 큰 혜택을 제공한다고 주장할 수도 있지만, 사회는 모든 동물의 생명이 귀중하고 신성하다는 것을 인정해야만 한다. 마하트마 간디는 일전에, “한 국가의 위대함은 그 나라의 동물이 받는 대우를 보고 판단할 수 있다”라고 말했다. 동물들은 종종 고문, 감금, 그리고 결국 죽음의 희생양이다. 동물 실험에는 강한 도덕적, 윤리적 염려가 있는데 왜냐하면, 단순히, 동물들이 고통받기 때문이다. 이것은 사회가 인간의 개인적 이득을 위한 동물의 고통을 어떻게 정당화할 수 있는지에 대한 심각한 의문을 일으킨다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >우리가 사랑하는 사람들을 포함하여 전세계의 수많은 사람들이, 무수히 많은 불치병으로 고통받는다. 비록 과학 연구를 위한 동물 실험이 도덕적, 윤리적으로 잘못되었다고 생각되어야 하지만, 인구를 보존하는 데에 그것이 수반하는 긍정적인 결과는 단순히 무시될 수 없다. 캘리포니아 생물의학 연구 협회에 따르면, “지난 100년간 거의 모든 의학적 돌파구가 동물을 이용한 연구로부터 직접 발생하였다.” 이러한 결과의 패턴을 기반으로 해서, 적합한 동물 실험이 없으면, 연구자들이 사람의 생명을 치료하고 구하기 위해 필요한 치료법을 생산하는 것은 불가능할 것이다. 또한, 동물 실험이 동물 학대로부터 동물들을 보호하기 위해 법으로 강하게 규제되고 있다는 것이 증명되었다. 연구자들은 강세를 받고 밀집된 연구실에서는 신용할 수 없는 결과가 나온다고 나아가 말했다. 이것은 동물 피실험체의 복지를 방관하지 않는 것이 과학의 최대 관심사라는 것을 의미한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Have you heard about animal testing? What are your thoughts about it?</li>
          <li>Do you think animal testing is helpful? Why or why not?</li>
          <li>In your opinion, are there negative effects when it comes to animal testing?</li>
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

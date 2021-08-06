<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/close-up-box-with-vegetables-hands-mature-man_329181-4600.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Vegetarianism Versus Veganism</h1>
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
      <td class = "lowertable" >There are many ways in which vegetarianism and veganism overlap. However, vegetarianism is the better choice because it is less restrictive. According to Lisa Moskovitz, a New York-based nutritionist, vegetarianism makes it “easier to consume a more balanced intake of nutrients.” Both vegetarians and vegans “require more attention and effort to ensure all nutrients are accounted for. It is easier to become deficient in B-vitamins, iron, Vitamin D, calcium, and protein,” according to Moskovitz. She explained that vegans “have a much higher risk of all of those deficiencies, whereas a vegetarian who is properly planning and balancing meals will have much less risk of deficiencies in general.” A study published in Nutrients in 2014 revealed that vegans had an average of 738 mg of calcium per day, which is far below the recommended 1,000 mg per day. On the other hand, semi-vegetarians, who ate meat once in a while, consumed the most calcium in the study. As you can see, veganism is an unhealthy practice.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Veganism is better than vegetarianism for a number of reasons. First of all, it is ideal for weight loss. A study involving 21,966 participants found that vegans generally have a lower BMI than vegetarians. Furthermore, researchers in one study assigned different types of diets to 75 participants. According to medicalnewstoday.com, “After 16 weeks, participants in the vegan group had lost significantly more fat around the abdomen than those in the control group.” A vegan lifestyle also encourages healthier habits, leading to weight loss. According to healthline.com, “Part of the weight-related benefits vegans experience may be explained by factors other than diet. These may include healthier lifestyle choices, such as physical activity, and other health-related behaviors.” Several studies also indicate a lower risk of developing cancer, reduced symptoms of arthritis, and improved kidney function in those who follow a vegan lifestyle. Plus, vegans live completely cruelty-free because they don’t engage in activities that harm animals. Thus, veganism is superior to vegetarianism.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>overlap</b> 겹치다, 공통되다
        </p>
        <p>
          <b>restrictive</b> 제한[구속]하는
        </p>
        <p>
          <b>ensure</b> 반드시 ~하게[이게] 하다, 보장하다
        </p>
        <p>
          <b>deficient</b> (필수적인 것이) 부족한[결핍된]
        </p>
        <p>
          <b>assign</b> 맡기다[배정하다]
        </p>
        <p>
          <b>abdomen</b> 배, 복부
        </p>
        <p>
          <b>arthritis</b> 관절염
        </p>
        <p>
          <b>kidney</b> 신장
        </p>
        <p>
          <b>cruelty</b> 학대
        </p>
        <p>
          <b>engage in</b> ~에 관여[참여]하다
        </p>
        <p>
          <b>superior</b> (~보다 더) 우수한[우세한 우월한]
        </p>
  </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >채식주의와 비거니즘이 겹치는 방식은 여러 가지가 있습니다. 하지만 채식주의는 덜 제한적이기 때문에 더 나은 선택입니다. 뉴욕의 영양학자 리사 모스코비츠에 따르면, 채식을 하면 "보다 균형 잡힌 영양 섭취를 쉽게" 할 수 있다고 합니다. 채식주의자와 비건(엄격한 채식주의자) 모두 "모든 영양소를 확인할수 있도록 더 많은 관심과 노력이 요구됩니다. B-비타민, 철분, 비타민D, 칼슘, 단백질이 부족해지는 것이 더 쉽다”고 모스코비츠는 말했습니다. 그녀는 비건은 “이러한 결핍들의 위험이 모두 훨씬 높은 반면, 식사를 적절하게 계획하고 균형을 잡는 채식주의자는 일반적으로 결핍 위험이 훨씬 적다.”고 설명했습니다. 2014년 뉴트리션 지에 발표 된 연구에 따르면 비건은 하루 평균 738mg의 칼슘을 섭취하며 이는 일일 권장량 1,000mg보다 훨씬 낮은 수치입니다. 반면에 가끔 고기를 먹던 준 채식주의자들은 이 연구에서 가장 많은 칼슘을 섭취한 것으로 나타났습니다. 보시다시피 비거니즘은 건강에 좋지 않은 행위입니다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >비거니즘은 여러 가지 이유로 채식보다 낫습니다. 첫번째로 체중 감량에 이상적입니다. 21,966명의 참가자를 대상으로 한 연구에서 비건들이 채식주의자들보다 일반적으로 체질량지수가 더 낮다는 사실이 밝혀졌습니다. 게다가, 한 연구에서 연구원들은 75명의 참가자들에게 다양한 종류의 식단을 배정했습니다. Medicalnewstoday.com에 따르면, "16주 후에 비건 그룹의 참가자들은 대조군 그룹의 참가자들보다 복부 주변의 지방이 훨씬 더 많이 감소했습니다." 비건 생활 방식은 또한 건강한 습관을 장려하며 체중을 감소시킵니다. Healthline.com에 따르면, “비건이 경험하는 체중과 관련 장점들의 일부는 식단 이외의 요인으로 설명 될 수 있습니다. 여기에는 신체 활동 및 기타 건강 관련 행동과 같은 보다 건강한 생활 방식 선택이 포함될 수 있습니다.” 여러 연구들은 비건 생활 방식을 따르는 사람들은 암 발병 위험이 낮아지고 관절염 증상이 감소하며 신장 기능이 향상된다는 것을 밝혔습니다. 또한, 비건은 동물을 해치는 활동에는 참여하지 않기 때문에 동물학대/실험과는 완전히 무관합니다. 따라서, 비거니즘이 채식주의보다 우월합니다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What is the difference between veganism and vegetarianism?</li>
          <li>Would you rather be a vegetarian or a vegan? Why?</li>
          <li>What are the downsides of vegetarianism and veganism?</li>
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

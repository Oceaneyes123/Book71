
<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/wide-shot-baby-giraffe-near-its-mother-two-zebras-with-green-trees_181624-16496.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Wild Animals Be Kept in Captivity?
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
      <td class = "lowertable" >In recent years, zoos have made great strides in improving the welfare of animals. According to Michael Hutchins, the director of conservation for the American Zoo and Aquarium Association (AZA), zoos are “changing the way animals are housed, how they are fed, and how they interact with humans in order to better provide for their welfare.” Many researchers, including David Shepherdson of the Oregon Zoo agree with Hutchins and argue that conditions are improving for zoo animals. “Zoo exhibits built now are totally different from the way they were built 30 years ago,” Shepherdson said. “There’s a new appreciation for the rich psychological complexity that animals have in their lives.”</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >A 2003 study conducted by a team of biologists from Oxford University found that wild animals accustomed to roaming don’t fare so well in captivity. Certain species, such as lions, cheetahs, tigers, and polar bears, suffer from physical and mental stress and high infant mortality. This study corresponds to similar research, which has found that many animals suffer psychological distress and display abnormal or self-destructive behavior. The researchers of the Oxford study concluded that wide-ranging carnivores should not be kept in captivity. “If we can’t keep them well, then don’t keep them at all,” said Ros Clubb, one of the study’s authors and zoologist at Oxford.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>welfare</b> (개인·단체의) 안녕[행복]
        </p>
        <p>
          <b>conservation</b> (자원 등을 보호하기 위한) 관리
        </p>
        <p>
          <b>complexity</b> 복잡성, 복잡함
        </p>
        <p>
          <b>accustom</b> [~ oneself로] (…에) 익숙해지다, 길들다 ((to))
        </p>
        <p>
          <b>mortality</b> (특정 기간·상황에서의) 사망자 수[사망률]
        </p> 
        <p>
          <b>self-destructive</b> 자멸적인, 자멸형의, 자살적인(suicidal)
        </p> 
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >최근 몇 년간, 동물원은 동물들의 복지를 증진 시키는 데 노력해왔다. 미국 동물원 및 수족관 협회의 Michael Hutchins에 따르면, 동물원은 “동물들의 복지를 위해서 동물들이 서식하는 방법, 그들을 먹이는 법, 그리고 그들이 인간과 교감하는 법 등을 변화시키고 있다”고 한다. 오리건 동물원의 David Shepherdson를 포함한 많은 연구원들은 Hutchins와 같은 생각이고 동물원의 동물들을 위한 환경이 나아지고 있다고 말한다. “현재의 동물원의 전시는 30년전의 동물원과는 완전히 다르다”라고 Shepherdson은 말했다. “동물들이 그들의 삶에서 가지는 많은 심리적인 복잡한 특징들에 관해 사람들이 새롭게 조명하고 있다.”</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >옥스포드 대학의 생물학자 팀에 의해 시행 된 2003년 조사는 어슬렁거리는 습성이 있는 야생 동물들은 밀폐된 공간에서 잘 지내지 못한다는 것을 발견했다. 사자, 치타, 호랑이, 북극곰은 신체적 그리고 정신적 스트레스와 높은 유아사망으로 고통 받는다. 이 연구는 많은 동물들이 심리적인 고통을 겪고 있고 비정상적이거나 자기 파괴적인 행동을 보인다는 연구와 일치한다. 옥스포드 연구원들의 조사는 광범위한 육식동물들은 밀폐된 공간에 가둬두면 안된다는 결론을 내렸다. 옥스포드 대학의 연구의 필자이자 동물학자인 Ros Clubb는 “만약 우리가 그들을 잘 살 수 있는 환경에 가둘 수 없다면, 가두지 않는 것이 낫다”고 말했다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>When was the last time that you’ve visited a zoo?</li>
          <li>Do you think zoos have a good impact on animals? Why or why not?</li>
          <li>In your opinion, what animals should or shouldn’t be put in zoos?</li>
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

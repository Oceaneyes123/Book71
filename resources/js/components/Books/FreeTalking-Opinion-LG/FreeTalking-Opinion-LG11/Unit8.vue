<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/coronavirus-vaccine-composition-lab_23-2148920822.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should Vaccination Be Mandatory?
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
      <td class = "lowertable" >Vaccination should be compulsory for everyone, not just for children entering public schools. Vaccines save people’s lives. According to the American Academy of Pediatrics, “Most childhood vaccines are 90-99 percent effective in preventing disease.” Furthermore, according to Shot at Life, an advocacy campaign that is a part of the United Nations Foundation, vaccines save the lives of 2.5 million children a year. Plus, the Centers for Disease Control and Prevention stated, “Routine childhood immunization among children born between 1994 and 2018 will prevent an estimated 419 million illnesses, 26.8 million hospitalizations, and 936,000 early deaths over the course of their lifetimes.” Moreover, thanks to vaccines, the last case of smallpox in the U.S. was in 1948, and the last in the world was in Somalia in 1977. In the 20th century, 16,316 Americans died from polio. However, in 2012, there were no reported cases of polio or smallpox in the U.S. Vaccines have made the world a much safer place to live in.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >It should not be mandatory to vaccinate children. Vaccines contain very harmful ingredients. For instance, there is an organic mercury compound called thimerosal in one type of flu vaccine. Some doctors believe it is linked to autism. In addition, some vaccines contain aluminum, which can cause neurological damage. Also, according to vaxtruth.org, some vaccines contain yeast proteins that can cause “migraines, irritable bowel syndrome, asthma, diabetes, Alzheimer’s, Lou Gehrig’s disease, ADD, seizure, and stroke.” Plus, many diseases that vaccines target have disappeared. According to the Centers for Disease Control and Prevention, only nine people died from diphtheria in the U.S. between 1980 and 2016. Furthermore, only 11 deaths a year from tetanus have been reported since 1989. Polio has basically been eradicated in the U.S., and only 32 people have died from the mumps virus since 1979. Is there really a need for vaccines? No! We should start relying on natural immunity again. The first speaker provided many statistics and cited credible sources, making his argument much more convincing. The second speaker, on the other hand, used a dubious source. The latter half of her argument was also quite weak.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>compulsory</b> 의무적인, 필수의
        </p>
        <p>
          <b>pediatrics</b> 소아과(학)
        </p>
        <p>
          <b>routine</b> 정례적인
        </p>
        <p>
          <b>immunization</b> 면역 조치
        </p>
        <p>
          <b>autism</b> 자폐증
        </p>
        <p>
          <b>migraine</b> 편두통
        </p>
        <p>
          <b>asthma</b> 천식
        </p>
        <p>
          <b>eradicate</b> 근절하다
        </p>
        <p>
          <b>credible</b> 믿을 만한
        </p>
        <p>
          <b>convincing</b> 설득력 있는
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >백신 접종은 공립 학교에 입학하는 어린이들뿐만 아니라 모든 사람에게 의무 사항이어야 한다. 백신은 사람들의 생명을 구한다. 미국 소아과 학회에 따르면, “대부분의 어린 시절 백신은 질병 예방에 90-99퍼센트 효과가 있다.” 게다가, 국제연합 재단의 일부인 지지 캠페인인 Shot at Life에 따르면, 백신은 매년 2백5십만 명의 어린이의 생명을 구한다. 그리고 질병관리센터는 “1994년부터 2018년 사이에 태어난 어린이들의 정례적인 어린 시절 예방 접종은 그들의 일생 동안 4억1900만 건의 질병, 2680만 건의 입원 및 936,000건의 조기 사망을 예방할 것이다.” 라고 말했다. 더구나, 백신 덕분에 미국에서의 마지막 천연두 사례는 1948년에 있었고, 전세계적으로는 1977년에 소말리아에서 발생했다. 20세기에, 16,316명의 미국인들이 소아마비로 사망했다. 그러나, 2012년에 미국에서 소아마비나 천연두가 보고된 사례가 없었다. 백신은 세계를 더 살기 안전한 곳으로 만들었다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >어린이들을 예방 접종하는 것은 의무적이지 않아야 한다. 백신은 매우 유해한 성분을 가지고 있다. 예를 들어, 한 종류의 독감 백신에는 티메로살이라고 불리는 유기수은화합물이 있다. 일부 의사들은 그것이 자폐증과 연관 있다고 믿는다. 게다가 일부 백신은 신경의 손상을 일으킬 수 있는 알루미늄을 포함하고 있다. 또한 vaxtruth.org에 따르면, 어떤 백신은 “편두통, 과민성 대장 증후군, 천식, 당뇨명, 알츠하이머병, 루게릭병, 주의력 결핍증, 발작 및 뇌졸중을 일으킬 수 있는 효모 단백질을 포함하고 있다. 그리고, 백신이 필요한 많은 질병들이 사라졌다. 질병 통제 예방센터에 따르면, 1980년과 2016년 사이에 아홉 명 만이 디프테리아로 사망했다. 게다가 1989년 이후로 매년 11건에 불과하는 파상풍으로 인한 사망이 보고되었다. 소아마비는 미국에서 근본적으로 근절되었고, 32명 만이 귀밑샘염 비루스로 사망했다. 백신이 정말 필요한가? 아니다! 우리는 자연적인 면역에 다시 의존해야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Are the side effects of vaccines dangerous?</li>
          <li>Is vaccination safe for children? Why do you think so?</li>
          <li>What kind of vaccinations have you had in the past?</li>
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

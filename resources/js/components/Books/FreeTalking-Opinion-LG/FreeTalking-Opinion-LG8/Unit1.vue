<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/doctor-holding-preparing-vaccine-while-wearing-protective-equipment_23-2148847188.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Thoughts on Vaccines
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
      <td class = "lowertable" >Prevention is better than cure, and a vaccine is the best way to prevent an outbreak of a disease or to reduce its negative effects. Vaccinated people become immune to a certain pathogen and do not develop diseases. Although there are occasionally side effects, these affect only a tiny number of people compared to the protection offered to the vast majority. Vaccination Is a natural way to stimulate our immune system to fight a disease. Through vaccination, our immune system recognizes the pathogens and develops a suitable response prior to being faced with the “real disease.” </td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Many vaccines have significant adverse effects, of which the most serious can result in death.With many vaccines the immunity is not life-long. Sometimes the vaccines itself can cause a serious disease to develop as a side effect.If governments know that compulsory mass vaccination is likely to cause death or permanent disability in even a few cases, it is immoral for them to make it compulsory. Some vaccines include toxic materials such as chemicals including mercury, formaldehyde, aluminum, and a variety of other known toxic materials. Vaccines might be capable of causing recurrent infections in children because they weaken the immune system. Parents should have the right to choose on behalf of their children whether they should be vaccinated at all, or to choose vaccination against some diseases but not others.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">

        <p>
          <b>outbreak</b> 발병
        </p>
        <p>
          <b>vaccinate</b> (…에게) 예방 주사를 맞히다
        </p>
        <p>
          <b>pathogen</b> 병원균, 병원체
        </p>
        <p>
          <b>stimulate</b> 자극
        </p>
        <p>
          <b>adverse</b> 부정적인, 불리한
        </p>
        <p>
          <b>compulsory</b> 강제적인, 의무적인, 필수의
        </p>
         
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >예방이 치료보다 낫고, 백신은 질병의 창궐을 막거나 그것의 부작용을 줄이기 위한 최고의 방법이다. 백신접종을 받은 사람들은 특정 병원균에 대해 면역력이 생기고 그 질병을 발전시키지 않는다. 부작용이 가끔 있긴 하지만, 이는 거대한 다수가 보호받는 것에 비하면 아주 적은 수의 사람에게만 영향을 미칠 뿐이다. 백신 접종은 질병에 싸울 우리의 면역 체계를 자극하는 자연적인 방법이다. 백신 접종을 통해 우리의 면역 체계는 병원균을 인식하고 진짜 질병에 직면하기 전에 적절한 대처방법을 만들어낸다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >많은 백신이 심각한 부정적 효과를 가지고 있고, 그 중에서 가장 심한 경우에는 죽음에 이르기도 한다. 많은 백신들로 인한 면역성도 평생 지속되진 않는다. 백신 그 자체가 부작용으로써 심각한 질병을 일으키기도 한다. 정부가 만일 의무적 대량 백신접종이 몇몇 경우에라도 사망이나 영구적 장애를 일으킬 수 있다는 것을 안다면, 그것을 의무로 만드는 것은 부도덕한 일이다. 어떤 백신들은 수은, 포름알데히드, 알루미늄 등의 화학물질 같은 유독물질과 다른 여러 유해 물질을 포함한다. 백신은 면역 체계를 약화시키기 때문에 아이들에게 반복적으로 감염이 나타나게 할 수도 있다. 부모들은 아이들을 대신해서 그들이 백신을 전부 맞을 것인지 아니면 몇몇 질병에 대해서만 맞을 것인지를 선택할 권리를 가져야 한다. </td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>What are your thoughts on vaccines? Do you think they are helpful? Why or why not?</li>
          <li>Do you get vaccine shots? If yes, what are they for? If not, what do you consider getting?</li>
          <li>What can you say about people who are anti-vaccine?</li>
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

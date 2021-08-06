<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img src="https://image.freepik.com/free-photo/closeup-shot-head-cute-elephant-wilderness_181624-16995.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >

        <transition name="slide-fade">
        <h1 v-if="showTitle" class = "upper-header-lg">Should We Track Animals?
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
      <td class = "lowertable" >Tracking animals may be important in discovering animal habitats and research, but it has created extremely harmful consequences. According to a research paper by Steven Cooke, a biologist at Carleton University, there are multiple instances of tracking being used by nefarious people to find animals. Sharks in a conservation program in western Australia were found and killed by people homing in on them with radio signals. Poachers in India attempted to hack GPS data sent by collars on Bengal Tigers. Even animals that grew in captivity found these devices to cause harm, with monkeys getting large cuts and wounds from tracking collars. While learning about animals is important, if we are unintentionally putting them in harm’s way, it is not right. Even with research of domesticated animals, if we cause harm to them, we should stop immediately.</td>
    </tr>
    <tr class = "second-dialog-lg">
      <td class = "uppertable" ><b>Victoria :</b></td>
      <td class = "lowertable" >Tracking animals is necessary for their protection. While it may seem as though we are putting homing beacons on these animals, this is far from the truth. If we put tracking devices on endangered species that migrate long distances, we can alert the proper legal forces involved and protect them wherever they go. By tracking their migration habits and mating nests, we can further protect their habitats and ensure that they grow back from an endangered species. In fact, thanks in part to this technology, formerly endangered species like the Wood Stork, and Island Fox have been moved up from the endangered species list. Now they are a “threatened” species. When we consider just how many animal species we have made extinct, we should track animals to help protect and guide their species back to a healthy number.</td>
    </tr>

    </table>

      <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Vocabulary</h3>

      <div style="padding : 16px;">
        <p>
          <b>track</b> 추적하다
        </p>
        <p>
          <b>multiple</b> 많은
        </p>
        <p>
          <b>nefarious</b> 범죄의, 비도덕적인
        </p>
        <p>
          <b>home in on</b> ~을 향해 ~으로 곧장 나아가다
        </p>
        <p>
          <b>radio signal</b> 무선 신호
        </p>
        <p>
          <b>poacher</b> 밀렵꾼
        </p>
        <p>
          <b>captivity</b> 감금, 억류
        </p>
        <p>
          <b>unintentionally</b> 무심코
        </p>
        <p>
          <b>homing beacon</b> 항공기의 무선 항행 원조 시설의 하나
        </p>
        <p>
          <b>endangered</b> 멸종될 위기에 이른
        </p>
        <p>
          <b>migrate</b> 이동하다
        </p>
        <p>
          <b>alert</b> (위험 등을) 알리다
        </p>
        <p>
          <b>further</b> 더
        </p>
        <p>
          <b>threatened</b> 멸종할 위기에 직면한
        </p>
        <p>
          <b>guide</b> 인도하다, 이끌다
        </p>
      </div>

      <div class ="line-lg">
      </div>
      <h3 class = "border-translate-lg white--text">해석</h3>

      <div style="padding : 16px;">

        <table class = "standard-table">

          <tr>
            <td class = "uppertable" ><b>David :</b></td>
            <td class = "lowertable" >동물을 추적하는 것은 동물의 서식지와 연구에 중요할지 모르지만, 그것은 극히 폐해를 초래한다. 칼레톤 대학의 생물학자인 스티븐 쿠케의 연구 보고서에 따르면, 범죄자들에 동물들을 찾기 위한 수많은 추적 사건들이 있다고 한다. 웨스턴 오스트레일리아의 환경보호 프로그램의 상어들은 무선 신호로 사람들에 의해 추적되었고 죽임을 당했다. 인도의 밀렵꾼들은 벵갈 호랑이의 목걸이에 전송된 GPS 자료를 해킹하려고 시도했다. 원숭이들은 대규모로 줄고 추적 장치인 목걸이로 인해 부상을 입으면서, 이 장치는 심지어 감금되어 있는 동물에게조차도 해를 가할 수 있다. 동물에 대해 배우는 것은 중요하지만, 만약 우리가 그들에게 해가 되는 방식으로 무심코 설치한다면, 그것은 옳지 않다. 가축의 연구조차도, 만약 우리가 그것들에게 해를 가한다면, 우리는 당장 멈추어야만 한다.</td>
          </tr>
          <tr class = "second-dialog-lg">
            <td class = "uppertable" ><b>Victoria :</b></td>
            <td class = "lowertable" >동물을 추적하는 것은 그들의 보호를 위해 필요하다. 이것은 이 동물들에 자동유도표지들을 달고 있는 것처럼 보이지만 그것은 사실과 전혀 다르다. 우리가 긴 거리를 이주하는 멸종 위기에 처한 종들에 추적 장치를 달면, 우리는 적절한 강제력을 알릴 수 있고 그들이 어디에 있는 보호할 수 있다. 그들의 이주 습관과 교미 둥지를 추적함으로써, 우리는 그들의 서식지를 더 보호하고 그들이 멸종 위기 종에서 벗어나도록 할 수 있다. 사실, 부분적으로 이 기술 덕분에 우드 스토크와 아일랜드 여우와 같이 전에 멸종 위기 종들은 멸종 위기 목록에서 옮겨졌다. 이제 그것들은 “절멸 위기” 종이다. 우리가 얼마나 많은 동물 종들을 우리가 멸종 시켜왔는지 생각할 때 우리는 그들을 보호하고 양호한 숫자에 도달하는 데 도움을 주기 위해 추적해야 한다.</td>
          </tr>

          </table>


      </div>

    <div class = "line-lg">
      </div>
      <h3 class = "border-lg white--text">Questions</h3>

      <div style="padding : 16px;">

        <ol style="margin: 12px;">
          <li>Do you believe that tracking animals is harmful?</li>
          <li>What are the advantages of tracking animals?</li>
          <li>Should we track animals that live in the wild? Why or why not?</li>
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

<template>
  <div :style="{ fontSize: fontSize + 'px' }">
    <v-container fluid ma-0 pa-0>
      <v-layout column>
        <v-img
          src="https://image.freepik.com/free-photo/coins-job-word_23-2148568014.jpg"
          style="max-width: 100%; display: block; height: auto"
        >
          <v-layout align-end fill-height pa-0 white--text>
            <transition name="slide-fade">
              <h1 v-if="showTitle" class="upper-header-lg">
                Should We Pursue Our Dream Jobs?
              </h1>
            </transition>
          </v-layout>
        </v-img>

        <div class="line-top-lg"></div>
        <h3 class="lower-header-lg white--text">Topic</h3>

        <div style="padding: 16px; line-height: 1.6">
          <table class="standard-table">
            <tr>
              <td class="uppertable"><b>David :</b></td>
              <td class="lowertable">
                Pursuit of a dream job doesn’t mean giving up everything in life
                on a gut feeling. While it is hard to plan for everything life
                throws at you, living life in regret is often worse. In a book
                called The Top Five Regrets of the Dying, the top regret of
                people on their deathbed was that they lived a life for others
                and not for themselves. In many cases, the pursuit of a dream
                job is one of the best ways for a person to live for themselves.
                Steve Jobs once said, “If you don’t build your dreams, someone
                else will hire you to build theirs.” According to a study by the
                Sage journal on life satisfaction, next to family and kinship
                support, job satisfaction is the second-most necessary element
                from statistical findings. A dream job is the pinnacle of job
                satisfaction. Logically speaking, when you’re happy at work,
                that’s one thing to be happier about. While many dream jobs can
                be extremely difficult to reach, it is often better to live a
                life having tried than one of regrets before dying.
              </td>
            </tr>
            <tr class="second-dialog-lg">
              <td class="uppertable"><b>Victoria :</b></td>
              <td class="lowertable">
                Not everyone’s dreams can come true. If anything, this is a
                fantasy that can only realistically occur for a privileged
                percentage of the world. When you consider that more than 4.4
                billion people live on less than $3 a day, perspective can shift
                very quickly. If more than half of the world cannot even afford
                food or shelter, isn’t it a bit ridiculous for the privileged to
                flaunt their dream jobs in their faces? Even if the world were
                completely equal, and everyone worked their dream jobs, the
                world would be cast into total disarray. Not too many people
                dream of being janitors, or garbage workers, or truck drivers.
                However, without these people our trash would pile up, we would
                not be able to send mail or move packages, and nobody would
                clean that errant pee stain on the Subway. In a world where
                dream jobs rule, there would be no balance and a lack of
                diversity in the job market. If everyone became an author, the
                world would be full of books, half of them would most likely be
                terrible.
              </td>
            </tr>
          </table>

          <div class="line-lg"></div>
          <h3 class="border-lg white--text">Vocabulary</h3>

          <div style="padding: 16px">
            <p><b>pursuit</b> 추구</p>
            <p><b>gut feeling</b> 직감</p>
            <p><b>deathbed</b> 임종</p>
            <p><b>realistically</b> 현실적으로 말해서</p>
            <p><b>privileged</b> 특권을 가진</p>
            <p><b>perspective</b> 관점, 시각</p>
            <p><b>janitor</b> 수위</p>
            <p><b>errant</b> 잘못된</p>
            <p><b>stain</b> 얼룩</p>
          </div>

          <div class="line-lg"></div>
          <h3 class="border-translate-lg white--text">해석</h3>

          <div style="padding: 16px">
            <table class="standard-table">
              <tr>
                <td class="uppertable"><b>David :</b></td>
                <td class="lowertable">
                  꿈의 직장을 추구하는 것은 직감에 의해 삶의 모든 것을 포기하는
                  것을 의미하지는 않는다. 여러분에게 주어진 삶에 모든 것을
                  계획하는 것은 힘들겠지만, 후회하며 사는 것은 종종 더 나쁘다.
                  “죽기 전에 하는 후회 Top 5”라는 책에서, 임종 직전에 사람들이
                  하는 가장 큰 후회는 그들이 타인을 위해서 살았고 그들 스스로를
                  위해서 살지 않았다는 것이다. 많은 경우에서, 꿈의 직업의 추구는
                  사람들이 그들을 위한 삶을 사는 최고의 방법이다. 스티브 잡스는
                  “여러분이 여러분의 꿈을 쌓지 않으면, 누군가가 그들의 것을 쌓기
                  위해 여러분의 고용할 것이다”라고 말한 적이 있다. Sage 저널의
                  생활 만족도에 대한 연구에 따르면, 통계학적인 발견에서 가족과
                  친족의 지지 다음으로 직업 만족도는 가장 필요한 요소이다. 꿈의
                  직업은 직업 만족도의 정점이다. 논리적으로 말하면, 여러분이
                  직장에서 행복하면, 그것이 더 행복해야 할 하나이다. 많은 꿈의
                  직업이 성취하기 극도로 어렵지만, 그것을 이루기 위해 노력을
                  하는 것이 죽기 전의.
                </td>
              </tr>
              <tr class="second-dialog-lg">
                <td class="uppertable"><b>Victoria :</b></td>
                <td class="lowertable">
                  모두의 꿈이 실현될 수 있는 것은 아니다. 이것은 세계의 특권층의
                  일부에게만 현실적으로 발생할 수 있는 환상일 뿐이다. 여러분이
                  44억명의 사람들이 하루에 3달러 미만으로 살아가는 것을 고려할
                  때, 관점은 매우 빨리 바뀔 수 있다. 만약 세계의 절반 이상의
                  인구가 음식이나 주거지의 비용을 감당할 수조차 없다면, 특권층이
                  그들의 얼굴에다 그들의 꿈의 직장을 과시하는 것은 조금 우습지
                  않은가? 세계가 완전히 동등하고 모두가 꿈의 직장에서 일한다
                  할지라도, 세계는 완전 엉망진창인 상태로빠질 것이다. 너무 많은
                  사람들이 청소부나 쓰레기를 치우는 노동자 혹은 트럭 운전사가
                  되기를 바라지 않을 것이다. 하지만, 이러한 사람들이 없다면
                  우리의 쓰레기는 쌓이고 우편을 보내거나 운송을 하지 못할 것이며
                  아무도 지하철에 있는 노상방뇨를 치우지 않을 것이다. 꿈꾸는
                  직장이 다스리는 세계에서 균형이 없을 것이며 직업 시장에서
                  다양성이 부족할 것이다. 만약 모두가 작가가 된다면, 세계는
                  책으로 가득할 것이며 그것들 중 반은 끔찍할 것이다.
                </td>
              </tr>
            </table>
          </div>

          <div class="line-lg"></div>
          <h3 class="border-lg white--text">Questions</h3>

          <div style="padding: 16px">
            <ol style="margin: 12px">
              <li>What is your dream job?</li>
              <li>What are some tips on attaining a dream job?</li>
              <li>
                What would you do if someone knocks on your door one day and
                offers you your dream job?
              </li>
            </ol>
          </div>
        </div>
      </v-layout>
    </v-container>
  </div>
</template>



<script>
export default {
  props: ["fontSize"],

  data() {
    return {
      showTitle: false,
    };
  },

  mounted() {
    this.showTitle = true;
  },

  beforeMount() {},

  methods: {},

  watch: {
    fontSize(current, old) {
      console.log(current, "current");
      console.log(old, "previous");
    },
  },
};
</script>

<style scoped lang="css">
</style>

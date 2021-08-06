<template>
  <div :style="{ fontSize: fontSize + 'px' }">
    <v-container fluid ma-0 pa-0>
      <v-layout column>
        <v-img
          src="https://image.freepik.com/free-photo/elk-head-yellow-butterfly-it_181624-11229.jpg"
          style="max-width: 100%; display: block; height: auto"
        >
          <v-layout align-end fill-height pa-0 white--text>
            <transition name="slide-fade">
              <h1 v-if="showTitle" class="upper-header-lg">
                Animal Rights: Are They Important?
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
                Human beings are omnivorous, which means we can survive quite
                happily with or without meat. Contrary to popular belief
                prehistoric humans did not subsist solely on meat. Quite The
                opposite in fact; our ancestors subsisted on a range of foods
                that they found, such as fruits and vegetables as well as some
                meat. Yet even if they had no meat they could still survive.
                This is just as true today as it was 10,000 years ago. We can
                happily survive and live healthily without meat, yet we insist
                on ending millions if not billions of lives every year. And for
                what? A hamburger? This is wrong.
              </td>
            </tr>
            <tr class="second-dialog-lg">
              <td class="uppertable"><b>Victoria :</b></td>
              <td class="lowertable">
                Human beings are the most advanced species on the planet and
                while we do a lot to look after animals and plants we also need
                to think about ourselves. While it may be true that we can
                survive without meat, are we really existing at our full
                potential and achieving all that we could by consuming only
                vegetables? We have to think of our race first and while it’s
                tough we are on top of the food chain. You don’t see lions and
                tigers debating the ethics of eating meat, do you?
              </td>
            </tr>
          </table>

          <div class="line-lg"></div>
          <h3 class="border-lg white--text">Vocabulary</h3>

          <div style="padding: 16px">
            <p><b>omnivorous</b> 잡식성의</p>
            <p><b>subsisted</b> 근근이 살아가다</p>
            <p><b>potential</b> 잠재력</p>
            <p><b>food chain</b> 먹이 사슬</p>
          </div>

          <div class="line-lg"></div>
          <h3 class="border-translate-lg white--text">해석</h3>

          <div style="padding: 16px">
            <table class="standard-table">
              <tr>
                <td class="uppertable"><b>David :</b></td>
                <td class="lowertable">
                  인간은 잡식성이다, 이는 우리가 생존할 수 있다는 것을 의미한다.
                  대중의 믿음에 반해 선사시대의 사람들이 오로지 고기만 먹고 살지
                  않았다. 사실은 꽤 반대다; 우리 조상들은 그들이 발견한 고기뿐만
                  아니라 과일 그리고 야채와 같은 음식들을 모두 먹는다, 하지만
                  만약 그들이 고기를 먹지 않는다 해도 그들은 여전히 생존할 수
                  있다. 이것은 만년 전에 있었던 것처럼 오늘날도 마찬가지다.
                  우리는 고기 없이 행복하게 살아 남고 건강하게 살 수 있다,
                  하지만 우리는 매년 수백만 아니면 수십억 동물들을 죽이자고
                  주장하고 있다. 무엇을 위해? 햄버거? 이는 틀렸다.
                </td>
              </tr>
              <tr class="second-dialog-lg">
                <td class="uppertable"><b>Victoria :</b></td>
                <td class="lowertable">
                  인간은 지구 상에 가장 진보된 종이다. 그리고 우리가 동물과
                  식물을 잘 돌보는 동안 우리는 또한 우리 스스로에 대해 생각할
                  필요가 있다. 우리가 고기 없이 생존할 수 있다는 것은
                  사실이지만, 우리는 정말로 완전한 잠재성으로 존재하고 있고
                  우리가 채소만을 먹음으로써 할 수 있는 모든 것을 달성할 수
                  있을까? 우리는 우리 인간을 먼저 생각해야만 하고 힘들겠지만
                  우리는 먹이 사슬의 상위를 차지한다. 여러분은 고기를 먹는 것에
                  대한 윤리문제를 논의하고 있는 사자와 호랑이를 볼 수 없지
                  않은가?
                </td>
              </tr>
            </table>
          </div>

          <div class="line-lg"></div>
          <h3 class="border-lg white--text">Questions</h3>

          <div style="padding: 16px">
            <ol style="margin: 12px">
              <li>What do you think is “animal rights”?</li>
              <li>
                If there is a law that prohibits killing animals, should it
                apply to all animals?
              </li>
              <li>
                If people are not allowed to kill animals anymore, do you think
                you can survive eating purely vegetables?
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

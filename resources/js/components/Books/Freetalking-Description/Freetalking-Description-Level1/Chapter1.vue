<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://image.freepik.com/free-photo/family-with-cute-kids-autumn-park_1157-26503.jpg" style="max-width: 100%; display:block; height: auto;">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <h1 class= "upperheader-FD1">Family
      </h1>
    </v-layout>
  </v-img>

  <div class= "top-line-FD1">
  </div>
  <h3  class = "uppper-border-FD1 white--text">Sample Descriptions</h3>
  <div style = "padding : 16px;">

      <h3>
        Four people are having a picnic.
      </h3>

      <h3>They look happy.</h3>

      <p><h4>소풍을 하고 있는 네명의 사람이 있습니다.</h4></p>

      <h4>그들은 행복해 보입니다.</h4>


      <div class = "line-FD1">
      </div>
      <h3 class = "border-FD1 white--text">Suggested Vocabulary</h3>
      <div style="padding : 16px;">

        <p>
          <b>Picnic 소풍, 피크닉, 도시락, 소풍[피크닉]을 하다</b>
        </p>

        <p>
          <b>Fruit 과일, 열매</b>
        </p>

        <p>
          <b>Blanket 담요, 짙게 드리운[두텁게 내려앉은] ~, 전반[전면]적</b>
        </p>

        <p>
          <b>Park 공원, 지역[단지], 사유지 공원[대정원]</b>
        </p>

      </div>

      <div class = "line-FD1">
      </div>
      <h3 class = "border-FD1 white--text">Questions for Discussion</h3>
      <div style="padding : 16px;">

        <p>

          <v-container grid-list-md text-xs-left>
            <v-layout row wrap>


              <v-flex xs12>
                <v-card light color="#ffbd69">
                  <v-card-text class="px-10">
                    <p>
                      <b>
                      Do you like having a picnic with your family? Why or Why not?<br />
                      <br />
                      How many people you can see in the picture?<br />
                      <br />
                      What can you say about the color of their clothes?<br />
                      <br />
                      What do you think is the season in this picture?
                      </b>
                    </p>
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>

        </p>

        <p>

          <v-container grid-list-md text-xs-left>
            <v-layout row wrap>


              <v-flex xs12>
                <v-card light color="#ffbd69">
                  <v-card-text class="px-10">
                    <p>
                      <b>
                      가족들과 소풍을 가는 것을 좋아하나요? 왜 그런가요, 아니라면 왜 아닌가요?<br />
                      <br />
                      사진에서 몇명의 사람을 볼 수 있나요?<br />
                      <br />
                      그들의 옷 색깔로 무엇을 말할 수 있나요?<br />
                      <br />
                      이 사진의 계절은 무엇이라고 생각합니까?
                      </b>
                    </p>
                  </v-card-text>
                </v-card>
              </v-flex>
            </v-layout>
          </v-container>

        </p>




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
    return {};
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
p {
  margin-top: 10px;
}

h3 {
  padding-top: 7px;
}

body {
  font-size: 16px;
}
</style>

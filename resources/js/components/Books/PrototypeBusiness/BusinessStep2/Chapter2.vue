<template>

  <div :style = "{fontSize: fontSize + 'px'}">

    <v-container fluid ma-0 pa-0>

      <v-layout column>
        <v-img
        src="https://marketplace.canva.com/MADGvqoV9yA/7/screen_2x/canva-mosque-MADGvqoV9yA.jpg" class = "cover-photo">

        <v-layout
        align-end
        fill-height
        pa-0
        white--text
        >
        <h1 style="background-color: rgba(254, 183, 43, 0.7);
        width: 100%;
        padding-top : 10px;
        padding-left : 10px;
        padding-bottom: 10px;">Talking about past events
      </h1>
    </v-layout>
  </v-img>

  <div style=" border-color: #899857; border-style: solid; border-width: 2px;">
  </div>
  <h3  class = "border" >Today's topic</h3>
  <div style = "padding : 16px;">

    <table style = "border-collapse: collapse;">

      <tr v-for="dialog in dialogs" :key="dialog">
        <td class = "uppertable" >{{dialog.name}}</td>
        <td class = "lowertable" >{{dialog.speech}}</td>
      </tr>
    
    </table>

    <div style="margin-left: -18px; margin-right: -18px; margin-top: 10px; border-color: #899857; border-style: solid; border-width: 2px;">
    </div>
    <h3 class = "border" style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px; margin-top: 0px; background-color: #899857;">Translation</h3>
    <div style="padding : 16px;">

      <table style = "border-collapse: collapse;">

        <tr v-for="translation in translations" :key="translation">
          <td class = "uppertable" >{{translation.name}}</td>
          <td class = "lowertable" >{{translation.speech}}</td>
        </tr>
  
      </table>
      
    </div>

    <div style="margin-left: -18px; margin-right: -18px; margin-top: 10px; border-color: #899857; border-style: solid; border-width: 2px;">
    </div>
    <h3 class = "border" style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px; margin-top: 0px; background-color: #899857;">Exercise</h3>
    <div style="padding : 16px;">

      <p>
        Fill the gaps with was, wasn't were or weren't
      </p>

      <ol style="margin: 12px;">
        <li>
          A: Where ( &emsp; ) you yesterday?<br />
          B: We ( &emsp; ) in a meeting.
        </li>
        <li>
          A: ( &emsp; ) Julia at the trade fair last year?<br />
          B: No, she ( &emsp; ) there.
        </li>
      </ol>

      <p>
        Fill in the gaps.<br />
        ago, last, yesterday, night
      </p>
      <ol style="margin: 12px;">
        <li>
          He was in New York ten days ( &emsp; ).
        </li>
        <li>
          HToday is Monday so, ( &emsp; ) was Sunday.
        </li>
        <li>
          There was a problem at the factory last ( &emsp; ).
        </li>
        <li>
          I was in Australia ( &emsp; ) month.
        </li>
      </ol>
      <p>
        Free response:<br />
        Work with a partner. Talk about where you were:<br />
        - yesterday evening<br />
        - last Saturday<br />
        - a week ago
      </p>

    </div>

    <div style="margin-left: -18px; margin-right: -18px; margin-top: 10px; border-color: #899857; border-style: solid; border-width: 2px;">
    </div>
    <h3 class = "border" style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px; margin-top: 0px; background-color: #899857;">Self Study</h3>
    <div style="padding : 16px;">


      <p>
        Notes
      </p>

      <p>

        <v-container grid-list-md text-xs-left>
          <v-layout row wrap>


            <v-flex xs12>
              <v-card light color="#527318">
                <v-card-text class="px-10">
                  <p>
                    be: past simple
                  </p>
                  <p>
                    긍정문: The conference was good last week.<br />
                    의문문: Was John there?<br />
                    부정문: The presentation wasn't very good.
                  </p>
                  <p>
                    Time references to the past
                  </p>
                  <p>
                    <b>last</b> + (Tuesday, March, week, month, year, summer, Christmas)<br />
                    (two days, three months, a year)+ <b>ago</b>
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

  props: ['fontSize'],

  data(){

    return{
      dialogs:[
        {
          name:'Colleague:',
          speech:'Were you at the trade fair last week, Hanna? In India?'
        },
        {
          name:'Hanna:',
          speech:'Yes.'
        },
        {
          name:'Colleague:',
          speech:'Where was it? Delhi?'
        },
        {
          name:'Hanna:',
          speech:'Yeah.'
        },
        {
          name:'Colleague:',
          speech:'How was it? OK?'
        },
        {
          name:'Hanna:',
          speech:'It was very good, yeah.'
        },
        {
          name:'Colleague:',
          speech:'Was it big?'
        },
        {
          name:'Hanna:',
          speech:'Yeah. There were thousands of people.'
        },
        {
          name:'Colleague:',
          speech:'How many companies were there?'
        },
        {
          name:'Hanna:',
          speech:'Um... about four hundred, I think.'
        },
        {
          name:'Colleague:',
          speech:'Really?'
        },
        {
          name:'Hanna:',
          speech:'Yeah, it was big. I was surprised. I wasn’t there last year. I was there two years ago, in Calcutta, and um... there weren’t a lot of companies there. Only about a hundred.'
        },
        {
          name:'Colleague:',
          speech:'So this wasn’t your first visit to India, then?'
        },
        {
          name:'Hanna:',
          speech:'No, my second.'
        },
        {
          name:'Colleague:',
          speech:'Right. Were you the only person there, from the company?'
        },
        {
          name:'Hanna:',
          speech:'No. Ingrid Werner was there, from the Frankfurt office. And Rafael and Maria, you know from, um...?'
        },
        {
          name:'Colleague:',
          speech:'Oh, from Barcelona?'
        },
        {
          name:'Hanna:',
          speech:'Yeah.'
        },
        {
          name:'Colleague:',
          speech:'Were you all in the same hotel?'
        },
        {
          name:'Hanna:',
          speech:'We weren’t in the same hotel, no. Um... But it was a good trip. Long, though.'
        },
        ],

        translations:[
        {
          name:'A:',
          speech:'제 이름은 린다 샘머슨입니다. 그리고 저는 휴즈 보험에서 왔어요.'
        },
        {
          name:'B:',
          speech:'뭐라고요? 다시 한 번 말해줄래요?'
        },
        {
          name:'A:',
          speech:'린다 샘머슨.  S-A M 두개-E-R-S-O-N'
        },
        {
          name:'B:',
          speech:'좀 더 천천히 말해줄래요?'
        },
        {
          name:'A:',
          speech:'미안해요. S-A M 두개-E-R-S-O-N'
        },
        {
          name:'B:',
          speech:'S-A M 두개 -E-R-S-O-N'
        },
        {
          name:'A:',
          speech:'맞아요. 그리고 저는 휴즈 보험에서 왔어요.'
        },
        {
          name:'B:',
          speech:'맞아요. 그리고 저는 휴즈 보험에서 왔어요.'
        },
        {
          name:'A:',
          speech:'H-U-G-H-E-S.'
        },
        {
          name:'B:',
          speech:'H-U-G-H-E-S.'
        },
        {
          name:'A:',
          speech:'맞아요.'
        },
        {
          name:'B:',
          speech:'알았어요. 전화 줘서 정말 고마워요. 확인해 볼게요..'
        },
        ]

    }

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

p{

  margin-top: 10px;
}

h3{
  padding-top: 7px;

}

body{

  font-size: 16px;
}

.border:before {
  content: "";
  width: 0px;
  height: 0px;
  border-style: solid;
  border-width: 40px 40px 0px 0px;
  transform: rotate(180deg);
  border-color: transparent #899857 transparent transparent;
  position: absolute;
  top: 0px;
  margin-left: 190px;
}
.border {
  position: relative;
  left: 0px;
  width: 200px;
  height: 40px;
  background: #899857;
  padding-left: 10px;

}
.profile {
  background-color: rgba(0, 0, 0, 0);
  width: 100%;
  padding-top : 330px;
  padding-left : 10px;
  padding-bottom: 10px;
}

.uppertable {
  border: 0px solid #dddddd;
  text-align: left; padding: 8px;
  vertical-align:top;
  width: 5%;
  white-space: nowrap;
}

.lowertable {
  border: 0px solid #dddddd;
  text-align: left;
  padding: 8px;
}

</style>

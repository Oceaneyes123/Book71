<template>

<div :style = "{fontSize: fontSize + 'px'}">

<v-container fluid ma-0 pa-0>

 <v-layout column>
   <v-img
          src="https://marketplace.canva.com/MADGxwcj6PU/4/screen_2x/canva-three-people-sitting-beside-table-MADGxwcj6PU.jpg" class="cover-photo">

       <v-layout
       align-end
       fill-height
       pa-0
       white--text
     >
       <h1 style="background-color: rgba(13, 13, 13, 0.7);
       width: 100%;
       padding-top : 10px;
       padding-left : 10px;
       padding-bottom: 10px;">Jobs and Occupation</h1>
     </v-layout>
   </v-img>


         <h3 style="background-color: #a7d7c5;   
                    padding-top : 10px;  
                    padding-left : 10px; 
                    padding-bottom: 10px;">Reading Practice <br><span class = "korean">( 선생님의 안내에 따라 문장을 읽어 주세요 )</span></h3>
              <div style="padding : 16px;">

<p>I am Edward Stack, an architect. I am currently working at Owen Morse Architects located in Manhattan. Although I just graduated this year, my company absorbed me as a regular staff after my internship of six months. I really love my workplace. I share a neat and cozy office with two other staff. They are friendly and extremely helpful to me. Our office has a clear view of the city and it inspires me even more working on new building designs. At the moment, I am working on a shopping mall project. My starting salary for this year is one thousand dollars a month which allows me to buy my own condominium in the following year!
</p>

<h3 style="padding-top: 7px;  margin-left: -18px; margin-right: -18px; padding-left: 10px; padding-bottom: 10px;  padding-top: 10px;margin-top: 10px; background-color: #a7d7c5;">Vocabulary Review</h3>

<div style="padding : 16px;">



<li style="list-style-type: none;"><u>Locate(v)</u> -  to establish a business or house in a particular place <span class = "korean">…의 정확한 위치를 찾아내다, 두다[설치하다], 사업을 시작하다</span>
</li>

<li style="list-style-type: none;"><u>Absorb(v)</u> -   to take something in <span class = "korean">흡수하다[빨아들이다], 흡수하다, 받아들이다, 빼앗다, 빠지게 만들다</span>
</li>

<li style="list-style-type: none;"><u>Staff(n)</u> -  workers <span class = "korean">직원, 사무직원, 참모, 지팡이, 직원으로 일하다; 직원을 제공하다</span>
</li>

<li style="list-style-type: none;"><u>Workplace(n)</u> -   place of employment <span class = "korean">직장, 업무 현장</span>
</li>


<p>Fill in the blanks using the words above.
</p>

<ol style="margin: 12px;">
 <li>If the teaching style is very good, the students will ___________ the lesson easily.
 </li>

 <li>Several ________ will take their days off this Christmas day.
 </li>

 <li>It is _________ hot in the desert!
 </li>

 <li>It must be great to have a sauna in the ___________!
 </li>

 <li>The Statue of Liberty is _________ in the United States.
 </li>


</ol>

</div>

<h3  style="padding-top: 7px;  margin-left: -18px; margin-right: -18px;  padding-bottom: 10px;  padding-top: 10px; padding-left: 10px; background-color: #a7d7c5; ">Comprehension</h3>

<div style="padding : 16px;">

<ol style="margin: 12px;">
<li>What is his job?
</li>

<li>Where is he working?
</li>

<li>Why does he love his workplace?
</li>

<li>What inspires him more in working at his building designs?
</li>

<li>What is he currently working at?
</li>

<li>How much is his salary?
</li>
</ol>

</div>

<h3  style="padding-top: 7px;  margin-left: -18px; margin-right: -18px;  padding-bottom: 10px;  padding-top: 10px; padding-left: 10px; background-color: #a7d7c5; ">Translation</h3>

<div style="padding : 16px;" class = "korean">

  <p>나는 건축가 에드워드 스택이다. 나는 현재 맨해튼에 위치한 오웬 모스 건축사에서 일하고 있다. 
     비록 나는 올해 막 졸업했지만, 우리 회사는 6개월의 인턴십을 마친 후 나를 정규 직원으로 채용했다. 
     나는 내 직장이 정말 좋다. 나는 다른 두 명의 직원과 깔끔하고 아늑한 사무실을 함께 쓰고 있다. 
     그들은 친절하고 나에게 매우 도움이 된다. 우리 사무실은 도시를 훤히 내다보고 있고, 
     새로운 건물 설계에 더 많은 영감을 준다. 지금은 쇼핑몰 프로젝트를 하고 있어. 
     내 올해 초봉은 한 달에 천 달러다. 그래서 다음 해에 내 콘도를 살 수 있다!</p>

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

<style lang="css">

p{

 margin-top: 10px;
}

h3{
 padding-top: 7px;

}


body{

 font-size: 16px;
}

</style>

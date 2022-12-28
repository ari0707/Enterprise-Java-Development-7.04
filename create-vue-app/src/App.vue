<template>
  <div id="app">

    <h1 class = "text0">Welcome to Vue.js</h1>
    <p class="text1">Become a coding ninja with the fastest-growing JavaScript framework</p>

    <img class = "logo" src="./images/Vue_logo.png" alt="Vue logo"/>
    <img class = "logo1" src="./images/ironhack_logo.png" alt="ironhack logo"/>
    <img class = "menu" src="./images/Burger_menu.png" alt="burger menu"/>

    <div class = "background"></div>

    <img class = "USP1" src="./images/USP-1.png" alt="Performant"/>
    <h4 class = "titlePerformant">Performant</h4>
    <p class="insidePerformant">Truly reactive, compiler-optimized rendering system that rarely requires manual optimization.</p>
    <img class = "USP2" src="./images/USP-2.png" alt="Approachable"/>
    <h4 class = "titleApproachable">Approachable</h4>
    <p class="insideApproachable">Builds on top of standard HTML, CSS and JavaScript with intuitive API and world-class documentation.</p>
    <img class = "USP3" src="./images/USP-3.png" alt="Versatile"/>
    <h4 class = "titleVersatile">Versatile</h4>
    <p class="insideVersatile">A rich, incrementally adoptable ecosystem that scales between a library and a full-featured framework.</p>

    <button class="Awesome">Awesome!</button>

  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style>
  .logo{
    position: absolute;
    width: 129px;
    height: 129px;
    left: 235px;
    top: 86px;
    background: url(kisspng-vue-js-javascript-library-react-angularjs-js-5b395da440b705.png);
  }
  .logo1{
    position: absolute;
    width: 35px;
    height: 38px;
    left: 30px;
    top: 20px;
    background: url(image.png);
  }
  .menu{
    position: absolute;
    width: 22px;
    height: 20px;
    left: 548px;
    top: 29px;
    background: url(image.png);
  }
  .Awesome {
    position: absolute;
    width: 121px;
    height: 31px;
    left: 239px;
    top: 354px; 
    background: #34495E;
    border-radius: 13px;
  }
  .text1 {
    position: absolute;
    width: 309px;
    height: 40px;
    left: 145px;
    top: 292px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 14px;
    line-height: 20px;
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .text0 {
    position: absolute;
    width: 456px;
    height: 158px;
    left: 110px;
    top: 174px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 50px;
    line-height: 95px;
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #2B2F30;
  }
  .USP1{
    position: absolute;
    width: 60px;
    height: 60px;
    left: 88px;
    top: 509px;
    background: url(seo.png);
  }
  .USP2{
    position: absolute;
    width: 60px;
    height: 60px;
    left: 270px;
    top: 509px;
    background: url(web-development.png);
  }
  .USP3{
    position: absolute;
    width: 60px;
    height: 60px;
    left: 465px;
    top: 509px;
    background: url(app-development.png);
  }
  .background{
    position: absolute;
    width: 600px;
    height: 312px;
    left: 0px;
    top: 450px;
    background: #39B983;
  }
  .titlePerformant{
    position: absolute;
    width: 87px;
    height: 95px;
    left: 75px;
    top: 550px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 95px;
/* identical to box height, or 594% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .titleApproachable{
    position: absolute;
    width: 107px;
    height: 95px;
    left: 250px;
    top: 550px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 95px;
/* identical to box height, or 594% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .titleVersatile{
    position: absolute;
    width: 68px;
    height: 95px;
    left: 470px;
    top: 550px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
    line-height: 95px;
/* identical to box height, or 594% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .insidePerformant{
    position: absolute;
    width: 125px;
    height: 91px;
    left: 56px;
    top: 620px;
    font-family: 'Inria Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 17px;
/* or 142% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .insideApproachable{
    position: absolute;
    width: 125px;
    height: 91px;
    left: 237px;
    top: 620px;
    font-family: 'Inria Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 17px;
/* or 142% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }
  .insideVersatile{
    position: absolute;
    width: 125px;
    height: 91px;
    left: 437px;
    top: 620px;
    font-family: 'Inria Sans';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 17px;
/* identical to box height, or 594% */
    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: -0.02em;
    color: #000000;
  }

</style>

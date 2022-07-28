<!-- Please remove this file from your project -->
<template>
  <div>
    <nav>
      <div class="mobileview">
      <img class="mobilelogo" src="logo.png">
      <div class="container" :class="{change: classToggle}" @click="myFunction">
        <div class="bar1"></div>
        <div class="bar2"></div>
        <div class="bar3"></div>
      </div>
      <ul class="ul-class" v-if="classToggle">
        <li><a href="#">Menu One</a></li>
        <li><a href="#">Menu One</a></li>
        <li><a href="#">Menu One</a></li>
        <li><a href="#">Menu One</a></li>
        <li class="user-li">
          <img class="user-img" src="Mask.png">
          <img class="user-img oval-img" src="Oval.png">
          <a class="text-dec" href="#">User</a>
          <img class="user-img" src="Icon.png">
        </li>
      </ul>
      </div>
      <ul class="nav-ul">
        
          <li class="nav-ul-li"><a class="text-dec"  href="#"><img src="logo.png" class="logo-img"></a></li>
                
          <li class="nav-li-margin"><a class="text-dec menupadding60" id="menuone" href="#">Menu One</a></li>
          <li class="nav-li-margin"><a class="text-dec menupadding30" id="menutwo" href="#">Menu Two</a></li>
          <li class="nav-li-margin"><a class="text-dec menupadding30" id="menuthree" href="#">Menu Three</a></li>
          <li class="nav-li-margin"><a class="text-dec menupadding30" id="menufour" href="#">Menu Four</a></li>
          <div class="user-div">
            <li class="user-div-li">
              <img src="Mask.png" alt="">
              <img src="Oval.png" class="user-div-li-ovalimg">
              <a class="text-dec user-div-li-a" href="#">User</a>
              <img src="Icon.png" class="nav-icon">
            </li>
          </div>
      </ul>
    </nav>
    <div id="red_body">
      
      <img v-if="imageExists" src="lettuc.png" class="lettuce-img">
      
      <img v-if="imageExists" src="elici.png" class="elici-img">
      
      <img v-else src="pngwin.png" class="pngwin-img">
      
      <div v-if="imageExists" class="gradient-div-cover">
      </div>
      
    </div>
    <div class="text-dec discover">
      <h1>Discover Restaurant</h1>
      <h1>& Delicious Food</h1>
      <input class="textInput" type="text" value="search restaurant,food"><input type="submit" class="input-submit" value="GO">
    </div>
    
    <div class="location">
      <img src="placehold.png" class="location-img">
      <h4 class="location-name">Hydrabad</h4>
    </div>
    <div class="slider-button-div">
      <div class="slider-button-div-left">
        <img @click="toggleImage" src="Ellipse.png" class="slider-button-div-left-img1">
        <img @click="toggleImage" src="Path1.png" class="slider-button-div-left-img2">
        <img @click="toggleImage" src="Path9.png" class="slider-button-div-left-img3">
      </div>
      <div class="slider-button-div-right">
        <img @click="toggleImage" src="Path9.png" class="slider-button-div-right-img1">
        <img @click="toggleImage" src="Path2.png" class="slider-button-div-right-img2">
        <img @click="toggleImage" src="Ellipse.png" class="slider-button-div-right-img3">
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
  data() {
  return {
    imageExists: true,
    classToggle: false
  }
  },
  methods: {
    toggleImage(){
      this.imageExists = !this.imageExists;
    },
    myFunction() {
      this.classToggle = !this.classToggle;
    }
  }
}
</script>

<style scoped>

.nav-ul{
  display:flex; list-style: none;
}

.nav-ul-li{
  padding-left: 80px;
}

.logo-img{
  width:155px; 
  height: 52px;
}

.nav-li-margin{
  margin: auto;
}

.nav-icon{
  cursor: pointer; 
  padding-left: 10px; 
  margin-top: -8px;
}

.user-div{
  display:flex; 
  margin: auto 0 auto 28%;
}

.user-div-li{
  margin: auto; 
  display: flex; 
  align-items: center; 
  padding-right: 120px;
}

.user-div-li-ovalimg{
  margin-top: -40px; 
  margin-left: -16px;
}



.text-dec{
  text-decoration: none;
  color: #2e266f;
  font-family: sans-serif;
  white-space: nowrap;
}

.menupadding60{
  padding-left: 60px;
}

.menupadding30{
  padding-left: 30px;
}

.user-div-li-a{
  color: white; 
  padding-left: 10px;
}

.lettuce-img{
  z-index: 0; 
  width: 120%; 
  margin-left: -58.5%; 
  margin-top: -16%;
}

.elici-img{
  z-index: 1; 
  margin-left: -94%; 
  margin-top: -138%; 
  width: 175%;
}

.pngwin-img{
  z-index: 0; 
  width: 150%; 
  margin-left: -75.5%; 
  margin-top: 50%;
}

#red_body{
  background-color: #fe043c;
  Height:980px;
  margin-top: -7.2%;
  margin-left: 72%;
  max-width: 28%;
}

.discover{
    margin-top: -628px;
    padding-left: 105px;
    font-size: 27px;
    font-weight: bold;
    line-height: 0.3;
}

.gradient-div-cover{
  margin-top: -645px; 
  margin-left: -320px; 
  width:315px; 
  height:600px; 
  background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
  background-size: 29px 29px; 
  background-position: -9px -9px;
}

.input-submit{
  cursor: pointer;
}

.location{
    align-items: center;
    display: flex;
    width: 16%;
    height: 60px;
    margin-top: 181px;
    background: #fe043c;
    color: white;
    border-top-right-radius: 80px 80px;
    border-bottom-right-radius: 80px 80px;
}

.location-img{
  cursor: pointer; 
  margin-left: 15%;
}

.location-name{
  font-family: sans-serif; 
  font-weight: 500; 
  margin-left: 8%; 
  font-size: larger;
}

.slider-button-div{
  float:right; 
  display: flex;
}

.slider-button-div-left{
  display: flex; 
  align-items: center; 
  margin-right: -30px;
}

.slider-button-div-left-img1{
  cursor: pointer; 
  width: 30%;
}
.slider-button-div-left-img2{
  cursor: pointer; 
  margin-left: -20%; 
  width: 10%;
}

.slider-button-div-left-img3{
  cursor: pointer; 
  margin-left: -9%; 
  width: 41%;
}

.slider-button-div-right{
  cursor: pointer; 
  display: flex; 
  align-items: center;
}

.slider-button-div-right-img1{
  cursor: pointer; 
  width: 41%;
}

.slider-button-div-right-img2{
  cursor: pointer; 
  margin-left: -10%; 
  width: 10%;
}

.slider-button-div-right-img3{
  cursor: pointer; 
  margin-left: -20%; 
  width: 30%;
}

.textInput{
  width: 34%;
  height: 57px;
  font-size: 16px;
  padding-left: 40px;
  padding-right: 12px;
  color: rgba(0,0,0,0.3);
  border: none;
  box-shadow: 5px 5px 28px #f2ccbb;
  margin-top: 15px;
}

input[type="submit"] {
    margin-left: -129px;
    font-size: large;
    height: 48px;
    width: 122px;
    background: #fe043c;
    color: white;
    border: 0;
    -webkit-appearance: none;
    border-top-left-radius: 25px;
}

input[type="submit"]:hover{
  font-size: x-large;
  transition: 0.5s;
  transition-timing-function: ease-in-out;
}





#menuone:hover{
  background: #fe043c;
  color: white;
  padding: 10%;
  padding-left: 60px;
  padding-right: 30px;
  white-space: nowrap;
  margin-left: 0;
  transition: 0.5s;
  transition-timing-function: ease-in-out;
}

[id^='menu']:hover{
  background: #fe043c;
  color: white;
  padding: 10%;
  padding-left: 30px;
  padding-right: 30px;
  white-space: nowrap;
  margin-left: 0;
  transition: 0.5s;
  transition-timing-function: ease-in-out;
}

@media screen and (min-width: 480px) {
  .mobileview {
    display: none;
  }
}

@media screen and (max-width: 480px) {

  .mobileview {
    margin-top: 5%;
  }
  .mobilelogo{
    width: 30%;
    margin-left: 5%;
  }

  .nav-ul{
    display: none;
  }

  .container {
  float: right;
  
  cursor: pointer;
  
  margin-right: 5%;
}

.bar1, .bar2, .bar3 {
  width: 35px;
  height: 5px;
  background-color: white;
  margin: 6px 0;
  transition: 0.4s;
}

/* Rotate first bar */
.change .bar1 {
  -webkit-transform: rotate(-45deg) translate(-9px, 6px) ;
  transform: rotate(-45deg) translate(-9px, 6px) ;
}

/* Fade out the second bar */
.change .bar2 {
  opacity: 0;
}

/* Rotate last bar */
.change .bar3 {
  -webkit-transform: rotate(45deg) translate(-8px, -8px) ;
  transform: rotate(45deg) translate(-8px, -8px) ;
}

.ul-class{
  display: flex;
  flex-direction: column;
  align-items: center;
  position: absolute;
  background: #fe043c;
  width: 100%;
  padding: 5%;
  transition: 0.4s;
}

.ul-class li{
  list-style: none;
  padding-bottom: 5%;
}

.ul-class li a{
  text-decoration: none;
  color: white;
  font-family: sans-serif;
}

.user-li{
  display: flex;
  flex-direction: row;
  align-items: center;
}

.user-img{
  cursor: pointer;
}

.oval-img{
  display: none;
}

#red_body{
  Height:600px;
  margin-top: -18%;
}



#red_body img{
  margin-top: 60%;
  width: 250%;
  margin-left: -200%;
}

.discover{
  margin-top: -62%;
  margin-left: -25%;
  font-size:xx-small;
}

.discover input{
  height:25px;
  width: 70%;
}

input[type="submit"]{
  height:20px;
  width: fit-content;
  margin-left: -15%;
  margin-bottom: -5%;
}

input[type="submit"]:hover{
  font-size: large;
}

.location{
  margin-top: 10%;
  width: 60%;
}

.slider-button-div{
 margin-top: -70%;
 margin-left: 55%;
 background: #fe043c;
 border-radius: 4px;
}

.lettuce-img{
  display: none;
}

.gradient-div-cover{
  display: none;
}

}

</style>
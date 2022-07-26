<!-- Please remove this file from your project -->
<template>
  <div>
    <nav>
      <ul style="display:flex; list-style: none;">
        
          <li style="padding-left: 80px;"><a class="text-dec"  href="#"><img src="logo.png" style="width:155px; height: 52px;" alt=""></a></li>
                
          <li style="margin: auto;"><a class="text-dec menupadding60" id="menuone" href="#">Menu One</a></li>
          <li style="margin: auto;"><a class="text-dec menupadding30" id="menutwo" href="#">Menu Two</a></li>
          <li  style="margin: auto;"><a class="text-dec menupadding30" id="menuthree" href="#">Menu Three</a></li>
          <li  style="margin: auto;"><a class="text-dec menupadding30" id="menufour" href="#">Menu Four</a></li>
          <div style="display:flex; margin: auto 0 auto 28%;">
            <li style="margin: auto; display: flex; align-items: center; padding-right: 120px;">
              <img src="Mask.png" alt="">
              <img src="Oval.png" style="margin-top: -40px; margin-left: -16px;" alt="">
              <a class="text-dec" style="color: white; padding-left: 10px;" href="#">User</a>
              <img src="Icon.png" style="cursor: pointer; padding-left: 10px; margin-top: -8px;" alt="">
            </li>
          </div>
      </ul>
    </nav>
    <div id="red_body">
      
      
      <img v-if="imageExists" src="lettuc.png" style="z-index: 0; width: 120%; margin-left: -58.5%; margin-top: -16%;" alt="">
      
      <img v-if="imageExists" src="elici.png" style="z-index: 1; margin-left: -94%; margin-top: -138%; width: 175%;" alt=""></img>
      
      <img v-else src="pngwin.png" style="z-index: 0; width: 150%; margin-left: -75.5%; margin-top: 50%;" alt="">
      
      <div v-if="imageExists" style="margin-top: -645px; margin-left: -320px; width:315px; height:600px; background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); background-size: 29px 29px; background-position: -9px -9px;">
      </div>
      
    </div>
    <div class="text-dec discover">
      <h1>Discover Restaurant</h1>
      <h1>& Delicious Food</h1>
      <input class="textInput" type="text" value="search restaurant,food"><input type="submit" style="cursor: pointer;" value="GO">
    </div>
    
    <div class="location">
      <img src="placehold.png" style="cursor: pointer; margin-left: 15%;" alt="">
      <h4 style="font-family: sans-serif; font-weight: 500; margin-left: 8%; font-size: larger;">Hydrabad</h4>
    </div>
    <div style="float:right; display: flex;">
      <div style="display: flex; align-items: center; margin-right: -30px;">
        <img @click="toggleImage" src="Ellipse.png" style="cursor: pointer; width: 30%;" alt="">
        <img @click="toggleImage" src="Path1.png" style="cursor: pointer; margin-left: -20%; width: 10%;" alt="">
        <img @click="toggleImage" src="Path9.png" style="cursor: pointer; margin-left: -9%; width: 41%;" alt="">
      </div>
      <div style="cursor: pointer; display: flex; align-items: center;">
        <img @click="toggleImage" src="Path9.png" style="cursor: pointer; width: 41%;" alt="">
        <img @click="toggleImage" src="Path2.png" style="cursor: pointer; margin-left: -10%; width: 10%;" alt="">
        <img @click="toggleImage" src="Ellipse.png" style="cursor: pointer; margin-left: -20%; width: 30%;" alt="">
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'NuxtTutorial',
  data() {
  return {
    imageExists: true
  }
  },
  methods: {
    toggleImage(){
      this.imageExists = !this.imageExists;
    }
  }
}
</script>

<style scoped>
.text-dec{
  text-decoration: none;
  color: #2e266f;
  font-family: sans-serif;
  white-space: nowrap;
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

/* input[type="text"] {
    width: 34%;
    height: 57px;
    font-size: 16px;
    padding-left: 40px;
    padding-right: 12px;
    color: rgba(0,0,0,0.3);
    border: none;
    box-shadow: 5px 5px 28px #f2ccbb;
    margin-top: 15px;
} */

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

.menupadding60{
  padding-left: 60px;
}

.menupadding30{
  padding-left: 30px;
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



</style>
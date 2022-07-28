<template>

    <div>
    <div class="upper-div">
        <div class="sub-upper-div1">
            
        </div>
        <div class="sub-upper-div2">
            <h4 class="sub-upper-div2-h4-1">some top restaurant for</h4>
            <h4 class="h4-font-weight">dining our or in!</h4>
        </div>
        <div class="sub-upper-div3">
            <h4 class="h4-font-weight sub-upper-div3-h4-margin">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed</h4>
            <h4 class="h4-font-weight">do eiusmod tempor incididunt ut labore et dolore magna</h4>
            <h4 class="h4-font-weight">aliqua. Ut enim ad minim veniam, quis nostrud exercitation</h4>
        </div>
    </div>
    <div class="gradient-div1">
    </div>

    <div class="div-display-align">
        <div class="below-sub-upper-div1">
            <img src="foo.png" class="below-sub-upper-div1-img">
            <div class="top-res-card-div">
            </div>
            <div class="top-res-card-text-div">
                <h2 class="top-res-card-text-div-h2">Fire Water</h2>
                <h5 class="top-res-card-text-div-h5-1">we are all about we are all about to the fullest and all</h5>
                <h5 class="top-res-card-text-div-h5-2">content dining out or in!dining out or in!</h5>
                <div class="div-display-align location-button">
                    <img class="top-res-location" src="placehold.png">
                    <h5 class="top-res-h5">Hitech City</h5>
                    <button class="top-res-button">Book Now <span><img src="Path11.png" class="top-res-button-span-img"></span></button>
                </div>
            </div>
        </div>
        
        <div class="below-sub-upper-div2">
            <img src="food.png" class="below-sub-upper-div1-img">
            <div class="top-res-card-div">
            </div>
            <div class="top-res-card-text-div">
                <h2 class="top-res-card-text-div-h2">the Wonton</h2>
                <h5 class="top-res-card-text-div-h5-1">we are all about we are all about to the fullest and all</h5>
                <h5 class="top-res-card-text-div-h5-2">content dining out or in!dining out or in!</h5>
                <div class="div-display-align location-button">
                    <img class="top-res-location" src="placehold.png">
                    <h5 class="top-res-h5">gachibowli</h5>
                    <button class="top-res-button">Book Now <span><img src="Path11.png" class="top-res-button-span-img"></span></button>
                </div>
            </div>
        </div>

        <div class="see-more-div">
            <div class="path92" id="path9">
                <img src="Path92.png">
                <img src="ova.png" class="see-more-div-img-2">
                <img class="see-more-div-img-3" src="Path22.png">
            </div>
            <h3 class="see-more-h3-text">see more</h3>
        </div>
    </div>
    <div class="gradient-div2">
    </div>

    </div>

</template>
<script>

export default{

}

</script>
<style scoped>

.upper-div{
   margin-top: 15%; 
   display: flex;
}

.sub-upper-div1{
   width: 1.2%; 
   background: #fe043c; 
   height: 73px; 
   margin-left: 8%;
}

.sub-upper-div2{
   line-height: 0; 
   font-family: sans-serif; 
   font-size:37px; 
   margin-left: 50px; 
   color: #2e266f;
}

.sub-upper-div2-h4-1{
   margin-top:20px; 
   font-weight: 500; 
   margin-bottom: -10px;
}

.h4-font-weight{
    font-weight: 500;
}

.sub-upper-div3{
    line-height: 0; 
    margin-top: -6px; 
    font-family: sans-serif; 
    opacity: 0.7; 
    margin-left: 95px; 
    font-size: 21px;
}

.sub-upper-div3-h4-margin{
    margin-top: 15px;
}

.gradient-div1{
    width:220px; 
    height:45px; 
    background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
    background-size: 29px 29px; 
    background-position: -16px -9px; 
    margin-top: 5%;
}

.div-display-align{
    display:flex; 
    align-items: center;
}

.below-sub-upper-div1{
    width: 33%; 
    height: 30%; 
    margin-right: 4%;
}

.below-sub-upper-div1-img{
    max-width: -webkit-fill-available;
}

.top-res-card-div{
    background: #fe043c; 
    max-width: -webkit-fill-available; 
    height: 13.2vmax; 
    opacity: 0.689; 
    margin-top: -41.5%; 
    border-radius: 8px;
}

.top-res-card-text-div{
    color:white; 
    position:relative; 
    margin-top: -37%; 
    margin-left: 8%; 
    line-height: 0;
}

.top-res-card-text-div-h2{
    color:white; 
    font-size: 2.5em; 
    font-family: sans-serif;
}

.top-res-card-text-div-h5-1{
    font-weight: 500;
}

.top-res-card-text-div-h5-2{
    margin-top: -2%; 
    font-weight: 500;
}

.top-res-location{
    cursor: pointer; 
    max-width: 4%;
}

.top-res-h5{
    margin-left: 2%; 
    font-weight: 500;
}

.top-res-button{
    cursor: pointer; 
    background: rgb(255, 248, 248); 
    border: none; 
    color: rgb(219, 3, 51); 
    margin-left: 40%; 
    margin-top: 0%; 
    width: 30%; 
    height: 3.5vmax; 
    display: flex; 
    align-items: center; 
    padding-left: 19px; 
    border-bottom-right-radius: 9px 9px;
}

.top-res-button-span-img{
    width:60%; 
    margin-top: 9%;
}

.below-sub-upper-div2{
    width: 33%;
}

.see-more-div-img-2{
    margin-left: -10%;
}

.see-more-div-img-3{
    margin-left: -158%;
}

.path92{
    margin-left: 85%;
    cursor: pointer; 
    display:flex; 
    align-items: center;
}

.see-more-h3-text{
    cursor: pointer; 
    color:#fe043c; 
    margin-left: 87%; 
    white-space: nowrap; 
    font-size: xx-large; 
    font-weight: 500; 
    font-family: sans-serif; 
    margin-top: 20px;
}

.gradient-div2{
    width:23%; 
    height:24vmax; 
    background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
    background-size: 29px 29px; 
    background-position: 2px 29px; 
    margin-left: 49%; 
    margin-top: -19.4%; 
    margin-bottom: 5%;
}

@media screen and (max-width: 480px) {

    .upper-div{
        display: flex;
        flex-direction: column;
        white-space: nowrap;
    }

    .sub-upper-div2{
    margin-top: -14%;
    }

    .sub-upper-div2 h4{
        font-size: 20px;
    }

    .sub-upper-div3{
    margin-left: 05%;
    }
    
    .sub-upper-div3 h4{
        font-size: 11px;
    }

    .div-display-align{
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .below-sub-upper-div1 {
        width: 80%;
        margin-right: 0;
    }

    .below-sub-upper-div2{
        width: 80%;
        margin-right: 0;
    }

    .top-res-card-text-div-h5-1{
        white-space: nowrap;
        font-size: 10px;
    }

    .top-res-card-text-div-h5-2{
        white-space: nowrap;
        font-size: 10px;
    }

    .location-button{
        display: flex;
        flex-direction: row;
        background: #fe043c;
        padding: 5%;
        margin-left: -9%;
        margin-top: -5%;
        margin-bottom: 5%;
        border-radius: 4px;
    }

    .top-res-button{
        padding: 8%;
    }

    .see-more-div{
        margin-left: -68%;
    }

    .top-res-card-div{
        height: 20.2vmax;
    }
    
}

</style>
<template>
<div>
    <div class="main-div">
        
        <div class="inside-main-div">
            <div class="red-bar">

            </div>
            <h1 class="text-below-red-bar">advanced booking</h1>
            <div class="input-box-div">
                <input class="textinput1" type="text" value="search restaurant"><input class="go-button" type="submit" value="GO">
            </div>
            <div class="date-time-guests-dropdown">
                <div class="date-div">
                    <h3 class="div-h3-1">Date <span><img src="Polygon1.png"></span></h3>
                    <h3 class="div-h3-2">15-9-19</h3>
                </div>
                <div class="time-div">
                    <h3 class="div-h3-1">Time <span><img src="Polygon1.png"></span></h3>
                    <h3 class="div-h3-2">9.30 PM</h3>
                </div>
                <div class="guests-div">
                    <h3 class="div-h3-1">Guests <span><img src="Polygon1.png"></span></h3>
                    <h3 class="div-h3-2">2 People</h3>
                </div>
            </div>
        </div>
        
    </div>
    <div class="radial-gradient-1">
    </div>
    <img class="cabbage-img" src="Pngtre.png">
    <div class="radial-gradient-2">
    </div>
    <img class="cauli-img" src="5a1.png">
    
</div>        
</template>
<script>

    export default{

    }

</script>
<style scoped>

.main-div{
    background: #FFEDDE; 
    display: flex;
    justify-content: center; 
    align-items: center; 
    height: 110vmin;
}

.inside-main-div{
    background: white; 
    display: flex; 
    flex-direction: column; 
    align-items: center; 
    max-width: 75%; 
    min-width: 70%;
}

.red-bar{
    width: 7.5%; 
    background: #fe043c; 
    height: 10px; 
    margin-top: 9%;
}

.text-below-red-bar{
    font-family: sans-serif; 
    font-weight: 500; 
    color: #2e266f;
}

.input-box-div{
    white-space: nowrap; 
    margin-left: -18%;
}

.go-button{
    cursor: pointer;
}

.date-time-guests-dropdown{
    display: flex; 
    margin-top: 2%; 
    margin-bottom: 3%;
}

.date-div{
    margin-right: 30%; 
    white-space: nowrap; 
    margin-left: -30%;
}

.div-h3-1{
    cursor: pointer; 
    font-family: sans-serif; 
    font-weight: 500; 
    color: #2e266f;
}

.div-h3-2{
    font-family: sans-serif; 
    font-weight: 500; 
    opacity: 0.389;
}

.time-div{
    white-space: nowrap; 
    margin-right: 30%;
}

.guests-div{
    white-space: nowrap;
}

.radial-gradient-1{
    width:23%; 
    height:22vmax; 
    background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
    background-size: 29px 29px; 
    background-position: 2px 19px; 
    position: inherit; 
    margin-top: -45.5%; 
    margin-left: 66%;
}

.cabbage-img{
    height: 155vmin; 
    margin-top: -43.25%; 
    margin-left: -16.5%;
}

.radial-gradient-2{
    width:23%; 
    height:24vmax; 
    background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
    background-size: 29px 29px; 
    background-position: 2px 19px; 
    position: inherit; 
    margin-top: -42%; 
    margin-left: 11%;
}

.cauli-img{
    float: right; 
    margin-top: -28%; 
    width: 11.4%;
}

.textinput1{
    width: 155%;
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
}

input[type="submit"]:hover{
    font-size: x-large;
    transition: 0.5s;
    transition-timing-function: ease-in-out;
}

@media screen and (max-width: 480px) {
    .red-bar{
        width: 25%
    }

    .text-below-red-bar{
        text-align: center;
    }

    .input-box-div{
        margin: 0;
    }

    .textinput1{
    width: 100%;
    height: 40px;
    font-size: 14px;
    padding-left: 0;
    padding-right: 0;
    color: rgba(0,0,0,0.3);
    border: none;
    box-shadow: 5px 5px 28px #f2ccbb;
    margin-top: 15px;
    }

    input[type="submit"]{
        margin-left: -22%;
        width: 20%;
        height: 10%;
    }

    .date-time-guests-dropdown{
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .date-div{
        margin-right: 0%;
        margin-left: 0%;
    }

    .time-div{
        margin-right: 0%;
    }

    .cabbage-img{
        display: none;
    }

    .cauli-img{
        display: none;
    }
}

</style>
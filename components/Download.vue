<template>
    <div>
        <div class="main-div">
            <div class="sub-main-div">
                <div class="red-bar-download-div">
                    <div class="red-bar-div">
                    </div>
                    <div class="download-app-div">
                        <h4 class="download-app-div-h4-1">Download app for</h4>
                        <h4 class="h4-font-weight">Exciting Deals</h4>
                    </div>
                </div>
                <div>
                    <div class="lorem-ipsum-div">
                        <h4 class="lorem-ipsum-div-h4">Lorem ipsum dolor sit amet,</h4>
                        <h4 id="h4-text-align" class="h4-font-weight">consectetur adipiscing elit, sed do</h4>
                    </div>
                </div>
                <div class="ios-ps-img-div">
                    <img class="img-width-cursor" src="pstore.png">
                    <img class="img-width-cursor" src="ios.png">
                </div>
            </div>
            <div class="sub-main-div-2">
                    <img class="phone-img" src="phoned.png">
                    <img class="green-veg-img" src="5a1c.png">
                    <div class="radial-gradient-div">
                    </div>
            </div>
        </div>
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
    padding-bottom: 15%;
}

.sub-main-div{
    width: 50%; 
    display: flex; 
    justify-content: center; 
    flex-direction: column; 
    margin-left: 8%;
}

.red-bar-download-div{
    display: flex;
}

.red-bar-div{
    min-width: 4.8%; 
    background: #fe043c; 
    height: 120px; 
    margin-left: 7%; 
    margin-top: -3.1%;
}

.download-app-div{
    line-height: 0; 
    font-family: sans-serif; 
    font-size:55px; 
    margin-left: 50px; 
    color: #2e266f; 
    white-space: nowrap;
}

.download-app-div-h4-1{
    margin-top:20px; 
    font-weight: 500; 
    margin-bottom: -10px;
}

.h4-font-weight{
    font-weight: 500;
}

.lorem-ipsum-div{
    margin-bottom: 12%; 
    line-height: 0; 
    margin-top: -6px; 
    font-family: sans-serif; 
    opacity: 0.7; 
    margin-left: 22.5%; 
    font-size: 21px;
}

.lorem-ipsum-div-h4{
    font-weight: 500; 
    margin-top: 15px;
}

.ios-ps-img-div{
    margin-left: 22.5%;
}

.img-width-cursor{
    width: 35%; 
    cursor: pointer;
}

.sub-main-div-2{
    width: 45%; 
    display: flex; 
    flex-direction: column; 
    margin-left:7%
}

.phone-img{
    width: 75%; 
    position: relative;
}

.green-veg-img{
    margin-top: -92%; 
    margin-left: -24%; 
    width: fit-content; 
    height: 80%;
}

.radial-gradient-div{
    width:23%; 
    height:22vmax; 
    background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); 
    background-size: 29px 29px; 
    background-position: 2px 19px; 
    position: inherit; 
    margin-top: -95%; 
    margin-left: 0%;
}

@media screen and (max-width: 480px) {
    .main-div{
        padding-top: 15%;
        flex-direction: column;
        padding-bottom: 75%;
    }

    .sub-main-div{
        width: auto;
        margin-left: 0;
    }

    .download-app-div-h4-1{
        margin-top: 43%;
        font-size: x-large;
    }

    .h4-font-weight{
        font-size: x-large;
    }

    .lorem-ipsum-div{
        margin-top: 0;
        margin-left: 0;
    }

    .lorem-ipsum-div-h4{
        font-size: 16px;
        text-align: center;
        white-space: nowrap;
    }

    #h4-text-align{
        font-size: 16px;
        text-align: center;
    }

    .ios-ps-img-div{
        text-align: center;
        margin-left: 0;
    }

    .sub-main-div-2{
        width: auto;
    }

    .green-veg-img{
        width: auto;
        margin-top: -92%;
        margin-left: 35%;
    }
}

</style>

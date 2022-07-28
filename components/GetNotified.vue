<template>
    <div>
        <div>
            <div class="main-div-1">
                        <h4 class="main-div-1-h4-1">Get notified</h4>
                        <h4 class="h4-font-weight">about new amazing products</h4>
            </div>
            <div class="main-div-2">
                        <h4 class="main-div-2-h4-1">Lorem ipsum is simply dummy text of the printing and typesetting industry.</h4>
                        <h4 class="h4-font-weight">It has been the industry's standard dummy text ever since.</h4>
            </div>
            <div class="main-div-3">
                <input class="inputtext2" type="text" value="Email"><input type="submit" class="pointer-to-cursor"><span class="button-span-style">&#8594;</span>
            </div>
            <div class="main-div-4">
                <h4 class="pointer-to-cursor">Product</h4>
                <h4 class="pointer-to-cursor">Company</h4>
                <h4 class="pointer-to-cursor">Learn More</h4>
                <h4 class="pointer-to-cursor">Get in touch</h4>
            </div>
            <div class="main-div-5">
                <img class="pointer-to-cursor" src="Shape3.png">
                <img class="pointer-to-cursor" src="Shape2.png">
                <img class="pointer-to-cursor" src="Shape1.png">
                <img class="pointer-to-cursor" src="Shape.png">
                 <span>&#169;<span>2019 indianpix</span></span> 
            </div>
            <img class="plant-img" src="Group8.png">
            <div class="radial-gradient-div">
            </div>
        </div>
    </div>
</template>
<script>
    export default{
        data(){
            return {
                someData: null
            }
        }
    }
</script>
<style scoped>

.main-div-1{
    line-height: 0; 
    font-family: sans-serif; 
    font-size:xx-large; 
    color: #2e266f; 
    white-space: nowrap; 
    display: flex; 
    flex-direction: column; 
    align-items: center; 
    margin-top: 10%;
}

.main-div-1-h4-1{
    margin-top:20px; 
    font-weight: 500; 
    margin-bottom: -10px;
}

.h4-font-weight{
    font-weight: 500;
}

.main-div-2{
    margin-bottom: 3%; 
    line-height: 0; 
    margin-top: -6px; 
    font-family: sans-serif; 
    opacity: 0.7; 
    font-size: small; 
    display: flex; 
    flex-direction: column; 
    align-items: center;
}

.main-div-2-h4-1{
    font-weight: 500; 
    margin-top: 15px;
}

.h4-font-weight{
    font-weight: 500;
}

.main-div-3{
    white-space: nowrap; 
    display: flex; 
    justify-content: center; 
    align-items: center; 
    margin-bottom: 1%;
}

.inputtext2{
    width: 24%;
    height: 57px;
    font-size: 16px;
    padding-left: 40px;
    padding-right: 12px;
    color: rgba(0,0,0,0.3);
    border: none;
    box-shadow: 5px 5px 28px #f2ccbb;
    margin-top: 15px;
    border-radius: 25px;
}

input[type="submit"] {
    margin-top: 1.2%;
    margin-left: -60px;
    font-size: large;
    height: 48px;
    width: 50px;
    background: #fe043c;
    color: #fe043c;
    border: 0;
    -webkit-appearance: none;
    border-radius: 25px;
}

.pointer-to-cursor{
    cursor:pointer;
}

.button-span-style{
    cursor:pointer; 
    color: white; 
    margin-left: -3.2%; 
    margin-top: 1%; 
    font-size: xx-large;
}

.main-div-4{
    margin-bottom: 5%; 
    display: flex; 
    justify-content: center; 
    font-weight: 500; 
    font-family: sans-serif; 
    opacity: 0.7; 
    font-size: small; 
    gap: 2%; 
    margin-left: 3%;
}

.pointer-to-cursor{
    cursor:pointer;
}

.main-div-5{
    display: flex; 
    justify-content: flex-end; 
    gap: 4%; 
    margin-right: 2%; 
    margin-bottom: 2%;
}



.plant-img{
    margin-top: -40%; 
    margin-left:-2.5%; 
    width: 38%;
}

.radial-gradient-div{
    width:34%; 
    height:42vmax; 
    background-image: radial-gradient(rgb(0 0 0 / 2.5%) 8px, transparent 0); 
    background-size: 67px 67px; 
    background-position: 7px -16px; 
    position: inherit; 
    margin-top: -44%; 
    margin-left: 0%;
}

@media screen and (max-width: 480px) {
    .main-div-1{
        font-size: 18px;
    }

    .main-div-2{
        font-size: 10px;
        white-space: nowrap;
        overflow: auto;
    }

    .main-div-2-h4-1{
        display: none;
    }

    .main-div-3{
        margin-left: -5%;
    }

    .inputtext2{
        width: 52%;
    }

    .pointer-to-cursor{
        margin-top: 4.2%;
    }

    .button-span-style{
        margin-left: -12.2%;
        margin-top: 3%;
    }

    .main-div-4{
        flex-direction: column;
        align-items: center;
    }

    .main-div-5{
        align-items: flex-end;
    }

    .radial-gradient-div{
        margin-top: -75%;
    }
}

</style>

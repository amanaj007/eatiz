<template>
<div>
    <div style="background: #FFEDDE; display: flex;justify-content: center; align-items: center; height: 110vmin;">
        
        <div style="background: white; display: flex; flex-direction: column; align-items: center; max-width: 75%; min-width: 70%;">
            <div style="width: 7.5%; background: #fe043c; height: 10px; margin-top: 9%;">

            </div>
            <h1 style="font-family: sans-serif; font-weight: 500; color: #2e266f;">advanced booking</h1>
            <div style="white-space: nowrap; margin-left: -18%;">
                <input class="textinput1" type="text" value="search restaurant"><input style="cursor: pointer;" type="submit" value="GO">
            </div>
            <div style="display: flex; margin-top: 2%; margin-bottom: 3%;">
                <div style="margin-right: 30%; white-space: nowrap; margin-left: -30%;">
                    <h3 style="cursor: pointer; font-family: sans-serif; font-weight: 500; color: #2e266f;">Date <span><img src="Polygon1.png" alt=""></span></h3>
                    <h3 style="font-family: sans-serif; font-weight: 500; opacity: 0.389;">15-9-19</h3>
                </div>
                <div style="white-space: nowrap; margin-right: 30%;">
                    <h3 style="cursor: pointer; font-family: sans-serif; font-weight: 500; color: #2e266f;">Time <span><img src="Polygon1.png" alt=""></span></h3>
                    <h3 style="font-family: sans-serif; font-weight: 500; opacity: 0.389;">9.30 PM</h3>
                </div>
                <div style="white-space: nowrap;">
                    <h3 style="cursor: pointer; font-family: sans-serif; font-weight: 500; color: #2e266f;">Guests <span><img src="Polygon1.png" alt=""></span></h3>
                    <h3 style="font-family: sans-serif; font-weight: 500; opacity: 0.389;">2 People</h3>
                </div>
            </div>
        </div>
        
    </div>
    <div style="width:23%; height:22vmax; background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); background-size: 29px 29px; background-position: 2px 19px; position: inherit; margin-top: -45.5%; margin-left: 66%;">
    </div>
    <img src="Pngtre.png" style="height: 155vmin; margin-top: -43.25%; margin-left: -16.5%;" alt="">
    <div style="width:23%; height:24vmax; background-image: radial-gradient(rgb(0 0 0 / 20%) 3.1px, transparent 0); background-size: 29px 29px; background-position: 2px 19px; position: inherit; margin-top: -42%; margin-left: 11%;">
    </div>
    <img src="5a1.png" style="float: right; margin-top: -28%; width: 11.4%;" alt="">
    
</div>        
</template>
<script>

    export default{

    }

</script>
<style scoped>
/* FFEDDE */

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

/* input[type="text"] {
    width: 155%;
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
}

input[type="submit"]:hover{
    font-size: x-large;
    transition: 0.5s;
    transition-timing-function: ease-in-out;
}

</style>
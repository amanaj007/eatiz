<template>
    <div>
        <div>
            <div style="line-height: 0; font-family: sans-serif; font-size:xx-large; color: #2e266f; white-space: nowrap; display: flex; flex-direction: column; align-items: center; margin-top: 10%;">
                        <h4 style="margin-top:20px; font-weight: 500; margin-bottom: -10px;">Get notified</h4>
                        <h4 style="font-weight: 500;">about new amazing products</h4>
            </div>
            <div style="margin-bottom: 3%; line-height: 0; margin-top: -6px; font-family: sans-serif; opacity: 0.7; font-size: small; display: flex; flex-direction: column; align-items: center;">
                        <h4 style="font-weight: 500; margin-top: 15px;">Lorem ipsum is simply dummy text of the printing and typesetting industry.</h4>
                        <h4 style="font-weight: 500;">It has been the industry's standard dummy text ever since.</h4>
            </div>
            <div style="white-space: nowrap; display: flex; justify-content: center; align-items: center; margin-bottom: 1%;">
                <input class="inputtext2" type="text" value="Email"><input type="submit" style="cursor:pointer;" :value="someData"><span style="cursor:pointer; color: white; margin-left: -3.2%; margin-top: 1%; font-size: xx-large;">&#8594;</span>
            </div>
            <div style="margin-bottom: 5%; display: flex; justify-content: center; font-weight: 500; font-family: sans-serif; opacity: 0.7; font-size: small; gap: 2%; margin-left: 3%;">
                <h4 style="cursor:pointer;">Product</h4>
                <h4 style="cursor:pointer;">Company</h4>
                <h4 style="cursor:pointer;">Learn More</h4>
                <h4 style="cursor:pointer;">Get in touch</h4>
            </div>
            <div style="display: flex; justify-content: flex-end; gap: 4%; margin-right: 2%; margin-bottom: 4%;">
                <img src="Shape3.png" style="cursor:pointer;" alt="">
                <img src="Shape2.png" style="cursor:pointer;" alt="">
                <img src="Shape1.png" style="cursor:pointer;" alt="">
                <img src="Shape.png" style="cursor:pointer;" alt="">
                 <span>&#169;<span>2019 indianpix</span></span> 
            </div>
            <img src="Group8.png" style="margin-top: -40%; margin-left:-2.5%; width: 38%;" alt="">
            <div style="width:31%; height:38vmax; background-image: radial-gradient(rgb(0 0 0 / 2.5%) 8px, transparent 0); background-size: 67px 67px; background-position: 7px -21px; position: inherit; margin-top: -40%; margin-left: 0%;">
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

/* input[type="text"] {
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
} */

input[type="submit"] {
    margin-top: 1.2%;
    margin-left: -60px;
    font-size: large;
    height: 48px;
    width: 50px;
    background: #fe043c;
    color: white;
    border: 0;
    -webkit-appearance: none;
    border-radius: 25px;
}

</style>
<template>
    <div>
        <div class="explore-our-foods">
            <h2 class="explore-our-foods-h2">
                Explore Our Foods
            </h2>
            <h5 class="explore-our-foods-h5">
                Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
            </h5>
            <h5 class="explore-our-foods-h5">
                tempor invidunt ut labore et dolore magna.
            </h5>
        </div>
        <div class="food-card">
            <div class="inside-food-card">
                <div class="cards-div">
                    <img class="cards-div-img" src="1.png">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
                </div>
                <div class="cards-div">
                    <img class="cards-div-img" src="1.png">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
                </div>
                <div class="cards-div-2">
                    <img class="cards-div-img" src="3.png">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
                </div>
            </div>
            <div class="inside-food-card">
                <div class="cards-div">
                    <img src="4.png" class="cards-div-img">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
                </div>
                <div class="cards-div">
                    <img src="5.png" class="cards-div-img">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
                </div>
                <div class="cards-div-2">
                    <img src="6.png" class="cards-div-img">
                    <div class="sub-cards-div">
                        <div class="sub-sub-cards-div">
                            <h3 class="sub-sub-cards-div-h3-1">Ham Sandwich</h3>
                            <h3 class="sub-sub-cards-div-h3-2">$10.50</h3>
                        </div>
                        <div class="next-sub-cards-div">
                            <h4>Lorem ipsum dolor sit amet, consetetur sadipscing</h4>
                            <h4>elitr</h4>
                        </div>
                    </div>
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
.explore-our-foods{
    margin-top: 10%; 
    display: flex; 
    flex-direction: column; 
    align-items: center; 
    margin-bottom: 4%;
}

.explore-our-foods-h2{
    color: #2e266f; 
    font-weight: 500; 
    font-family: sans-serif;
}

.explore-our-foods-h5{
    margin-top: 0px; 
    line-height: 0; 
    font-weight: 500; 
    opacity: 0.5; 
    font-family: sans-serif;
}

.food-card{
    display: flex; 
    flex-direction: column; 
    align-items: center; 
    margin-bottom: 10%;
}

.inside-food-card{
    display: flex; 
    justify-content: center; 
    margin-bottom: 5%;
}

.cards-div{
    cursor: pointer; 
    width: 28%; 
    margin-right: 3%; 
    background: white; 
    border-radius: 8px; 
    box-shadow: 0px 10px 0px 1px #F9F9FB;
}

.cards-div-img{
    width: -webkit-fill-available;
}

.sub-cards-div{
    display: flex; 
    flex-direction: column; 
    background: white;
}

.sub-sub-cards-div{
    display: flex; 
    flex-direction: row; 
    justify-content: space-around; 
    font-family: cursive;
}

.sub-sub-cards-div-h3-1{
    color: #2e266f;
}

.sub-sub-cards-div-h3-2{
    color: #f98169;
}

.next-sub-cards-div{
    opacity: 0.4; 
    margin-left: 10%; 
    margin-bottom: 10%; 
    line-height: 0; 
    font-size: small;
}

.cards-div-2{
    cursor: pointer; 
    width: 28%; 
    background: white; 
    border-radius: 8px; 
    box-shadow: 0px 10px 0px 1px #F9F9FB;
}   

@media screen and (max-width: 480px) {
    .explore-our-foods-h5{
        overflow: auto;
    }

    .food-card{
        align-items: baseline;
    }

    .inside-food-card{
        flex-direction: column;
        align-items: center;
        max-width: -webkit-fill-available;
        padding-left: 5%;
        padding-right: 5%;
    }

    .cards-div{
        width: fit-content;
        max-width: -webkit-fill-available;
        margin-right: 0;
    }

    .cards-div-2{
        width: fit-content;
        max-width: -webkit-fill-available;
        margin-right: 0;
    }
}

</style>
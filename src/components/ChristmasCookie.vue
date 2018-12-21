<template>
    <div class="main">
        <div class="plate">
            <div class="message">
                <p class="merry">Merry</p> 
                <p class="christmas">Christmas</p>
            </div>
            <div class="cookie">
                <div class="frosting">
                    <div class="snowflake">
                        <div class="line line-1"></div>
                        <div class="line line-2"></div>
                        <div class="line line-3"></div>
                        <div class="arrows arrows-1">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>
                        <div class="arrows arrows-2">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>
                        <div class="arrows arrows-3">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>
                        <div class="arrows arrows-4">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>
                        <div class="arrows arrows-5">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>
                        <div class="arrows arrows-6">
                            <div class="arrow-line arrow-line-1"></div>
                            <div class="arrow-line arrow-line-2"></div>
                            <div class="arrow-line arrow-line-3"></div>
                            <div class="arrow-line arrow-line-4"></div>
                        </div>

                        <div class="icing-circles">
                            <div class="circle circle-1"></div>
                            <div class="circle circle-2"></div>
                            <div class="circle circle-3"></div>
                            <div class="circle circle-4"></div>
                            <div class="circle circle-5"></div>
                            <div class="circle circle-6"></div>
                            <div class="circle circle-7"></div>
                            <div class="circle circle-8"></div>
                            <div class="circle circle-9"></div>
                            <div class="circle circle-10"></div>
                            <div class="circle circle-11"></div>
                            <div class="circle circle-12"></div>
                            <div class="circle circle-middle"></div>
                        </div>

                        <div class="silver-sprinkles">
                            <div class="sprinkle sprinkle-1"></div>
                            <div class="sprinkle sprinkle-2"></div>
                            <div class="sprinkle sprinkle-3"></div>
                            <div class="sprinkle sprinkle-4"></div>
                            <div class="sprinkle sprinkle-5"></div>
                            <div class="sprinkle sprinkle-6"></div>
                            <div class="sprinkle sprinkle-7"></div>
                            <div class="sprinkle sprinkle-8"></div>
                            <div class="sprinkle sprinkle-9"></div>
                            <div class="sprinkle sprinkle-10"></div>
                            <div class="sprinkle sprinkle-11"></div>
                            <div class="sprinkle sprinkle-12"></div>
                            <div class="sprinkle sprinkle-middle"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Pacifico');

    .main {
        position: relative;
        display: block;
        margin: auto;
        height: 600px;
        width: 700px;
        background-image: repeating-linear-gradient(
                            to right,
                            transparent 0, #cca05e 10%,
                            transparent 10%, transparent 10.5%,
                            #deb47a 10.5%, #c39c68 20%,
                            transparent 20%, transparent 20.5%
                          ),

                          repeating-linear-gradient(
                            90deg, 
                            #bfaa8f 0, #e8bc85 10%,
                            #774d19 10%, #774d19 10.5%,
                            #cea879 10.5%, #c59b68 20%,
                            #774d19 20%, #774d19 20.5%
                          );

    }

    .plate {
        position: absolute;
        top: 5%;
        left: 12%;
        height: 90%;
        width: 78%;
        background: radial-gradient(circle at left bottom, white, white, #e0e0e0, #afafaf);
        border-right: 5px solid white;
        border-radius: 50%;
        transform: rotate(-45deg);
        box-shadow: -15px 6px 50px 0px #2f2f2f;
    }

    .message {
        position: relative;
        top: 55%;
        left: 22%;
        transform: rotate(31deg);
    }

    .merry, .christmas {
        font-family: 'Pacifico', cursive;
        font-size: 3em;
        margin: 0;
        color: #9a0303;
        line-height: 50px;
    }

    .christmas {
        margin-left: 56px;
    }

    .cookie {
        position: absolute;
        top: 18%;
        left: 17%;
        height: 65%;
        width: 65%;
        border-radius: 50%;
        background: radial-gradient(circle at top left, #eadec4, #eadec4, #e0cfa1, #e1ca98);
        box-shadow: 0px 4px 10px 0px #634806;
        border-top: 3px solid #ebe0c6;
    }

    .frosting {
        position: absolute;
        top: 7%;
        left: 7.5%;
        height: 85%;
        width: 85%;
        border-radius: 50%;
        background: radial-gradient(circle at top, #fafeff, #cef3ff, #cef3ff, lightblue);
        border-bottom: 3px solid #8ac5d6;
        border-top: 3px solid white;
    }

    .snowflake {
        position: absolute;
        height: 95%;
        width: 95%;
        top: 2%;
        left: 2%;
    }

    .line {
        position: absolute;
        height: 100%;
        width: 4%;
        left: 48%;
        background: linear-gradient(to right, #e6e6e6, white, #e6e6e6);
        border-radius: 30px;
    }

    .line-1 {
        transform: rotate(-10deg);
    }

    .line-2 {
        transform: rotate(100deg);
    }

    .line-3 {
        transform: rotate(45deg);
    }

    .arrows {
        position: absolute;
        height: 25%;
        width: 25%;
    }

    .arrows-1 {
        top: 2%;
        left: 36%;
        transform: rotate(-10deg);
    }

    .arrows-2 {
        top: 17%;
        left: 65%;
        transform: rotate(45deg);
    }

    .arrows-3 {
        top: 48%;
        left: 69%;
        transform: rotate(100deg);
    }

    .arrows-4 {
        top: 26%;
        left: 4%;
        transform: rotate(-80deg);
    }

    .arrows-5 {
        top: 58%;
        left: 10%;
        transform: rotate(-130deg);
    }

    .arrows-6 {
        top: 73%;
        left: 38%;
        transform: rotate(-190deg);
    }

    .arrow-line {
        position: absolute;
        height: 50%;
        width: 12%;
        background: linear-gradient(to right, #e6e6e6, white, #e6e6e6);
        border-radius: 30px;
    }

    .arrow-line-1 {
        transform: rotate(-35deg);
    }

    .arrow-line-2 {
        left: 45%;
        transform: rotate(35deg);
    }

    .arrow-line-3 {
        top: 35%;
        transform: rotate(-35deg);
    }

    .arrow-line-4 {
        left: 45%;
        top: 35%;
        transform: rotate(35deg);
    }

    .icing-circles {
        position: absolute;
        height: 95%;
        width: 95%;
        top: 2%;
        left: 2%;
        transform: rotate(45deg);
    }

    .circle {
        position: absolute;
        height: 8%;
        width: 8%;
        border-radius: 50%;
        background: white;
    }

    .circle-1 {
        top: 18%;
        left: 6%;
    }

    .circle-2 {
        top: -3%;
        left: 47%;
    }

    .circle-3 {
        top: 18%;
        left: 87%;
    }

    .circle-4 {
        top: 74%;
        left: 6%;
    }

    .circle-5 {
        top: 96%;
        left: 47%;
    }

    .circle-6 {
        top: 74%;
        left: 87%;
    }

    .circle-7 {
        top: 29%;
        left: 38%;
    }

    .circle-8 {
        top: 29%;
        left: 56%;
    }

    .circle-9 {
        top: 47%;
        left: 29%;
    }

    .circle-10 {
        top: 47%;
        left: 64%;
    }

    .circle-11 {
        top: 63%;
        left: 38%;
    }

    .circle-12 {
        top: 63%;
        left: 56%;
    }

    .circle-middle {
        top: 46%;
        left: 47%;
    }



</style>

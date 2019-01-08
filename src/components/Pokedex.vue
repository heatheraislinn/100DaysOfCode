<template>
    <div class="pokedex">
        <div class="poke-monitor">
            <div class="top-buttons">
                <div class="button button-1"></div>
                <div class="button button-2"></div>
            </div>
            <div class="screen"></div>
            <div class="button button-3"></div>
            <div class="hamburger-button">
                <div class="line"></div>
                <div class="line line-2"></div>
                <div class="line line-3"></div>
                <div class="line line-4"></div>
            </div>
        </div>

        <div class="left-bottom">
            <div class="button button-4"></div>
            <div class="pill-button pill-1"></div>
            <div class="pill-button pill-2"></div>
            <div class="green-screen"></div>
            <div class="plus-button">
                <div class="plus-arms vert"></div>
                <div class="plus-arms horiz"></div>
            </div>
        </div>

        <div class="middle-hinge"></div>

        <div class="right-side-box"></div>
    </div>
</template>

<style scoped>
    .pokedex {
        position: relative;
        margin: auto;
        width: 750px;
        height: 450px;
        margin-top: 5%;
        background-color: #dc0a2d;
        border-left: 2px solid black;
        border-right: 2px solid black;
        overflow: hidden;
    }

    .poke-monitor {
        position: absolute;
        left: 5%;
        top: 10%;
        width: 38%;
        height: 55%;
        background-color: #dedede;
        border-radius: 6px;
        border-bottom: 2px solid #545454;
    }

    .top-buttons {
        position: absolute;
        left: 36%;
        top: 3%;
        width: 30%;
        height: 10%;
    }

    .button {
        position: absolute;
        background-color: #dc0a2d;
        border-radius: 50%;
        border-bottom: 1px solid black;
    }

    .button-1 {
        width: 17%;
        height: 50%;
        left: 25%;
    }

    .button-2 {
        width: 17%;
        height: 50%;
        right: 25%;
    }

    .button-3 {
        width: 10%;
        height: 11%;
        left: 15%;
        top: 84%;
    }

    .button-4 {
        width: 14%;
        height: 35%;
        left: 11%;
        top: 5%;
        background-color: #2b2b2b;
    }

    .screen {
        position: absolute;
        width: 68%;
        height: 60%;
        left: 13%;
        top: 11%;
        background-color: #27aafd;
        border: 10px solid black;
    }

    .hamburger-button {
        position: absolute;
        width: 10%;
        height: 11%;
        left: 76%;
        top: 85%;
    }

    .line {
        position: absolute;
        width: 100%;
        height: 12%;
        background-color: black;
    }

    .line-1 {
        top: 1%;
    }

    .line-2 {
        top: 22%;
    }

    .line-3 {
        top: 43%;
    }

    .line-4 {
        top: 65%;
    }

    .left-bottom {
        position: absolute;
        width: 45%;
        height: 30%;
        bottom: 1%;
    }

    .green-screen {
        position: absolute;
        left: 27%;
        top: 31%;
        width: 36%;
        height: 41%;
        background-color: #51ae5f;
        border-radius: 4px;
        border-bottom: 2px solid black;
    }

    .plus-button {
        position: absolute;
        left: 67%;
        top: 5%;
        width: 28%;
        height: 70%;
    }

    .plus-arms {
        position: absolute;
        width: 27%;
        height: 96%;
        background: #2b2b2b;
        border-radius: 5px;
    }

    .vert {
        left: 40%;
        border-bottom: 2px solid black;
        z-index: 2;
    }

    .horiz {
        left: 40%;
        transform: rotate(90deg);
        border-right: 2px solid black;
    }

    .pill-button {
        position: absolute;
        top: 2%;
        width: 12%;
        height: 6%;
        border-radius: 5px;
        border-bottom: 1px solid black;
    }

    .pill-1 {
        left: 28%;
        background: #2d2d2d;
    }

    .pill-2 {
        left: 50%;
        background: #27aafd;
    }

    .middle-hinge {
        position: absolute;
        top: -3%;
        left: 47%;
        width: 7.5%;
        height: 105%;
        border: 2px solid black;
        background: linear-gradient(to right, 
                                        #dc0a2d 0, 
                                        #dc0a2d 15%, 
                                        #deb4bb 15%, 
                                        #deb4bb 25%, 
                                        #dc0a2d 25%, 
                                        #dc0a2d 30%, 
                                        #dd546b 30%,
                                        #dd546b 35%,
                                        #dc0a2d 35%,
                                        #dc0a2d 80%,
                                        #89061c 80%
                                    );
    }

    .right-side-box {
        position: absolute;
        width: 38%;
        height: 79%;
        left: 58%;
        top: 10%;
        background-color: #2d2d2d;
        border-radius: 6px;
        border-bottom: 2px solid black;
    }

</style>

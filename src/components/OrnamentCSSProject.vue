<template>
    <div class="background">
        <div class="red-ornament">
            <div class="ornament-string-1"></div>
            <div class="ornament-top-1"></div>
            <div class="red-ball"> </div>
        </div>

        <div class="red-ornament-shadow">
            <div class="ornament-string-1-shadow"></div>
            <div class="ornament-top-1-shadow"></div>
            <div class="red-ball-shadow"></div>
        </div>

        <div class="green-ornament">
            <div class="ornament-string-2"></div>
            <div class="ornament-top-2"></div>
            <div class="green-ball"> </div>
        </div>

        <div class="green-ornament-shadow">
            <div class="ornament-string-2-shadow"></div>
            <div class="ornament-top-2-shadow"></div>
            <div class="green-ball-shadow"></div>
        </div>

        <div class="white-ornament">
            <div class="ornament-string-3"></div>
            <div class="ornament-top-3"></div>
            <div class="white-ball"></div>
        </div>

        <div class="white-ornament-shadow">
            <div class="ornament-string-3-shadow"></div>
            <div class="ornament-top-3-shadow"></div>
            <div class="white-ball-shadow"></div>
        </div>
    </div>
</template>

<style scoped>
    .background {
        position: relative;
        margin: auto;
        display: block;
        margin-top: 8%;
        width: 950px;
        height: 700px;
        background: repeating-linear-gradient(
            90deg,
            #d5ccb2 0px,
            #d5ccb2 40px,
            #b09f79 40px,
            #b09f79 80px
        );
    }

    .red-ornament {
        position: absolute;
        height: 72%;
        width: 24%;
        left: 50%;
        z-index: 2;
    }

    .ornament-string-1 {
        position: relative;
        height: 75%;
        width: 5%;
        left: 10%;
        border-left: 3px solid white;
    }

    .ornament-top-1 {
        position: relative;
        height: 5%;
        width: 25%;
        left: -2%;
        background: linear-gradient(90deg, #606060 0%, #989898 25%, #606060 50%, #2d2d2d 100%);
    }

    .red-ball {
        position: relative;
        height: 43%;
        width: 100%;
        left: -40%;
        top: -2%;
        background: radial-gradient(circle at 80px 20px, #ea1a1a, #480d0d);
        border-radius: 50%;
        transform: rotate(-25deg);
    }

    .red-ball:before {
        content: "";
        position: absolute;
        background: radial-gradient(circle at 50% 120%, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0) 70%);
        border-radius: 50%;
        bottom: 0.5%;
        left: 5%;
        opacity: 0.3;
        height: 100%;
        width: 90%;
        filter: blur(5px);
        z-index: 2;
    }

    .red-ball:after {
        content: "";
        width: 100%;
        height: 100%;
        position: absolute;
        top: 15%;
        left: 20%;
        border-radius: 50%;
        background: radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8) 14%, rgba(255, 255, 255, 0) 24%);
        transform: translateX(-80px) translateY(-90px) skewX(-20deg);
        filter: blur(10px);
    }

    .red-ornament-shadow {
        position: absolute;
        height: 72%;
        width: 24%;
        left: 57%;
        top: 0%;
        opacity: 0.2;
        z-index: 1;
    }

    .ornament-string-1-shadow {
        position: relative;
        height: 81%;
        width: 5%;
        left: 10%;
        border-left: 3px solid black;
    }

    .ornament-top-1-shadow {
        position: relative;
        height: 5%;
        width: 25%;
        left: -2%;
        background: black;
    }

    .red-ball-shadow {
        position: relative;
        height: 43%;
        width: 100%;
        left: -40%;
        top: -2%;
        background: black;
        border-radius: 50%;
    }

    .green-ornament {
        position: absolute;
        height: 34%;
        width: 24%;
        left: 58%;
        z-index: 2;
    }

    .ornament-string-2 {
        position: relative;
        height: 75%;
        width: 5%;
        left: 10%;
        border-left: 3px solid white;
    }

    .ornament-top-2 {
        position: relative;
        height: 8%;
        width: 25%;
        left: -2%;
        top: -22%;
        background: linear-gradient(90deg, #606060 0%, #989898 25%, #606060 50%, #2d2d2d 100%);
    }

    .green-ball {
        position: relative;
        height: 89%;
        width: 96%;
        left: -39%;
        top: -24%;
        background: radial-gradient(circle at 80px 20px, #37ce28, #0d2b06);
        border-radius: 50%;
        transform: rotate(-25deg);
    }

    .green-ball:before {
        content: "";
        position: absolute;
        background: radial-gradient(circle at 50% 120%, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0) 70%);
        border-radius: 50%;
        bottom: 0.5%;
        left: 5%;
        opacity: 0.3;
        height: 100%;
        width: 90%;
        filter: blur(5px);
        z-index: 2;
    }

    .green-ball:after {
        content: "";
        width: 100%;
        height: 100%;
        position: absolute;
        top: 15%;
        left: 20%;
        border-radius: 50%;
        background: radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8) 14%, rgba(255, 255, 255, 0) 24%);
        transform: translateX(-80px) translateY(-90px) skewX(-20deg);
        filter: blur(10px);
    }

    .green-ornament-shadow {
        position: absolute;
        height: 34%;
        width: 24%;
        left: 66%;
        top: 0%;
        opacity: 0.2;
        z-index: 1;
    }

    .ornament-string-2-shadow {
        position: relative;
        height: 90%;
        width: 5%;
        left: 10%;
        border-left: 3px solid black;
    }

    .ornament-top-2-shadow {
        position: relative;
        height: 8%;
        width: 25%;
        left: -2%;
        top: -22%;
        background: black;
    }

    .green-ball-shadow {
        position: relative;
        height: 89%;
        width: 96%;
        left: -39%;
        top: -24%;
        background: black;
        border-radius: 50%;
    }

    .white-ornament {
        position: absolute;
        height: 34%;
        width: 24%;
        left: 76%;
        z-index: 2;
    }

    .ornament-string-3 {
        position: relative;
        height: 120%;
        width: 5%;
        left: 10%;
        border-left: 3px solid white;
    }

    .ornament-top-3 {
        position: relative;
        height: 8%;
        width: 25%;
        left: -2%;
        top: -22%;
        background: linear-gradient(90deg, #606060 0%, #989898 25%, #606060 50%, #2d2d2d 100%);
    }

    .white-ball {
        position: relative;
        height: 89%;
        width: 96%;
        left: -39%;
        top: -24%;
        background: radial-gradient(circle at 80px 20px, #fff, #989898);
        border-radius: 50%;
        transform: rotate(-25deg);
    }

    .white-ball:before {
        content: "";
        position: absolute;
        background: radial-gradient(circle at 50% 120%, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0) 70%);
        border-radius: 50%;
        bottom: 0.5%;
        left: 5%;
        opacity: 0.3;
        height: 100%;
        width: 90%;
        filter: blur(5px);
        z-index: 2;
    }

    .white-ball:after {
        content: "";
        width: 100%;
        height: 100%;
        position: absolute;
        top: 15%;
        left: 20%;
        border-radius: 50%;
        background: radial-gradient(circle at 50% 50%, rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8) 14%, rgba(255, 255, 255, 0) 24%);
        transform: translateX(-80px) translateY(-90px) skewX(-20deg);
        filter: blur(10px);
    }

    .white-ornament-shadow {
        position: absolute;
        height: 34%;
        width: 24%;
        left: 83%;
        top: 0%;
        opacity: 0.2;
        z-index: 1;
    }

    .ornament-string-3-shadow {
        position: relative;
        height: 131%;
        width: 5%;
        left: 10%;
        border-left: 3px solid black;
    }

    .ornament-top-3-shadow {
        position: relative;
        height: 8%;
        width: 25%;
        left: -2%;
        top: -22%;
        background: black;
    }

    .white-ball-shadow {
        position: relative;
        height: 89%;
        width: 96%;
        left: -39%;
        top: -24%;
        background: black;
        border-radius: 50%;
    }
</style>

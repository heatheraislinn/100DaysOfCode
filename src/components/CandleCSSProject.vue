<template>
    <div class="background">
        <div class="candle">
            <div class="flame">
                <div class="inner-flame"></div>
            </div>
            <div class="wick"></div>
            <div class="candle-top"></div>
            <div class="candle-body"></div>
            <div class="outer-tray">
                <div class="inner-tray">
                    <div class="tray-inner-bottom"></div>
                </div>
            </div>
            <div class="outer-tray-base"></div>
            <div class="bottom-tray-base"></div>
            <div class="tray-shadow"></div>
            <div class="candle-glow"></div>
        </div>
    </div>
</template>

<style scoped>
    .background {
        position: relative;
        margin: auto;
        display: block;
        width: 650px;
        height: 800px;
        background: #0071b2;
    }

    .candle {
        position: relative;
        margin: auto;
        top: 15%;
        width: 50%;
        height: 70%;
    }

    .flame {
        position: absolute;
        top: 15%;
        left: 37%;
        width: 25%;
        height: 15%;
        background: #fbb615;
        border-radius: 80% 0 55% 50% / 55% 0 80% 50%;
        transform: rotate(-45deg);
        z-index: 6;
        animation: flameGrows 4s infinite linear;
    }

    @keyframes flameGrows {
        0% {
            width: 25%;
            height: 15%;
            top: 15%;
        }
        50% {
            width: 26%;
            height: 16%;
            top: 14%;
        }
        100% {
            width: 25%;
            height: 15%;
            top: 15%;
        }
    }

      .inner-flame {
        position: relative;
        margin: auto;
        top: 31%;
        right: 13%;
        width: 65%;
        height: 65%;
        background: orange;
        border-radius: 80% 0 55% 50% / 55% 0 80% 50%;
    }

    .wick {
        position: absolute;
        top: 27%;
        left: 50%;
        width: 5%;
        height: 5%;
        background: transparent;
        border-left: 3px solid black;
        z-index: 5;
    }

    .candle-top {
        position: absolute;
        top: 31%;
        left: 39%;
        width: 22%;
        height: 2%;
        background: #f3f3f3;
        border-radius: 50%;
        z-index: 4;
    }

    .candle-body {
        position: relative;
        margin: auto;
        top: 32%;
        width: 22%;
        height: 54%;
        background: #e6e6e6;
        z-index: 3;
    }

    .candle-body:after {
        content: "";
        position: absolute;
        left: 50%;
        width: 50%;
        height: 100%;
        background-color: #dadada;
    }

    .outer-tray {
        position: absolute;
        bottom: 12%;
        width: 100%;
        height: 10%;
        background: #fbb615;
        border-radius: 50%;
        z-index: 2;
    }

    .inner-tray {
        position: absolute;
        left: 10%;
        width: 80%;
        height: 80%;
        background: #e6a713;
        border-radius: 50%;
        overflow: hidden;
    }

    .tray-inner-bottom {
        position: absolute;
        top: 75%;
        left: 6%;
        width: 90%;
        height: 90%;
        background: #f3b118;
        border-radius: 50%;
    }

    .outer-tray-base {
        position: absolute;
        bottom: 9%;
        left: 15%;
        width: 56%;
        height: 0;
        border-bottom: 40px solid #e6a713;
        border-left: 25px solid transparent;
        border-right: 25px solid transparent;
        transform: rotate(180deg);
        z-index: 1;
    }

    .bottom-tray-base {
        position: absolute;
        bottom: 6%;
        left: 22.5%;
        width: 56.5%;
        height: 7%;
        border-radius: 50%;
        background: #e6a713;
        z-index: 1;
    }

    .tray-shadow {
        position: absolute;
        bottom: 3%;
        left: 10%;
        width: 80%;
        height: 10%;
        border-radius: 50%;
        background: black;
        opacity: 0.5;
    }

    .candle-glow {
        position: absolute;
        top: -4%;
        width: 100%;
        height: 55%;
        border-radius: 50%;
        background-color: #fffdcd;
        opacity: 0.4;
        animation: candleGlows 3s infinite linear;
    }

    @keyframes candleGlows {
        0% {
            width: 100%;
            height: 55%;
            opacity: 0.4;
        }
        50% {
            width: 101%;
            height: 56%;
            opacity: 0.6;
        }
        100% {
            width: 100%;
            height: 55%;
            opacity: 0.4;
        }
    }
</style>

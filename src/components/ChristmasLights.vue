<template>
    <div class="main">
        <div class="string"></div>
        <div class="light light-1">
            <div class="base"></div>
            <div class="bulb bulb-4"></div>
            <div class="glow glow-4"></div>
        </div>

        <div class="light light-2">
            <div class="base"></div>
            <div class="bulb bulb-5"></div>
            <div class="glow glow-5"></div>
        </div>

        <div class="light light-3">
            <div class="base"></div>
            <div class="bulb bulb-6"></div>
            <div class="glow glow-6"></div>
        </div>

        <div class="light light-4">
            <div class="base"></div>
            <div class="bulb bulb-7"></div>
            <div class="glow glow-7"></div>
        </div>

        <div class="light light-5">
            <div class="base"></div>
            <div class="bulb bulb-3"></div>
            <div class="glow glow-3"></div>
        </div>

        <div class="light light-6">
            <div class="base"></div>
            <div class="bulb bulb-2"></div>
            <div class="glow glow-2"></div>
        </div>

        <div class="light light-7">
            <div class="base"></div>
            <div class="bulb bulb-1"></div>
            <div class="glow glow-1"></div>
        </div>
    </div>
</template>

<style>
    .main {
        position: relative;
        margin: auto;
        display: block;
        margin-top: 5%;
        width: 750px;
        height: 500px;
        background: #dde7f1;
        overflow: hidden;
    }

    .string {
        position: absolute;
        bottom: 62%;
        right: -15%;
        width: 130%;
        height: 100%;
        background: transparent;
        border: 4px solid #424242;
        border-radius: 50%;
    }

    .light {
        position: absolute;
        width: 10%;
        height: 20%;
        background: transparent;
    }

    .light-1 {
        top: 37.4%;
        left: 45%;
    }

    .light-2 {
        top: 36%;
        left: 60%;
        transform: rotate(-6deg);
    }

    .light-3 {
        top: 32%;
        left: 75%;
        transform: rotate(-14deg);
    }

     .light-4 {
        top: 24%;
        left: 90%;
        transform: rotate(-23deg);
    }

    .light-5 {
        top: 36%;
        left: 30%;
        transform: rotate(6deg);
    }

    .light-6 {
        top: 32%;
        left: 15%;
        transform: rotate(14deg);
    }

    .light-7 {
        top: 25%;
        left: 0;
        transform: rotate(23deg);
    }

    .base {
        position: absolute;
        left: 18%;
        width: 65%;
        height: 28%;
        background: #424242;
        border-radius: 5px;
        z-index: 3;
    }

    .bulb {
        position: absolute;
        height: 90%;
        width: 70%;
        left: 15%;
        top: 10%;
        border-radius: 50%;
        z-index: 2;
    }

    .bulb-1 {
        background: #d90300;
        animation: lightUp 3s infinite linear;
    }

    .bulb-2 {
        background: #d8079c;
        animation: lightUp 3s infinite linear;
        animation-delay: 1.5s;
    }

    .bulb-3 {
        background: #135cd1;
        animation: lightUp 3s infinite linear;
    }

    .bulb-4 {
        background: #f3c900;
        animation: lightUp 3s infinite linear;
        animation-delay: 1.5s;
    }

    .bulb-5 {
        background: #068a1e;
        animation: lightUp 3s infinite linear;
    }

    .bulb-6 {
        background: #d90300;
        animation: lightUp 3s infinite linear;
        animation-delay: 1.5s;
    }

    .bulb-7 {
        background: #d8079c;
        animation: lightUp 3s infinite linear;
    }

    @keyframes lightUp {
        0% {
            opacity: .2;
        }
        49% {
            opacity: .2;
        }
        50% {
            opacity: 1;
        }
        100% {
            opacity: 1;
        }
    }

    .glow {
        position: absolute;
        height: 25%;
        width: 35%;
        border-radius: 50%;
        opacity: .5;
    }

    .glow-1 {
        top: 60%;
        left: 34%;
        background: #d90300;
        box-shadow: 0 0 50px 50px #d90300;
        animation: glow 3s infinite linear;
    }

    .glow-2 {
        top: 60%;
        left: 34%;
        background: #d8079c;
        box-shadow: 0 0 50px 50px #d8079c;
        animation: glow 3s infinite linear;
        animation-delay: 1.5s;
    }

    .glow-3 {
        top: 60%;
        left: 34%;
        background: #135cd1;
        box-shadow: 0 0 50px 50px #135cd1;
        animation: glow 3s infinite linear;
    }

    .glow-4 {
        top: 60%;
        left: 34%;
        background: #f3c900;
        box-shadow: 0 0 50px 50px #f3c900;
        animation: glow 3s infinite linear;
        animation-delay: 1.5s;
    }

     .glow-5 {
        top: 60%;
        left: 34%;
        background: #068a1e;
        box-shadow: 0 0 50px 50px #068a1e;
        animation: glow 3s infinite linear;
    }

    .glow-6 {
        top: 60%;
        left: 34%;
        background: #d90300;
        box-shadow: 0 0 50px 50px #d90300;
        animation: glow 3s infinite linear;
        animation-delay: 1.5s;
    }

    .glow-7 {
        top: 60%;
        left: 34%;
        background: #d8079c;
        box-shadow: 0 0 50px 50px #d8079c;
        animation: glow 3s infinite linear;
    }

    @keyframes glow {
        0% {
            opacity: 0;
        }
        49% {
            opacity: 0;
        }
        50% {
            opacity: .5;
        }
        100% {
            opacity: .5;
        }
    }
</style>

<template>
    <div class="box">
        <div class="head">  
            <div class="head-copy"></div>

            <div class="ear-left">
                <div class="inner-ear rotate-left"></div>
            </div>

            <div class="ear-right">
                <div class="inner-ear rotate-right"></div>
            </div>

            <div class="eye-left">
                <div class="pupil"></div>
            </div>

            <div class="eye-right">
                <div class="pupil"></div>
            </div>

            <div class="nose"></div>

            <div class="whisker-top-left"></div>
            <div class="whisker-mid-left"></div>
            <div class="whisker-bottom-left"></div>

            <div class="whisker-top-right"></div>
            <div class="whisker-mid-right"></div>
            <div class="whisker-bottom-right"></div>

            <div class="mouth"></div>
        </div>
    </div>
</template>

<style>
    body {
        background-color: #25A9FC;
    }

    .box {
        position: relative;
        margin: auto;
        display: block;
        margin-top: 8%;
        width: 600px;
        height: 420px;
        background: #fff295;
        border-radius: 10%;
    }

    .head {
        position: absolute;
        top: 23.5%;
        left: 25%;
        width: 50%;
        height: 67%;
        background: black;
        border-radius: 50%;
    }

    .head-copy {
        width: 100%;
        height: 100%;
        position: absolute;
        background: black;
        border-radius: 50%;
        z-index: 2;
    }

    .ear-left {
        position: absolute;
        width: 60%;
        height: 65%;
        left: -7%;
        top: -30%;
        background: black;
        -webkit-clip-path: polygon(31% 13%, 25% 97%, 100% 64%);
        clip-path: polygon(31% 13%, 25% 97%, 100% 64%);
        z-index: 1;
    }

     .ear-right {
        position: absolute;
        width: 60%;
        height: 65%;
        right: 2%;
        top: -31%;
        background: black;
        -webkit-clip-path: polygon(75% 15%, 0 66%, 85% 99%);
        clip-path: polygon(75% 15%, 0 66%, 85% 99%);
        z-index: 1;
    }

    .inner-ear{
        position: absolute;
        border-radius: 50%;
        width: 32%;
        height: 50%;
        top: 38%;
        left: 38%;
        background: #616161;
    }

    .rotate-left {
        transform: rotate(-25deg);
    }

    .rotate-right {
        transform: rotate(25deg);
    }

    .eye-left {
        position: absolute;
        background: white;
        width: 30%;
        height: 33%;
        top: 25%;
        left: 21%;
        border-radius: 50%;
        z-index: 3;
    }

    .eye-right {
        position: absolute;
        background: white;
        width: 30%;
        height: 33%;
        top: 25%;
        right: 21%;
        border-radius: 50%;
        z-index: 2;
    }

    .pupil{
        position: absolute;
        width: 28%;
        height: 30%;
        top: 35%;
        left: 36%;
        border-radius: 50%;
        background: #27354A;
    }

    .nose {
        position: absolute;
        top: 60%;
        left: 39%;
        width: 23%;
        height: 31.5%;
        background: #616161;
        -webkit-clip-path: polygon(50% 43%, 0 0, 100% 0);
        clip-path: polygon(50% 43%, 0 0, 100% 0);
        z-index: 4;
    }

    .whisker-top-left {
        position: absolute;
        width: 33%;
        top: 57%;
        left: 5%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(19deg);
        z-index: 3;
    }

    .whisker-mid-left {
        position: absolute;
        width: 33%;
        top: 68%;
        left: 3%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(0deg);
        z-index: 3;
    }

     .whisker-bottom-left {
        position: absolute;
        width: 33%;
        top: 79%;
        left: 5%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(-19deg);
        z-index: 3;
    }

    .whisker-top-right {
        position: absolute;
        width: 33%;
        top: 57%;
        right: 5%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(-19deg);
        z-index: 3;
    }

    .whisker-mid-right {
        position: absolute;
        width: 33%;
        top: 68%;
        right: 3%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(0deg);
        z-index: 3;
    }

     .whisker-bottom-right {
        position: absolute;
        width: 33%;
        top: 79%;
        right: 5%;
        border-top: 3px solid #c5c5c5;
        transform: rotate(19deg);
        z-index: 3;
    }

    .mouth {
        position: absolute;
        top: 68%;
        left: 42.5%;
        width: 16%;
        height: 19.5%;
        background: #1f1f1f;
        -webkit-clip-path: polygon(50% 43%, 0 0, 100% 0);
        clip-path: polygon(50% 43%, 0 0, 100% 0);
        transform: rotate(180deg);
        z-index: 4;
    }

</style>

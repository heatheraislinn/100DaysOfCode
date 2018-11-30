<template>
    <div class="background">
        <div class="christmas-tree">
            <div class="tree-top">
                <div class="top-left-side"></div>
                <div class="top-right-side"></div>
            </div>
            <div class="top-bottom">
                <div class="top-branches"></div>
            </div>

            <div class="tree-middle-top">
                <div class="top-middle-left-side"></div>
                <div class="top-middle-right-side"></div>
            </div>
            <div class="top-middle-bottom">
                <div class="top-middle-branches"></div>
            </div>

            <div class="tree-middle-bottom">
                <div class="middle-bottom-left-side"></div>
                <div class="middle-bottom-right-side"></div>
            </div>
            <div class="middle-bottom-bottom">
                <div class="middle-bottom-branches"></div>
            </div>

            <div class="tree-bottom">
                <div class="top-middle-left-side"></div>
                <div class="top-middle-right-side"></div>
            </div>
             <div class="bottom-bottom">
                <div class="top-middle-branches"></div>
            </div>

            <div class="tree-base"></div>
        </div>

        <div class="snow">
            <div class="snowball-1"></div>
            <div class="snowball-2"></div>
            <div class="snowball-3"></div>
            <div class="snowball-4"></div>
            <div class="snowball-5"></div>
            <div class="snowball-6"></div>
            <div class="snowball-7"></div>
            <div class="snowball-8"></div>
            <div class="snowball-9"></div>
            <div class="snowball-10"></div>
            <div class="snowball-11"></div>
            <div class="snowball-12"></div>
            <div class="snowball-13"></div>
            <div class="snowball-14"></div>
            <div class="snowball-15"></div>
            <div class="snowball-16"></div>
            <div class="snowball-17"></div>
        </div>
    </div>
</template>

<style scoped>
    .background {
        position: relative;
        margin: auto;
        display: block;
        width: 600px;
        height: 650px;
        background: #88b6d6;
        border: 4px solid gray;
        overflow: hidden;
    }

     .background:after {
        content: "";
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        width: 100%;
        height: 155px;
        background-color: white;
    }

    .christmas-tree {
        position: relative;
        margin: auto;
        top: 5%;
        width: 60%;
        height: 90%;
    }

    .tree-top {
        position: relative;
        margin: auto;
        width: 35%;
        height: 20%;
        background: green;
        z-index: 5;
    }

    .top-left-side {
        position: absolute;
        right: 56%;
        width: 70%;
        height: 130%;
        bottom: -6%;
        border-radius: 50%;
        transform: rotate(20deg);
        border-top-right-radius: 40%;
        background: #88b6d6;
    }

    .top-right-side {
        position: absolute;
        left: 56%;
        width: 70%;
        height: 130%;
        bottom: -6%;
        border-radius: 50%;
        transform: rotate(-20deg);
        border-top-left-radius: 40%;
        background: #88b6d6;
    }

    .top-bottom {
        position: relative;
        margin: auto;
        width: 29%;
        height: 15%;
        overflow: hidden;
        transform: rotate(180deg);
        z-index: 5;
    }

    .top-branches {
        position: absolute;
        margin: auto;
        top: 69%;
        width: 100%;
        height: 80%;
        border-radius: 50%;
        background: green;
    }

    .tree-middle-top {
        position: relative;
        margin: auto;
        top: -21%;
        width: 55%;
        height: 20%;
        background: green;
        overflow: hidden;
        z-index: 4;
    }

    .top-middle-left-side {
        position: absolute;
        right: 61%;
        width: 50%;
        height: 150%;
        bottom: -6%;
        border-radius: 50%;
        transform: rotate(33deg);
        border-top-right-radius: 40%;
        background: #88b6d6;
    }

    .top-middle-right-side {
        position: absolute;
        left: 61%;
        width: 50%;
        height: 150%;
        bottom: -6%;
        border-radius: 50%;
        transform: rotate(-33deg);
        border-top-left-radius: 40%;
        background: #88b6d6;
    }

    .top-middle-bottom {
        position: relative;
        margin: auto;
        top: -21%;
        width: 56%;
        height: 23%;
        overflow: hidden;
        transform: rotate(180deg);
        z-index: 4;
    }

    .top-middle-branches {
        position: absolute;
        margin: auto;
        top: 69%;
        width: 100%;
        height: 80%;
        border-radius: 50%;
        background: green;
    }

    .tree-middle-bottom {
        position: relative;
        margin: auto;
        top: -46%;
        width: 75%;
        height: 20%;
        background: green;
        overflow: hidden;
        z-index: 3;
    }

    .middle-bottom-left-side {
        position: absolute;
        right: 65%;
        width: 60%;
        height: 180%;
        bottom: -8%;
        border-radius: 50%;
        transform: rotate(44deg);
        border-top-right-radius: 40%;
        background: #88b6d6;
    }

    .middle-bottom-right-side {
        position: absolute;
        left: 65%;
        width: 60%;
        height: 180%;
        bottom: -8%;
        border-radius: 50%;
        transform: rotate(-44deg);
        border-top-left-radius: 40%;
        background: #88b6d6;
    }

    .middle-bottom-bottom {
        position: relative;
        margin: auto;
        top: -46%;
        width: 77%;
        height: 30%;
        overflow: hidden;
        transform: rotate(180deg);
        z-index: 3;
    }

    .middle-bottom-branches {
        position: absolute;
        margin: auto;
        top: 69%;
        width: 100%;
        height: 80%;
        border-radius: 50%;
        background: green;
    }

    .tree-bottom {
        position: relative;
        margin: auto;
        top: -83%;
        width: 55%;
        height: 20%;
        background: green;
        overflow: hidden;
        z-index: 2;
    }

    .bottom-bottom {
        position: relative;
        margin: auto;
        top: -83%;
        width: 56%;
        height: 23%;
        overflow: hidden;
        transform: rotate(180deg);
        z-index: 2;
    }

    .tree-base {
        position: relative;
        margin: auto;
        width: 10%;
        height: 20%;
        top: -110%;
        background: brown;
        z-index: 1;
    }

    .snow {
        position: relative;
        width: 100%;
        height: 10%;
        bottom: 15%;
        z-index: 2;
    }

    .snowball-1 {
        position: absolute;
        width: 10%;
        height: 80%;
        left: -2%;
        border-radius: 50%;
        background: white;
    }

    .snowball-2 {
        position: absolute;
        width: 7%;
        height: 80%;
        left: 5%;
        border-radius: 50%;
        background: white;
    }

    .snowball-3 {
        position: absolute;
        width: 8%;
        height: 80%;
        left: 9%;
        top: -8%;
        border-radius: 50%;
        background: white;
    }

    .snowball-4 {
        position: absolute;
        width: 12%;
        height: 80%;
        left: 14%;
        top: 2%;
        border-radius: 50%;
        background: white;
    }

    .snowball-5 {
        position: absolute;
        width: 10%;
        height: 80%;
        left: 21%;
        border-radius: 50%;
        background: white;
    }

    .snowball-6 {
        position: absolute;
        width: 7%;
        height: 80%;
        left: 28%;
        border-radius: 50%;
        background: white;
    }

    .snowball-7 {
        position: absolute;
        width: 8%;
        height: 80%;
        left: 33%;
        top: -8%;
        border-radius: 50%;
        background: white;
    }

    .snowball-8 {
        position: absolute;
        width: 12%;
        height: 80%;
        left: 38%;
        top: 2%;
        border-radius: 50%;
        background: white;
    }

    .snowball-9 {
        position: absolute;
        width: 10%;
        height: 80%;
        left: 45%;
        border-radius: 50%;
        background: white;
    }

    .snowball-10 {
        position: absolute;
        width: 7%;
        height: 80%;
        left: 50%;
        border-radius: 50%;
        background: white;
    }

    .snowball-11 {
        position: absolute;
        width: 8%;
        height: 80%;
        left: 55%;
        top: -8%;
        border-radius: 50%;
        background: white;
    }

    .snowball-12 {
        position: absolute;
        width: 12%;
        height: 80%;
        left: 61%;
        top: 2%;
        border-radius: 50%;
        background: white;
    }

     .snowball-13 {
        position: absolute;
        width: 10%;
        height: 80%;
        left: 68%;
        border-radius: 50%;
        background: white;
    }

    .snowball-14 {
        position: absolute;
        width: 7%;
        height: 80%;
        left: 75%;
        border-radius: 50%;
        background: white;
    }

    .snowball-15 {
        position: absolute;
        width: 8%;
        height: 80%;
        left: 80%;
        top: -8%;
        border-radius: 50%;
        background: white;
    }

    .snowball-16 {
        position: absolute;
        width: 12%;
        height: 80%;
        left: 85%;
        top: 2%;
        border-radius: 50%;
        background: white;
    }

    .snowball-17 {
        position: absolute;
        width: 12%;
        height: 80%;
        left: 92%;
        top: 6%;
        border-radius: 50%;
        background: white;
    }
</style>

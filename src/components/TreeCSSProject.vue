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
    </div>
</template>

<style scoped>
    .background {
        position: relative;
        margin: auto;
        display: block;
        width: 600px;
        height: 750px;
        background: lightblue;
        border: 4px solid gray;
    }

    .christmas-tree {
        position: relative;
        margin: auto;
        top: 10%;
        width: 60%;
        height: 80%;
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
        background: lightblue;
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
        background: lightblue;
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
        background: lightblue;
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
        background: lightblue;
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
        background: lightblue;
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
        background: lightblue;
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
</style>

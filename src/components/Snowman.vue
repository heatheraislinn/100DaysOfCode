<template>
    <div class="main">
        <div class="sun"></div>
        <div class="snowman">
            <div class="top-hat">
                <div class="round-top"></div>
                <div class="hat-body-top"></div>
                <div class="hat-body-bottom">
                    <div class="rounded-bottom"></div>
                </div>
                <div class="brim"></div>
            </div>

            <div class="snowman-head"></div>
        </div>

        

    </div>
</template>

<style>
    .main {
        position: relative;
        display: block;
        margin: auto;
        width: 600px;
        height: 750px;
        background: radial-gradient(transparent 75%, #05426f 100%),
                    linear-gradient(135deg, #91a5a6, #8a9b8b, #8dabab, #889a80, #6d969c, #477e92, #518998);               
    }

    .sun {
        position: absolute;
        height: 14%;
        width: 18%;
        top: 20%;
        right: 15%;
        background: radial-gradient(#ecc56b, #e4ddb7);
        box-shadow: 0 0 60px 20px #e4ddb7;
        border-radius: 50%;
    }

    .snowman {
        position: absolute;
        height: 80%;
        width: 70%;
        top: 15%;
        left: 15%;
    }

    .top-hat {
        position: absolute;
        height: 30%;
        width: 30%;
        left: 36%;
    }

    .round-top {
        position: absolute;
        width: 60%;
        height: 10%;
        left: 20%;
        top: 5%;
        border-radius: 50%;
        background: radial-gradient(ellipse at top left, #9b9d8f, #667177, black);
        z-index: 4;
    }

    .hat-body-top {
        position: absolute;
        height: 38%;
        width: 60%;
        left: 20%;
        top: 10%;
        background: linear-gradient(to right, #364e4e, #3a494e, #32454c, #59646a, #7d848a, #919284, #6e7d7a);
        border-bottom: 3px solid black;
        border-bottom-left-radius: 20%;
        border-bottom-right-radius: 20%;
        z-index: 3;
    }

    .hat-body-bottom {
        position: absolute;
        width: 60%;
        height: 33%;
        left: 20%;
        top: 36%;
        background: linear-gradient(to right, #630408, #500106, #2f0304, #820f14, #9e1723, #af2228, #992d3a);
        z-index: 2;
    }

    .rounded-bottom {
        position: absolute;
        width: 100%;
        height: 30%;
        top: 90%;
        background: linear-gradient(to right, #630408, #500106, #2f0304, #820f14, #9e1723, #af2228, #992d3a);
        border-bottom: 3px solid black;
        border-bottom-left-radius: 50%;
        border-bottom-right-radius: 50%;
        z-index: 2;
    }

    .brim {
        position: absolute;
        width: 110%;
        height: 24%;
        top: 68%;
        left: -5%;
        background: radial-gradient(ellipse at top left, #6f6e76, #918593, #889395, #6c7981, #3e5054, #3f333d, #707068);
        border-radius: 50%;
        z-index: 1;
    }

    .snowman-head {
        position: absolute;
        width: 33%;
        height: 21%;
        left: 34%;
        top: 22%;
        border-radius: 50%;
        border-left: 3px solid #b9b4a5;
        border-right: 3px solid #d4d4d4;
        background: radial-gradient(ellipse at top left, #96afa8, #7d9798, #8babba, #a9b5c3, #c6c7c9, #c6c7c9, #c0cccc);
    }
</style>

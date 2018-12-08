<template>
    <div class="wall">
        <div class="window">
            <div class="left-top-pane"></div>
            <div class="left-bottom-pane"></div>
            <div class="transom-vert"></div>
            <div class="transom-horiz"></div>
            <div class="right-top-pane"></div>
            <div class="right-bottom-pane"></div>
            <div class="snow"></div>
        </div>

        <div class="pane-top"></div>
        <div class="pane-front"></div>
        <div class="pane-shadow"></div>
    </div>
</template>

<style>
    .wall {
        position: relative;
        margin: auto;
        display: block;
        width: 700px;
        height: 750px;
        background: #4c3535;
    }

    .window {
        position: absolute;
        width: 54%;
        height: 67%;
        left: 20%;
        top: 7%;
        background: #014e85;
        border: 30px solid #7b7b7b;
    }

    .left-top-pane {
        position: absolute;
        height: 50%;
        width: 44%;
        border-left: 10px solid #a7a7a7;
        border-bottom: 6px solid #a7a7a7;
        background: transparent;
        z-index: 5;
    }

    .left-bottom-pane {
        position: absolute;
        height: 45%;
        width: 44%;
        top: 55%;
        border-left: 10px solid #a7a7a7;
        border-bottom: 6px solid #a7a7a7;
        background: transparent;
        z-index: 5;
    }

    .transom-vert {
        position: absolute;
        height: 100%;
        width: 10%;
        left: 47%;
        background: #7b7b7b;
        z-index: 2;
    }

    .transom-horiz {
        position: absolute;
        top: 50%;
        height: 5%;
        width: 100%;
        background: #7b7b7b;
        z-index: 4;
    }

    .right-top-pane {
        position: absolute;
        height: 50%;
        width: 43%;
        left: 55%;
        border-left: 8px solid #a7a7a7;
        border-bottom: 6px solid #a7a7a7;
        background: transparent;
        z-index: 5;
    }

    .right-bottom-pane {
        position: absolute;
        height: 45%;
        width: 43%;
        left: 55%;
        top: 55%;
        border-left: 8px solid #a7a7a7;
        border-bottom: 6px solid #a7a7a7;
        background: transparent;
        z-index: 5;
    }

    .snow {
        position: absolute;
        height: 100%;
        width: 100%;
        z-index: 1;
        background-image:
            url(https://i.imgur.com/uYjnk8N.png), 
            url(https://i.imgur.com/iAGD6MA.png), 
            url(https://i.imgur.com/hIJDjbg.png);
        animation: snow 30s linear infinite;
    }

    @keyframes snow {
        0% {
            background-position: 0px 0px, 0px 0px, 0px 0px;
        }
        100% {
            background-position: 500px 1000px, 400px 400px, 300px 300px
        }
    }

    .pane-top {
        position: absolute;
        bottom: 16%;
        left: 14%;
        width: 62%;
        height: 0;
        border-bottom: 15px solid #a7a7a7;
        border-left: 45px solid transparent;
        border-right: 45px solid transparent;
    }

    .pane-front {
        position: absolute;
        width: 75%;
        height: 6%;
        left: 14%;
        bottom: 10%;
        background: #7b7b7b;
        z-index: 2;
    }

    .pane-shadow {
        position: absolute;
        width: 71%;
        height: 8%;
        left: 16%;
        bottom: 8%;
        background: black;
        opacity: 0.2;
    }

</style>

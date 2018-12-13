<template>
    <div class="start wide" id="its-a-pencil">
        <div></div>
    </div>
</template>

<style>
    #its-a-pencil {
        background: #cccccc;
    }

    .start {
        text-align: center;
        min-height: 400px;
        position: relative;
    }

    .start .wide {
        width: 100%;
    }

    .start div {
        position: absolute;
        left: 30%;
        top: 40%;
    }

    #its-a-pencil div {
        width: 470px;
        height: 40px;
        background: #ffda55;
        border-top-right-radius: 4px;
        border-bottom-right-radius: 4px;
        box-shadow: 2px 2px 3px rgba(0, 0, 0, .3);
                            /* Pencil Body */
        background-image:   linear-gradient(to bottom,
                                transparent 62%,
                                rgba(0, 0, 0, .3) 100%),

                            /* Eraser */
                            linear-gradient(to right,
                                transparent 440px,
                                #e692cc 12px,
                                #e692cc 470px,
                                transparent 235px),

                            /* Metal Holder */
                            linear-gradient(to right,
                                transparent 395px,
                                rgba(191, 191, 191) 395px,
                                rgba(119, 119, 119) 410px,
                                rgba(191, 191, 191) 410px,
                                rgba(119, 119, 119) 425px,
                                rgba(191, 191, 191) 425px,
                                rgba(119, 119, 119) 440px,
                                transparent 440px);                             
    }

    #its-a-pencil div:before {
        content: "";
        position: absolute;
        height: 14px;
        left: -10%;
        top: -1%;
        border-right: 48px solid #f5dfad;
        border-bottom: 13px solid transparent;
        border-top: 13px solid transparent;
    }

    #its-a-pencil div:after {
        content: "";
        position: absolute;
        left: 0;
        top: 0;
        height: 100%;
        width: 100%;
        background-image: linear-gradient(to bottom,
                            rgba(255, 255, 255, 0) 12px,
                            rgba(255, 255, 255, .2) 17px,
                            rgba(255, 255, 255, .2) 21px,
                            rgba(255, 255, 255, 0) 35px);
    }

</style>

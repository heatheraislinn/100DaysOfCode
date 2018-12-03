<template>
    <div id="main">
        <div class="page-container">
            <div id="img-div">
                <img id="image" src="https://draxe.com/wp-content/uploads/2017/06/Chai-Tea-Final-2-e1498142140504.jpg" alt="A hot chai tea latte sprinkled with cinnamon.">
                <div id="img-caption">sweet. delicious. comforting.</div>
            </div>
            <div class="subtitle">a tribute to</div>
            <h1 id="title">The Chai Latte</h1>

            <div id="tribute-info">
                <div class="did-you-know">Did You Know</div>
                <div class="fact-grid">
                    <div class="fact">Masala chai is black tea brewed with cardamom, cinnamon, cloves, ginger, and black peppercorns</div>
                    <div class="fact">Chai originated in India where the word itself simply means "tea"</div>
                    <div class="fact">The chai latte gained popularity in the US during the 1990s when coffehouses began mixing it with steamed milk and sweeteners</div>
                    <div class="fact">A typical cup of chai tea prepared as directed contains approximately 40mg of caffeine compared to roughly 120mg in an average cup of coffee</div>
                    <div class="fact">The London Fog is a play on the chai latte, made with Earl Grey tea, milk, and vanilla syrup</div>
                    <div class="fact">Tea is much more environmentally friendly than coffee, using much less water to produce</div>
                </div>
            </div>

            <div class="link">Want to get a taste of chai tea or the chai latte? <a id="tribute-link" href="https://livesimply.me/2014/10/06/homemade-chai-tea-latte/" target="_blank">Try it</a> for yourself!</div> 
        </div>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css?family=Satisfy');
    @import url('https://fonts.googleapis.com/css?family=Cutive+Mono');

    html, body {
        text-align: center;
        font-family: Helvetica, Arial, sans-serif;
    }

    #main {
        position: relative;
        padding: 15px;
    }

    #main:after {
        content : "";
        display: block;
        position: absolute;
        top: 0;
        left: 0;
        background-image: url('https://images.freecreatives.com/wp-content/uploads/2015/05/4.jpg'); 
        width: 100%;
        height: 100%;
        opacity : 0.2;
        z-index: -1;
    }

    .page-container {
        max-width: 800px;
        margin: 0 auto;
    }

    img {
        max-width: 100%;
        display: block;
        height: auto;
        margin: auto;
        border: 10px solid #f2d7d7;
        border-radius: 50%;
    }

    #img-caption {
        font-family: 'Cutive Mono', monospace;
        margin-top: 40px;
    }

    h1 {
        font-family: 'Satisfy', cursive;
        font-size: 3em;
        margin: 0;
    }

    .subtitle {
        font-family: 'Cutive Mono', monospace;
        margin-bottom: 10px;
    }

    .did-you-know {
        background: white;
        text-transform: uppercase;
        padding: 10px;
        font-size: 1.3em;
        color: #484848;
        text-align: left;
        margin-top: 10px;
    }

    .fact-grid {
        margin-top: 10px;
        display: grid;
        grid-template-columns: 260px 260px 260px;
        grid-template-rows: 160px 160px;
        grid-gap: 10px;
    }

    .fact {
        background: #deebf5;
        border: 5px solid #b4daf3;
        padding: 15px;
        font-weight: bold;
        color: #484848;
    }

    .link {
        margin-top: 15px;
        margin-bottom: 20px;
        background: #f2d7d7;
        padding: 10px;
        border-radius: 40px;
        color: #484848;
    }

    a {
        color: #526651;
        text-decoration: none;
    }

    a:hover {
        color: white;
    }


</style>

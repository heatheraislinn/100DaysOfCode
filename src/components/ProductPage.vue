<template>
    <div id="page-wrapper">
        <header id="header">
            <div class="logo">
              <img id="header-img" src="http://inddc.in/webroot/assets/img/sample/shortcode/logo/1.png" alt="original trombones logo" />
            </div>

            <nav id="nav-bar">
                <ul>
                    <li><a class="nav-link" href="#features">Features</a></li>
                    <li><a class="nav-link" href="#how-it-works">How It Works</a></li>
                    <li><a class="nav-link" href="#pricing">Pricing</a></li>
                </ul>
            </nav>
        </header>

        <div class="container">
            <section id="hero">
                <h1>Iced Tea & Sunshine</h1>
                <h3>beautiful, inspirational, hand-crafted art</h3>
                <div class="sample-posters">
                    <img id="hero-image" src="https://i.etsystatic.com/9619353/r/il/3e0d9a/623811557/il_570xN.623811557_oj67.jpg" />
                    <img id="hero-image" src="https://i.etsystatic.com/9619353/r/il/6077fd/679235425/il_570xN.679235425_bmef.jpg" />
                    <img id="hero-image" src="https://i.etsystatic.com/9619353/r/il/e3ad9f/679142396/il_570xN.679142396_miwz.jpg" />
                </div>
            </section>

            <section id="features">
                <div class="our-features">What Will I Get?</div>
                <div class="features-grid">
                    <div class="icon">
                        <i class="fas fa-3x fa-image"></i>
                    </div>
                    <div class="desc">
                        <h2>High Quality Prints</h2>
                        <p>All of our posters are high-resolution images with bright colors and crisp lines. And, since they're created at 300dpi resolution, you can resize them any way you want. </p>
                    </div>
        
                    <div class="icon">
                        <i class="fas fa-3x fa-shipping-fast"></i>
                    </div>
                    <div class="desc">
                        <h2>Fast Shipping</h2>
                        <p>The posters are digital, meaning you send us money, we send you the poster. Shipping is basically instant, and the only thing that could hold you up how you're going to print it.</p>
                    </div>

                    <div class="icon">
                        <i class="far fa-3x fa-smile"></i>
                    </div>
                    <div class="desc">
                        <h2>Satisfaction Guaranteed</h2>
                        <p>These posters are inspirational. They're full of feel-good quotes. If they don't make you happy when you look at them, that's more on you than on us.</p>
                    </div>
                </div>
            </section>

            <section id="how-it-works">
                <div class="our-features">What Comes Next?</div>
                <div class="our-video">
                    <p>Buy our posters and you can feel as inspired as you do watching this video!</p>
                    <iframe id="video" width="560" height="315" src="https://www.youtube.com/embed/vte70xSXGL8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </section>

            <div class="our-features">Pricing</div>
            <section id="pricing">
                <div id="basic">
                    <div class="level">Basic</div>
                    <h2>$100</h2>
                    <ol>
                        <li>1 Poster</li>
                        <li>A little inspiration</li>
                        <li>Decorate a room</li>
                        <li>Make yourself smile</li>
                    </ol>
                    <button class="btn">Select</button>
                </div>

                <div id="inspired">
                    <div class="level">Inspired</div>
                    <h2>$400</h2>
                    <ol>
                        <li>5 Posters</li>
                        <li>A good bit of inspiration</li>
                        <li>Decorate a home</li>
                        <li>Brighten up your life</li>
                    </ol>
                    <button class="btn">Select</button>
                </div>

                <div id="invigorated">
                    <div class="level">Invigorated</div>
                    <h2>$750</h2>
                    <ol>
                        <li>10 Posters</li>
                        <li>Tons of inspiration</li>
                        <li>Christmas gifts</li>
                        <li>Share the positivity</li>
                    </ol>
                    <button class="btn">Select</button>
                </div>
            </section>
        </div>

        <footer>
            <h2 class="footer-question">Have questions or an idea for an inspirational poster?</h2>
            <p class="footer-let-us-know">We'd love to reach out to you!</p>
            <form id="form" action="https://www.freecodecamp.com/email-submit">
                <input name="email" id="email" type="email" placeholder="Enter your email address" required/>
                <div>
                    <input id="submit" type="submit" value="Send" class="btn"></input>
                </div>
            </form>
        </footer>

    </div>
</template>

<style>
    /** global element styling **/
* {
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Helvetica', Arial, sans-serif;
}

li {
    list-style: none;
}

a {
    color: #fff;
    text-decoration: none;
}

/* global classes styling */

.container {
    max-width: 1000px;
    width: 100%;
    margin: 0 auto;
    padding-top: 100px;
}

.btn {
    padding: 0 20px;
    height: 40px;
    font-size: 1em;
    font-weight: 900;
    text-transform: uppercase;
    border: 3px black solid;
    border-radius: 2px;
    background: transparent;
    cursor: pointer;
}

.grid {
    display: flex;
}

/* navigation bar */

header {
    position: fixed;
    top: 0;
    width: 100%;
    padding: 0px 10px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #027bba;
}



.logo {
    width: 70%;
}

#header-img {
    width: 15%;
}

.nav-link {
  color: white;
}

/* hero */

#hero {
  display: flex;
  flex-direction: column;
  align-items: center;
}

h1 {
    font-size: 2.5em;
}

h3 {
    font-weight: lighter;
}

.sample-posters {
    display: grid;
    grid-template-columns: 250px 250px 250px;
    grid-gap: 15px;
    margin-top: 40px;
}

#hero-image {
    width: 100%;
}

h2 {
    margin-bottom: 20px;
    word-wrap: break-word;
}

/* features */

#features {
    margin-top: 50px;
}

.our-features {
    background: #f26262;
    color: white;
    font-weight: bold;
    padding: 10px;
    border-radius: 40px;
    text-align: center;
    text-transform: uppercase;
}

.features-grid {
    display: grid;
    grid-template-columns: 150px 700px;
    grid-template-rows: 150px 150px 150px;
    margin-left: 50px;
}

.icon {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 125px;
    color: #6e6e6e;
}

.desc {
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: 125px;
    padding: 5px;
}

/* how it works */

#how-it-works {
  margin-top: 25px;
  margin-bottom: 50px;
}

.our-video {
    display: grid;
    grid-template-columns: 300px 600px;
    grid-gap: 10px;
    margin-left: 60px;
    margin-top: 30px;
}
  
iframe {
    max-width: 560px;
    width: 100%;
}

/* pricing */

#pricing {
  margin-top: 20px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
  
#basic, #inspired, #invigorated {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    width: calc(100%  / 3);
    margin: 10px;
    border: 1px solid #000;
    border-radius: 3px;
}
    
.level {
    background-color: #0286c2;
    color: white;
    padding: 15px 0;
    width: 100%;
    text-transform: uppercase;
    font-weight: 700;
}
    
h2 {
    margin-top: 15px;
}
    
ol {
    margin: 15px 0;
}
      
li { 
    padding: 5px 0;
}
    
button {
    border: 0;
    margin: 15px 0;
    background-color: #f1c40f;
    font-weight: 400;
}

/* Footer */

footer {
  margin-top: 30px;
  background-color: #545454;
  padding: 20px;
  text-align: center;
}

.footer-question {
    color: white;
    text-align: center;
    font-weight: 500;
    margin-bottom: 0;
}

.footer-let-us-know {
    color: white;
    text-align: center;
    font-size: 1.3em;
    margin-bottom: 20px;
}

input[type="email"] {
    max-width: 275px;
    width: 100%;
    padding: 10px;
    border-radius: 4px;
    border: none;

}

input[type="submit"] {
    height: 30px;
    margin: 15px 0;    
    border: 0;
    background-color: #f46d6e;
    text-align: center;
    color: white;

}

/* Other styles */
  
ul {
    display: flex;
    justify-content: flex-end;
}
    
li {
    padding: 0 10px;
}
  
span {
    margin-top: 5px;
    display: flex;
    justify-content: flex-end;
    font-size: 0.9em;
    color: #444;
}

@media screen and (max-width: 650px) {
    #header-img {
        width: 25%;
    }

    ul {
        justify-content: flex-start;
    }

    .sample-posters {
        grid-template-columns: 250px;
        grid-template-rows: 305px 305px 305px;
    }

    .features-grid {
        margin-left: 0;
        grid-template-columns: 150px 400px;
    }

    .our-video {
        grid-template-columns: 400px;
        grid-template-rows: 50px 300px;
    }
}

@media screen and (max-width: 500px) {
    #header-img {
        width: 35%;
    }

    ul {
        justify-content: flex-start;
    }

    .sample-posters {
        grid-template-columns: 250px;
        grid-template-rows: 305px 305px 305px;
    }

    .features-grid {
        margin-left: 0;
        grid-template-columns: 150px 330px;
    }

    .our-video {
        grid-template-columns: 400px;
        grid-template-rows: 50px 300px;
    }
}
</style>

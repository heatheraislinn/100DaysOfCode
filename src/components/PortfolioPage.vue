<template>
    <div>
        <nav>
            <ul id="navbar">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

        <header id="welcome-section" class="intro">
            <h1>Hi, I'm Heather.</h1>
        </header>

        <section id="about" class="about">
            <div class="about-pics">
                <img src="https://mantisnseamore.files.wordpress.com/2012/03/greatoutdoors.jpg" class="each-pic" />
                <img src="https://img.aws.livestrongcdn.com/ls-article-image-673/ds-photo/getty/article/144/128/177523849.jpg" class="each-pic" />
                <img src="https://admissions.msu.edu/img/degree-detail/degreedetail1/CALstudioartbfa.jpg" class="each-pic" />
                <img src="https://pbs.twimg.com/profile_images/975427879222693888/57tW8Uvn_400x400.jpg" class="my-pic" />
                <img src="https://css-tricks.com/wp-content/uploads/2018/05/css-art.jpg" class="each-pic" />
                <img src="https://vuejs.org/images/logo.png" style="height: 100px;" />
                <img src="https://upload.wikimedia.org/wikipedia/en/thumb/0/00/Boston_College_seal.svg/1200px-Boston_College_seal.svg.png" class="each-pic" />
            </div>
            <p class="about-description">
                I'm an outdoor-preferring, Earl Grey tea-drinking, studio art degree-having, CSS animation and design-loving, Vue and JavaScript-learning, History PhD -
            </p>
            <p class="frontend"> Turning Frontend Developer.</p>
        </section>

        <section id="projects">
            <h2 class="projects-header">Check out what I've worked on</h2>
            <div class="project-tile">

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687690-997e4480-fad4-11e8-9747-4a7d1a7c2383.png" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/mQgPMz" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687697-b0249b80-fad4-11e8-93d7-41fa3123ba86.png" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/rQEMoP" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687812-8ec4af00-fad6-11e8-8793-046bd3a5ad47.png" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/rQXZpd" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://adlantern.app/assets/images/Site-Demo.gif" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://adlantern.app/" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687687-91bea000-fad4-11e8-809b-595d15e6008f.gif" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/BGbgMR" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687682-7fdcfd00-fad4-11e8-8c96-6220386c8f19.gif" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/OareZO" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687793-4ad1aa00-fad6-11e8-9b35-c82ec6f1b42d.gif" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/aQRaRK" target="_blank">Link</a>
                        </div>
                    </div>
                </div>

                <div class="container">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687801-61780100-fad6-11e8-992b-09e4cb900fdd.gif" alt="project">
                    <div class="overlay">
                        <div class="text">
                            <a href="https://codepen.io/heatheraislinn/pen/VqZJGr" target="_blank">Link</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="contact">
            <div class="contact-header">
                <h1>Want to learn more about me?</h1>
            </div>
            <a href="https://twitter.com/heatherakshar" target="_blank" class="contact-details">Twitter</a>
            <a id="profile-link" href="https://github.com/heatheraislinn" target="_blank" class="contact-details">GitHub</a>
            <a href="https://codepen.io/heatheraislinn/" target="_blank" class="contact-details">CodePen</a>
            <a href="#" class="contact-details">LinkedIn</a>
            <a href="mailto:heatheraislinn@gmail.com" class="contact-details">Email</a>
        </section>

        <footer>
            <p>&copy; Created by Heather Shar as part of the <a href="https://www.freecodecamp.com/" target="_blank">FreeCodeCamp</a> Responsive Web Design curriculum</p>
        </footer>
    </div>
</template>

<style>
    html, body {
        font-family: 'Helvetica', Arial, sans-serif;
        text-align: center;
    }

    * {
        margin: 0;
        padding: 0;
    }

    /* Welcome Section */

    #welcome-section {
        top: 0;
        background: #85d6bc;
        min-height: 500px;
        padding-top: 375px;
        color: white;
    }

    h1 {
        margin-top: 20px;
        font-size: 3em;
        font-weight: normal;
    }

    .frontend {
        margin-top: 20px;
    }

    /* Nav */

    nav ul {
        text-align: right;
        position: fixed;
        width: 100%;
        background-color: #545454;
    }

    nav ul li {
        display: inline-block;
        margin: 55px;
        margin-bottom: 15px;
        margin-top: 25px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
    }

    nav ul li a:hover {
        color: white;
    }

    /* About Section */

    #about {
        padding-top: 40px;
        padding-bottom: 40px;
    }

    .about-pics {
        display: grid;
        grid-template-columns: 11% 11% 11% 25% 11% 11% 11%;
        grid-template-rows: 200px;
        justify-content: center;
        justify-items: center;
        align-items: center;
    }

    .each-pic {
        height: 100px;
        border-radius: 50%;
        width: 107px;
    }

    .my-pic {
        height: 200px;
        border-radius: 50%;
    }

    .about-description {
        text-transform: uppercase;
        width: 80%;
        font-size: 2.3em;
        text-align: justify;
        margin: 40px auto;
    }

    .frontend {
        text-transform: uppercase;
        font-size: 3em;
    }

    /* Projects Section */

    #projects {
        padding-top: 60px;
        padding-bottom: 60px;
        background: #ede4d7;
    }

    .projects-header {
        font-weight: normal;
        text-transform: uppercase;
        margin-top: 10px;
    }

    .project-tile {
        display: grid;
        grid-template-columns: 50% 50%;
        grid-template-rows: 500px 450px 500px 550px;
        max-width: 900px;
        justify-content: center;
        justify-items: center;
        margin: 40px auto;
        grid-gap: 10px;
    }

    .container {
        position: relative;
    }

    .project-pic {
        display: block;
        width: 100%;
        height: auto;
    }

    .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        height: 100%;
        width: 100%;
        opacity: 0;
        transition: .5s ease;
        background-color: #585858;
    }

    .container:hover .overlay {
        opacity: 1;
    }

    .text {
        color: white;
        font-size: 20px;
        position: absolute;
        top: 50%;
        left: 50%;
        -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
        text-align: center;
    }

    /* Contact Section */

    #contact {
        background: #85d6bc;
        padding-top: 160px;
        padding-bottom: 160px;
        color: white;
    }

    .contact-header {
        padding-bottom: 60px;
        text-transform: uppercase;
        font-weight: normal;
    }

    .contact-details {
        display: inline-block;
        font-weight: bold;
        margin: 0 35px 45px 35px;
        list-style-type: none;
        border: 2px solid white;
        border-radius: 100%;
        width: 100px;
        height: 100px;
        line-height: 100px;
        background: #85d6bc;
        color: white;
        text-decoration: none;
    }

    .contact-details:hover {
        background: white;
        color: #85d6bc;
    }

    /* Footer */

    footer {
        padding: 20px;
        background: #22313F;
        color: white;
        line-height: 40px;
    }

    footer a {
        color: white;
    }




@media only screen and (max-width: 500px) {
  nav ul {
    text-align: center;
  }
  nav ul li {
    margin: 20px;
  }
  .project {
    margin: 40px 0;
  }
}

@media only screen and (max-width: 367px) {
  /*    #contact{
    min-height:1100px;
  } */
  .contact-details {
    border: 2px solid #90C695;
    border-radius: 0;
    width: 90px;
    height: 20px;
    padding: 10px;
    line-height: normal;
  }
}


</style>

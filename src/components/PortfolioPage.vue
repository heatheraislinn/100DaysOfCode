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
                <a href="https://codepen.io/FreeCodeCamp/pen/NNvBQW" target="_blank">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687690-997e4480-fad4-11e8-9747-4a7d1a7c2383.png" alt="project">
                </a>

                <a href="https://codepen.io/FreeCodeCamp/pen/ONjoLe" target="_blank">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687697-b0249b80-fad4-11e8-93d7-41fa3123ba86.png" alt="project">
                </a>

                <a href="https://codepen.io/FreeCodeCamp/pen/PNKdjo" target="_blank">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687687-91bea000-fad4-11e8-809b-595d15e6008f.gif" alt="project">
                </a>

                <a href="https://codepen.io/FreeCodeCamp/pen/mVEJag" target="_blank">
                    <img class="project-pic" src="https://user-images.githubusercontent.com/7342669/49687682-7fdcfd00-fad4-11e8-8c96-6220386c8f19.gif" alt="project">
                </a>


                <a href="https://codepen.io/FreeCodeCamp/pen/wGqEga" target="_blank">
                    <img class="project-pic" src="https://cloud.githubusercontent.com/assets/15967809/17642774/7d091806-6171-11e6-8d47-ecf2f2833fe2.png" alt="project">
                </a>

                <a href="https://codepen.io/FreeCodeCamp/pen/KzXQgy" target="_blank">
                    <img class="project-pic" src="https://cloud.githubusercontent.com/assets/15967809/17642775/7d354304-6171-11e6-8b56-66eee4681d88.png" alt="project">
                </a>
            </div>

            <a href="https://codepen.io/FreeCodeCamp/" class="show-all" target="_blank">Show all</a>
        </section>

        <section id="contact" class="contact">
            <div class="header">
                <h1>Let's work together...</h1>
                <p>How do you take your coffee?</p>
            </div>
            <a href="https://facebook.com/freecodecamp" target="_blank" class="contact-details">Facebook</a>
            <a id='profile-link' href="https://github.com/freecodecamp" target="_blank" class="contact-details">GitHub</a>
            <a href="https://twitter.com/freecodecamp" target="_blank" class="contact-details">Twitter</a>
            <a href="mailto:example@example.com" class="contact-details">Send a mail</a>
            <a href="tel:555-555-5555" class="contact-details">Call me</a>
        </section>

        <footer>**This is just a fake portfolio.. All the projects and contact details given are not real..
            <p>&copy; Created for <a href="https://www.freecodecamp.com/" target="_blank">FreeCodeCamp</a></p>
        </footer>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Quicksand');

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
        font-family: 'Quicksand', sans-serif;
        color: white;
        font-weight: bold;
    }

    h1 {
        margin-top: 20px;
        font-size: 3em;
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
        padding-top: 40px;
        padding-bottom: 40px;
        background: #ede4d7;
    }

    .project-tile {
        display: grid;
        grid-template-columns: 50% 50%;
        grid-template-rows: 450px 450px 450px 450px;
        max-width: 800px;
        justify-content: center;
        justify-items: center;
        align-items: center;
        margin: 40px auto;
        grid-gap: 10px;
    }

    .project-pic {
        width: 100%;
        height: 100%;
    }


    .show-all {
        text-decoration: none;
        display: block;
        width: 200px;
        height: 30px;
        margin: 20px auto 90px;
        background: #e0ebe8;
        color: #008080;
        font-weight: bold;
        font-size: 1em;
        border: 2px solid #90C695;
        border-radius: 4px;
        cursor: pointer;
        padding-top:10px;
    }

    .show-all:hover {
        background: #E4F1FE;
        color: green;
    }

    /* Contact Section */

    .contact {
        background: #C8F7C5;
        padding-bottom: 160px;
    }

    .header {
        padding: 160px 0 110px;
    }

    .contact-details {
        display: inline-block;
        font-weight: bold;
        margin: 0 35px 45px 35px;
        list-style-type: none;
        border: 2px solid #90C695;
        border-radius: 100%;
        width: 100px;
        height: 100px;
        line-height: 100px;
        background: #e0ebe8;
        color: #008080;
        text-decoration: none;
    }

    .contact-details:hover {
        background: #E4F1FE;
        color: green;
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

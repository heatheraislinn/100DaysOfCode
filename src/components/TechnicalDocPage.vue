<template>
    <div>
        <nav id="navbar">
            <header>Tribute Page Documentation</header>
            <ul> 
                <a class="nav-link" href="#Introduction" rel="internal"><li>Introduction</li></a>
                <a class="nav-link" href="#What_you_should_already_know" rel="internal"><li>What you should already know</li></a>
                <a class="nav-link" href="#HTML_and_CSS" rel="internal"><li>HTML and CSS</li></a>
                <a class="nav-link" href="#Where_to_begin" rel="internal"><li>Where to begin</li></a>
                <a class="nav-link" href="#Images" rel="internal"><li>Images</li></a>
                <a class="nav-link" href="#Grids" rel="internal"><li>Grids</li></a>
                <a class="nav-link" href="#Links" rel="internal"><li>Links</li></a>
                <a class="nav-link" href="#Creating_a_background" rel="internal"><li>Creating a background</li></a>
                <a class="nav-link" href="#Fonts" rel="internal"><li>Fonts</li></a>
                <a class="nav-link" href="#Choosing_colors" rel="internal"><li>Choosing colors</li></a>
                <a class="nav-link" href="#Reference" rel="internal"><li>Reference</li></a>
            </ul>
        </nav>

        <main id="main-doc">
            <section class="main-section" id="Introduction">
                <header>Introduction</header>
                <article>  
                    <p>Creating a tribute page is the first project users encounter when working through the Responsive Web Design curriculum from Free Code Camp.</p>
                    <p>This project, and all corresponding projects, are set up in a way that allows the user to create something unique and personal, while also guiding him or her to use concepts learned from the Responsive Web Design challenges. This is achieved by setting the user up with a single task (build a tribute page, for example), and then asking him or her to include a number of smaller tasks to follow a path to completion. For example:</p>
                    <li>Within the <code>img-div</code> element, I should see an element with a corresponding <code>id="img-caption"</code> that contains textual content describing the image shown in <code>img-div</code>.</li>
                    <li>I should see an <code>a</code> element with a corresponding <code>id="tribute-link"</code>, which links to an outside site that contains additional information about the subject of the tribute page. HINT: You must give your element an attribute of <code>target</code> and set it to <code>_blank</code> in order for your link to open in a new tab (i.e. <code>target="_blank"</code>).</li>
                </article>
            </section>

            <section class="main-section" id="What_you_should_already_know">
                <header>What you should already know</header>
                <article>
                    <p>This guide assumes you have the following basic background:</p>
                    <li>A general understanding of the Internet and the World Wide Web.</li>
                    <li>A desire to learn how to code a basic page using HTML and CSS.</li>
                    <li>Interest in learning through Free Code Camp.</li>
                </article>
            </section>

            <section class="main-section" id="HTML_and_CSS">
                <header>HTML and CSS</header>
                <article>
                    <p>HTML and CSS are what we're using to create this tribute page, but what exactly are they? Hopefully I can put together a simple answer to explain them.</p>
                    <p>HTML, or HyperText Markup Language, is a markup language used to describe the structure of a web page. It uses a special syntax or notation to organize and give information about the page to the browser. The HyperText part of HTML comes from the early days of the web and its original use case. Pages usually contained static documents that contained references to other documents. These references contained hypertext links used by the browser to navigate to the reference document so the user could read the reference document without having to manually search for it. The latest version of HTML is HTML5.</p>
                    <p>CSS, or Cascading Style Sheets, tell the browser how to display the text and other content that you write in HTML. Using CSS, you can control things like color, fonts, positioning, spacing, sizing, decorations, and transitions. The idea behind CSS is that you can use a selector to target an HTML element in the DOM (Document Object Model) and then apply a variety of attributes to that element to change the way it is displayed on the page.</p>
                </article>
            </section>

            <section class="main-section" id="Where_to_begin">
                <header>Where to begin</header>
                <article> 
                    <p>I usually begin by creating a simple HTML structure for my pages. If you're using something like CodePen to code in, you don't even have to worry about beginning with things like <code>html</code>, <code>head</code>, or <code>body</code> tags. You can just dive right in.</p>
                    <p>So, I create my basic structure for the page by walking through the story points in the Free Code Camp project instructions.</p>
                </article>
            </section>

            <section class="main-section" id="Images">
                <header>Images</header>
                <article>
                    <p>Images are a fantastic way to add personality to a page. You can use any type of image in your code, whether it's something you created and have locally on your computer, or it's something you found on a website that you can link to.</p>
                    <p>Add images by using the following structure, and note that the <code>img</code> tag is self-closing, meaning it doesn't have a matching tag at its end: <code>img src="" alt=""</code>.</p>
                </article>
            </section>

            <section class="main-section" id="Grids">
                <header>Grids</header>
                <article>
                    <p>CSS Grid helps you easily build complex web designs. It works by turning an HTML element into a grid container with rows and columns for you to place children elements where you want within the grid.</p>
                    <p>Grids are a great way to add interesting structures to your page, and to keep them neat and tidy.</p>
                    <p>Turn any HTML element into a grid container by setting its <code>display</code> property to <code>grid</code>. This gives you the ability to use all the other properties associated with CSS Grid.</p>
                </article>
            </section>

            <section class="main-section" id="Links">
                <header>Links</header>
                <article>
                    <p>Links allow you to add additional information into your page. You can link to both internal and external sources.</p>
                    <p>You can use <code>anchor</code> elements to link to content outside of your web page. <code>anchor</code> elements need a destination web address called an <code>href</code> attribute. They also need anchor text. Here's an example:</p>
                    <code>
                        <a href="https://freecodecamp.org">this links to freecodecamp.org</a>
                    </code>
                    <p>Then your browser will display the text "this links to freecodecamp.org" as a link you can click. And that link will take you to the web address https://www.freecodecamp.org.</p>
                </article>
            </section>

            <section class="main-section" id="Creating_a_background">
                <header>Creating a background</header>
                <article>
                    <p>To add more interest to your page, think about adding a background. A simple gray background can create depth. If you're feeling bold, though, consider adding a wallpaper background.</p>
                    <p>The best way to add a wallpaper background is through a CSS property. In the <code>body</code> selector, set the following: <code>background-image: url("url-goes-here")</code>. You may need to add a few more properties to get the background to fill the entire screen if you'd like. You can also set the opacity so your background isn't too distracting from the rest of your page.</p>
                </article>
            </section>

            <section class="main-section" id="Fonts">
                <header>Fonts</header>
                <article>
                    <p>Fonts can also make a statement. I like to use different fonts in my titles and subtitles. They can draw the eye in and make your text fun to read. Be careful, though. Don't pick a font that makes your page too difficult for users to read!</p>
                    <p><a href="https://fonts.google.com/">Google Fonts</a> is a great source for finding fonts that can add a bit of decoration to your text and still work with any browser.</p>
                </article>
            </section>

            <section class="main-section" id="Choosing_colors">
                <header>Choosing Colors</header>
                <article>
                    <p>CSS gives you the freedom to change colors on many elements in your page. You can change the colors of backgrounds, texts, titles, links, etc.</p>
                    <p>When picking colors, though, it's important to consider usability. Choose colors that look nice, but that also allow users to be able to read what you have to say. Think about how your backgrounds contrast with your texts, and make sure you can see what you need to see!</p>
                </article>
            </section>

            <section class="main-section" id="Reference">
                <header>Reference</header>
                <article>
                    <li>For more information on any of these points, or to try learning how to code so that you can create a tribute page of your own, check out <a href="https://freecodecamp.org" target="_blank">Free Code Camp</a>.</li>
                </article>
            </section>
        </main>
    </div>
</template>

<style>
    html,body {
        min-width: 290px;
        color: #4d4e53;
        background-color: #ffffff;
        font-family: 'Helvetica', Arial, sans-serif;
        line-height: 1.5;
}
    #navbar {
        position: fixed;
        min-width: 290px;
        top: 0px;
        left: 0px;
        width: 300px;
        height:100%;
        border-right: solid 1px gray;
    }

    header {
        color: black;
        font-size: 30px;
        margin: 10px;
        text-align: center;
        font-size: 1.8em;
        font-weight: thin;
    }

    #main-doc header {
        text-align:left;
        margin:0px;
    }

    #navbar ul {
        height: 88%;
        overflow-y: auto;
        overflow-x: hidden;
    }

    #navbar li {
        color: #4d4e53;
        border: 1px solid;
        border-bottom-width: 0px;
        padding: 8px;
        padding-left: 45px;
        list-style: none;
        position: relative;
        left: -50px;
        width: 100%;
    }

    #navbar a {
        color: #4d4e53;
        text-decoration: none;
        cursor: pointer;
    } 

    #main-doc {
        position: absolute;
        margin-left: 310px;
        padding: 20px;
        margin-bottom: 110px;
    }

    section {
        margin-bottom: 30px;
    }

    section article {
        color: #4d4e53;
        margin: 15px;
        font-size: 0.96em;
    }

    section li {
        margin: 15px 0px 0px 20px;
    }

    code {
        background-color: #e6e6e6;
        color: #a90000;
        padding: 2px 5px;
        margin: 5px;
    }

    @media only screen and (max-width: 815px) {
    /* For mobile phones: */
        #navbar ul{
            border:1px solid;
            height:207px;
        }

        #navbar{
            background-color: white;
            position: absolute;
            top: 0;
            padding: 0;
            margin: 0;
            width: 100%;
            max-height: 275px;
            border: none;
            z-index: 1;
            border-bottom: 2px solid;
        }

        #main-doc{
            position: relative;
            margin-left: 0px;
            margin-top: 270px;
        } 

        #main-doc section {
        /* padding-top: 240px; */
        }
    }

    @media only screen and (max-width: 400px) {
        #main-doc{
            margin-left:-10px;
        }
    }

</style>

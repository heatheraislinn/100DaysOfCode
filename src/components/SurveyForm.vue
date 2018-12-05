<template>
    <div id="main">
        <div class="page-container">
            <div class="column-1">
                <div class="instruct-container">
                    <div class="instruct-1">
                        <span class="number">1</span>
                        <span class="direction">Enter!</span>
                    </div>
                    <div class="instruct-2">
                        <span class="number">2</span>
                        <span class="direction">Win!</span>
                    </div>
                    <div class="instruct-3">
                        <span class="number">3</span>
                        <span class="direction">Eat!</span>
                    </div>
                </div>
            </div>

            <div class="column-2">
                <h1 id="title">Win Free Pizza For a Year</h1>
                <p id="description">Fill out this survey to enter the contest</p>

                <form id="survey-form">
                    <div class="rowTab">
                        <div class="labels">
                            <label id="name-label" for="name">Name: </label>
                        </div>
                        <div class="rightTab">
                            <input type="text" class="survey-input" name="name" id="name" placeholder="Enter your name" required>
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label id="email-label" for="email">Email: </label>
                        </div>
                        <div class="rightTab">
                            <input type="email" class="survey-input" name="email" id="email" placeholder="Enter your email" required>
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label id="number-label" for="age">Age: </label>
                        </div>
                        <div class="rightTab">
                            <input type="number" class="survey-input" name="age" id="number" min="1" max="100" placeholder="Age">
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label for="howOften">Which option best describes how often you eat pizza?</label>
                        </div>
                        <div class="rightTab">
                            <select id="dropdown" name="howOften" class="dropdown">
                                <option disabled value>Select an option</option>
                                <option value="daily">Daily</option>
                                <option value="weekly">Weekly</option>
                                <option value="monthly">Monthly</option>
                                <option value="preferNo">Prefer not to say</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label for="userRating">How likely is it that you would recommend pizza to a friend?</label>
                        </div>
                        <div class="rightTab">
                            <ul>
                                <li class="radio"><label>Definitely<input name="radio-buttons" value="1" type="radio" class="userRatings"></label></li>
                                <li class="radio"><label>Maybe<input name="radio-buttons" value="2" type="radio" class="userRatings"></label></li>
                                <li class="radio"><label>Not at all<input name="radio-buttons" value="3" type="radio" class="userRatings"></label></li>
                                <li class="radio"><label>Unsure<input name="radio-buttons" value="4" type="radio" class="userRatings"></label></li>
                            </ul>
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label for="preferences">What are your favorite pizza toppings?</label>
                        </div>
                        <div class="rightTab">
                            <ul id="preferences">
                                <li class="checkbox"><label><input name="prefer" value="1" type="checkbox" class="userRatings">Just cheese</label></li>
                                <li class="checkbox"><label><input name="prefer" value="2" type="checkbox" class="userRatings">Pepperoni</label></li>
                                <li class="checkbox"><label><input name="prefer" value="3" type="checkbox" class="userRatings">Mushrooms</label></li>
                                <li class="checkbox"><label><input name="prefer" value="4" type="checkbox" class="userRatings">Olives</label></li>
                                <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Green peppers</label></li>
                                <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Banana peppers</label></li>
                                <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Anchovies</label></li>
                                <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Pineapple</label></li>
                                <li class="checkbox"><label><input name="prefer" value="5" type="checkbox" class="userRatings">Sausage</label></li>
                            </ul>
                        </div>
                    </div>

                    <div class="rowTab">
                        <div class="labels">
                            <label for="comments">Tell us why you think you should win free pizza for a year:</label>
                        </div>
                        <div class="rightTab">
                            <textarea class="survey-input" id="comments" name="comment" placeholder="Enter your answer here"></textarea>
                        </div>
                    </div>

                     <button id="submit" type="submit">Submit</button>
                </form>
            </div>

        </div>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css?family=Abel');

    html, body {
        font-family: Helvetica, Arial, sans-serif;
        text-align: center;
    }

    #main {
        position: relative;
        padding: 40px;
    }

    #main:after {
        content : "";
        display: block;
        position: absolute;
        top: 0;
        left: 0;
        background: url('https://therecipecritic.com/wp-content/uploads/2018/08/zucchini_crust_pizza-1-of-1.jpg') no-repeat center;
        width: 100%;
        height: 100%;
        z-index: -1;
    }

    .page-container {
        max-width: 800px;
        display: grid;
        grid-template-columns: 250px 550px;
        margin: 0 auto;
        background-color: white;
    }

    .column-1 {
        background: #ac1f01;
        padding: 10px;
        text-align: center;
    }

    .instruct-container {
        display: grid;
        grid-template-rows: 150px 150px 150px;
        align-items: center;
        margin-top: 200px;
    }

    .number {
        color: white;
        font-size: 2.5em;
        border: 2px solid white;
        padding: 10px 20px;
        border-radius: 50%;
    }

    .direction {
        display: block;
        margin-top: 20px;
        font-family: 'Abel', sans-serif;
        text-transform: uppercase;
        font-size: 1.5em;
        color: white;
        font-weight: bold;
    }

    .column-2 {
        padding: 10px;
    }

    #title {
        font-family: 'Abel', sans-serif;
        text-transform: uppercase;
        margin-bottom: 0;
    }

    p {
        margin-top: 0;
    }

    .labels {
        display: inline-block;
        text-align: right;
        width: 40%;
        padding: 5px;
        vertical-align: top;
        margin-top: 10px;
    }

    .rightTab {
        display: inline-block;
        text-align: left;
        width: 48%;
        vertical-align: middle;
    }

    .survey-input {
        height: 20px;
        width: 250px;
        padding: 5px;
        margin: 10px;
        border: 1px solid #c0c0c0;
        border-radius: 2px;
    }

    .dropdown {
        height: 35px;
        width: 140px;
        padding: 5px;
        margin: 10px;  
        margin-top: 15px;
        border: 1px solid #c0c0c0;
        border-radius: 2px;
    }

    .radio, .checkbox {
        position: relative;
        left: -43px;
        margin-left: 10px;
        display: block;
        padding-bottom: 10px;
    }

    .userRatings, input[type="checkbox"] {
        float: left;
        margin-right: 5px;
    }

    textarea {
        height: 75px !important;
    }

    #submit {
        background-color: #ac1f01;
        border-radius: 4px;
        color: white;
        font-weight: bold;
        font-size: 1em;
        padding: 10px;
        border: 0px solid;
        margin: 15px;
        cursor: pointer;
    }

    @media screen and (max-width: 833px) {
        .survey-input {
            width: 70%;
        }
        select {
            width: 90%;
        }
    }

    @media screen and (max-width: 650px) {
        #title {
            text-align: left;
            width: 50%;
        }
        p {
            text-align: left;
            width: 50%;
        }
        .labels {
            width: 50%;
            text-align: left;
            float: left;
        }
        .rightTab {
            width: 100%;
            float: left;
        }
        .survey-input {
            width: 40%;
        }
        select {
            width: 100%;
        }
        button {
            float: left;
        }
    }

     @media screen and (max-width: 580px) {
        #title {
            text-align: left;
            width: 40%;
        }
        p {
            text-align: left;
            width: 40%;
        }
        .labels {
            width: 40%;
            text-align: left;
            float: left;
        }
        .rightTab {
            width: 100%;
            float: left;
        }
        .survey-input {
            width: 35%;
        }
        select {
            width: 100%;
        }
        button {
            float: left;
        }
    }

</style>

# Here I will be giving you some steps and references to complete this challenge.


## Step 1 - Bringing in our styles/stylesheets (CSS)
* I've already written all of the css for this project
* so you wont need to change anything in our "main.css" file
* you will however need to bring it into our index.html file.
* so on line 8 of our index.html file, you will need to add in a link tag.
* this link tag will need to reference (href) our file "main.css"

* Info about link tags found here:
* https://www.w3schools.com/tags/tag_link.asp


* If you've got this hooked up right, you should be able to
* double click the index.html file from finder
* and see a dark background on the page.
* If not, go read the website again :)


## Step 2 - Creating our button click function (JS)
* Before we hook it up to our HTML, inside of our "button-click.js" file
* we need to create the logic that will be alerting our user that the button has been clicked
* we will be using a *function* that you can call anything you'd like,
* just something that makes sense to read/has purpose... something like "handleClick" or "alertUser"
* whichever feels more comfortable for you.

* Info about functions here:
* https://www.w3schools.com/js/js_functions.asp
* (Very useful at the bottom of the page)

* More info about the javascript window object's alert method found here:
* https://www.w3schools.com/jsref/met_win_alert.asp


## Step 3 - Bringing in our button-click.js file to our HTML (HTML)
* On line 23 of our index.html file,
* we will need to add in our script containing the function we created
* to do this we will need a script tag with the "src" property being our "button-click.js" file

* Info about script tags here:
* https://www.w3schools.com/tags/att_script_src.asp

* At this point, you should be able to refresh the page on your index.html
* And in your console, you should see the console.log I put in there that says "File is hooked up correctly".
* If not, recheck your script tag in index.html.


## Step 4 - Creating our container with our button. (HTML)
* Here's where it all comes together.
* On line 16 of our index.html,
* Create a "div" element with a "class" attribute of "button-container".
* This is because of the styles I have in main.css
* which will make the button look better, as well as center it on the screen.
* Inside of the button-container div, create a "button" element which says anything you want,
* such as "Click here" and has an "onClick" attribute which *Invokes* our function we wrote in button-click.js

* Info about html classes here:
* https://www.w3schools.com/html/html_classes.asp

* Info about html button onclick attribute:
* https://www.w3schools.com/jsref/event_onclick.asp

* At this point our dope ass app should be running in full force.
* Should look like the screenshots in the screenshots folder,
* and should alert the user every time the button is clicked.
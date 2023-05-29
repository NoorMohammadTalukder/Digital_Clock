# About

This simple digital clock application using html,css and js build for assignment purpose

## Installation

Just clone the repository and open the index.html file in your browser.

## Description of project

* The HTML code includes a video element that plays the "bg.mp4" file on loop, and a div element with an id "clock" where the clock will be displayed.

* The JavaScript function "updateClock" gets the current time and formats it to display in the "clock" element. It checks if the hours, minutes, and seconds are less than 10 and adds a leading zero if true. The time is then concatenated and assigned to the innerHTML property of the "clock" element.

* The "updateClock" function is called once initially, and then repeatedly every second using setInterval method to keep the clock updated in real-time.

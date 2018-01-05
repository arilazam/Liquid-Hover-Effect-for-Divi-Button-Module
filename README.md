# Liquid-Hover-Effect-for-Divi-Button-Module
Using canvas and JavaScript you can achieve really awesome effects. Recently I’ve come across this cool liquid hover effect and I tried to apply it to Divi button module. It might look like too much code for a single button, but it is experimental and I just wanted to show how it can be implemented for Divi.

To implement this effect we’ll have to assign a CSS class to the Button Module and apply neccessary settings, then use Javascript to wrap the button text with span and insert the canvas inside the button and apply the liquid hover effect. Also we’ll use some CSS for canvas and button text.

Step 1: Apply the following button settings. Important ones are the border radius and transparent background color.

Button Settings -> Design
use custome styles for button: yes
button text size: 20
button border radius: 100
button hover border radius: 100

Step 2: Add the *btn-liquid* CSS class to Button Settings -> Advanced -> CSS Class field.

Step 3: This is the JS code snippet for the liquid hover effect. You can set the color stops for the button dynamic gradient and the background color (see highlighted lines in the code below).

Liquid Button.js

Add the JS code snippet into the Divi -> Theme Options -> Integration -> Add code to the < body > field.

Step 4: We need to apply some CSS rules to button text and the canvas, for this we’ll use the following CSS snippet:

Liquid Button.css

Copy the CSS snippet above and add it into the Divi -> Theme Options -> General -> Custom CSS field.

That’s all, enjoy the effect.

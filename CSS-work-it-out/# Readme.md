# Readme

## Purpose

Using CSS selectors, you'll give a exercise webpage some new style. 

## Getting Started

Before you begin, take a look at the site’s structure and be sure you understand the classnames and any additional attributes already in the HTML. 

1. Create a separate CSS file called "style.css" - Be sure to that your new css file is in the same folder as your HTML.
2. Link your HTML to your new CSS file 
3. To begin styling, making the image at the top of the page a little smaller. Navigate to style.css and write a CSS selector for the img tag.
    - Within its curly braces, write: ```height: 150px;```
4. The font size of the workout description should be larger. In style.css, write a CSS selector for the ```.description``` class. Change the font size to ```font-size:20px;```
5. Next, let’s style the workout time. The element on line 15 of index.html has an id attribute of workout-time. Navigate to style.css and add a workout-time ID selector. Then make the ```font-weight: bold;```
6. Now, let’s change the bullet points of the equipment list to squares instead of circles. Start by writing a selector for the li elements inside of the .equipment element. Then change the ```list-style:square;```
7. Next let’s make the time for each exercise step appear gray. In style.css, write a selector for p elements that also have a class of .time and change the color to gray. 
8. At the bottom of the page, there’s a link to the full workout.Change the link color to ```color:SeaGreen;```

9. Finally, let’s make the font Helvetica instead of the default Times New Roman. Instead of writing multiple selectors to apply the font-family property, write a selector that applies a font-family attribute to all text at once.

The selector should target the h1, h2, p, and li elements.

```font-family: Helvetica;```
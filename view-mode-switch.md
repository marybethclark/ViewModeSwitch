# What does it do? #


## What interactive elements exist?
display mode icons in upper right

bottle icons

"add to cart" buttons

## How do you interact with them?

 by hovering and by clicking the display mode icons

by hovering - Bottle icons are "fake" links.

by hovering - "add to cart" buttons are "fake" links.

##  What visual effects are produced by interacting?
Display mode icons change color from grey to blue on hover.

Display mode icons change the entire page layout when clicked.

"add to cart" button switches to darker shade of blue on hover.

## How does it do it?
for page layout change - a javascript function with an event listener that somehow changes the scripts.css link from one file to another??

See "What CSS styles are used" below for the other 2 "how" methods.

## What existing HTML elements are changed?
It looks as if all of the elements are re-used, just arranged in a different layout.
## What new HTML elements are created?
I can't see that any new HTML elements are created.

## What CSS styles are used to produce the effect?
hover to make "add to cart" button switch to darker shade of blue

 hover to make display mode icons change color from grey to blue

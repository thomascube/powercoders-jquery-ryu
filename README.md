# jQuery Exercise: Ryu fires a Hadouken

Build a simple page showing Ryu firing a Hadouken. Use jQuery to switch images when mouse hovers or clicks on Ryu and animate a Hadouken image on click. Display the total number of Hadoukens fired as text below the image.

## Preparation

First: Get yourself familiar with the [jQuery API documenation](http://api.jquery.com/).

Second: Clone this repository ont your computer using git bash.

## Instructions

The goal is to code the mouse interactions using jQuery inside the `index.html` file as shown in the [demo video](https://www.dropbox.com/sh/ubzin2y7vdfd7lz/AAB5PyM3-6gckn7K24Oelidda?dl=0&preview=jquery-ryu.mp4#).

1. When mouse enter the Ryu image, the `images/ryu_animated.gif` image shall be shown.
2. When mouse leaved the Ryu image, the initial still image shall be shown.
3. When mouse button in pressed, the image `images/ryu_hadouken_pose.png` shall be shown plus:
   * A new image `images/hadouken.gif` shall be added to the DOM
   * The hadouken image shall be animated to the right using a 'swing' animation of one second.
   * When the animation is done, the hadouken image shall be removed from the DOM
4. The number of hadoukens fired by Ryu shall be counted and displayed as text below the image. Update the counter after the hadouken was been fired.

Good luck!
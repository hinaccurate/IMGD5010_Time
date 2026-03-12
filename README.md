# IMGD5010_Time
An assignment to create a  formal piece of visual music, an animation that focuses on developing and playing with a single graphical element over time.

## morning time
### link to work

[https://editor.p5js.org/hinaccurate/full/qAbtMPciO](https://editor.p5js.org/hinaccurate/full/qqq43M6QP)

### what I tried to create 

This is the third attempt I've made to scale down an overly ambitious project related to animating a single element over time. I have now animated a circle to form a rising sun to the opening measures of "Call to the Cows" from Rossini's _William Tell Overture._

### what's actually there

Using what I learned in previous iterations, the sun (a circle) rises and expands across a lightening background until it stops at the end of the music, going from nighttime to dawn to morning in about 13 seconds. This is accomplished by 

1. translating the orientation of the coordinates so the circle can rise from the bottom of the canvas,
2. using noStroke and the blur filter to create a realistically colored sun,
3. having both the diameter and the Y coordinate of the sun affected by the frame count to allow it to appear bigger relative to how high it goes,
4. using variables affected by the millisecond count to adjust the background color, and
5. using milliseconds (more accurate and easier to match to the music) to ensure the entire drawing would stop looping when the music finished.

### how I got here

Previous iterations of this assignment include:

1. "approaching the hall of the mountain king", [https://editor.p5js.org/hinaccurate/full/tL1dzzvhu](https://editor.p5js.org/hinaccurate/full/tL1dzzvhu), which also used a circle as the graphical element; this is where I did the most work with the millisecond function, embedded background music, and the using the blur filter to create effects
2. "we're gonna need a bigger boat", [https://editor.p5js.org/hinaccurate/full/jDRRT78a3](https://editor.p5js.org/hinaccurate/full/jDRRT78a3), which used the letter "V" as a graphical element; this animation did not include background music and was intended to only animate about 6 measures of the _Jaws_ leitmotif, but it was again too far out of scope; this is where I did the most work with the translate function used in the submitted assignment

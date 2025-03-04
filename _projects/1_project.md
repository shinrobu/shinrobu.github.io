---
layout: page
title: Arduino Fighstick
description: A project to create a game controller with an arcade-style button layout, colloquially known as a "fightstick."
img: assets/img/fightstick.jpg
importance: 1
category: Work
related_publications: false
---

This is a project to create a game controller with an arcade-style button layout, colloquially known as a "fightstick." Created using <a href="https://github.com/AlanChatham/UnoJoy">Alan Chatham's UnoJoy library</a>, and an Arduino Mega 2560 Rev3.

This fightstick has an LCD screen display (QAPASS 1602A) as well, for an extra feature to practice with. This is used as to display the buttons currently being pressed on the controller. However, a  7ms delay was implemented to make the LCD screen actually readable. This was the closest value we could compromise with to make the controller as responsive as possible while making the LCD readable.

If you would like to create a controller that would be more practical, I highly recommend to not implement this LCD feature. 7ms delay is a significant negative factor in playing competitive fighting games.

There's no documentation on how the actual fightstick itself was built/wired, but it's not too hard to create the actual fightstick.



To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fightstick.jpg" title="Fightstick image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fightstick2.jpg" title="Fightstick image 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Finished product. Woodworking and wiring done by Garrett Wong. Photo credit: Kevin Ly
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}

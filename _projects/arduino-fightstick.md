---
layout: page
title: Arduino Fightstick
description: A project to create a game controller with an arcade-style button layout, colloquially known as a "fightstick."
img: assets/img/fightstick.jpg
importance: 2
category: Work
related_publications: false
---

This is a project to create a game controller with an arcade-style button layout, colloquially known as a "fightstick." Created using <a href="https://github.com/AlanChatham/UnoJoy">Alan Chatham's UnoJoy library</a>, and an Arduino Mega 2560 Rev3.

This fightstick has an LCD screen display (QAPASS 1602A) as well, for an extra feature to practice with. This is used as to display the buttons currently being pressed on the controller. However, a  7ms delay was implemented to make the LCD screen actually readable. This was the closest value we could compromise with to make the controller as responsive as possible while making the LCD readable.

If you would like to create a controller that would be more practical, I highly recommend to not implement this LCD feature. 7ms delay is a significant negative factor in playing competitive fighting games.

There's no documentation on how the actual fightstick itself was built/wired, but it's not too hard to create the actual fightstick.

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

### Parts List
- Arduino Mega 2560 Rev3
- QAPASS 1602A LCD Screen
- Arcade Joystick (we used a Sanwa JLF 8-way joystick, easily found on Amazon)
- 8x Arcade Buttons (we used 30mm Qanba buttons, also easily found on Amazon)
- An enclosure for the fightstick itself

The code for the project can be found at this repository: 

<div class="repo p-2 text-center">
    <a href="https://github.com/shinrobu/Arduino-Fightstick" rel="external nofollow noopener" target="_blank"> 
        <img class="only-light w-100" alt="shinrobu/Arduino-Fightstick" src="https://github-readme-stats.vercel.app/api/pin/?username=shinrobu&amp;repo=Arduino-Fightstick&amp;theme=buefy&amp;locale=en&amp;show_owner=false&amp;description_lines_count=2"> 
        <img class="only-dark w-100" alt="shinrobu/Arduino-Fightstick" src="https://github-readme-stats.vercel.app/api/pin/?username=shinrobu&amp;repo=Arduino-Fightstick&amp;theme=midnight-purple&amp;locale=en&amp;show_owner=false&amp;description_lines_count=2"> 
        </a>
</div>

Special thanks to Garrett Wong, Kevin Ly, and Keenan Tan for their contributions to this project.
---
layout: page
title: Arduino Fightstick
description: An alarm clock based on an FPGA board, utilizing VGA to show the clock on a monitor.
img: assets/img/fpga_alarm_clock.png
importance: 4
category: Work
related_publications: false
---

This project was creating an alarm clock in Verilog.

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
- Nexys A7 100T FPGA Board
- VGA Cable

The code for the project can be found at this repository: 

<div class="repo p-2 text-center"> 
    <a href="https://github.com/xenoQui/FPGA-AlarmClock" rel="external nofollow noopener" target="_blank"> 
        <img class="only-light w-100" alt="xenoQui/FPGA-AlarmClock" src="https://github-readme-stats.vercel.app/api/pin/?username=xenoQui&amp;repo=FPGA-AlarmClock&amp;theme=buefy&amp;locale=en&amp;show_owner=true&amp;description_lines_count=2"> 
        <img class="only-dark w-100" alt="xenoQui/FPGA-AlarmClock" src="https://github-readme-stats.vercel.app/api/pin/?username=xenoQui&amp;repo=FPGA-AlarmClock&amp;theme=midnight-purple&amp;locale=en&amp;show_owner=true&amp;description_lines_count=2"> 
    </a> 
</div>
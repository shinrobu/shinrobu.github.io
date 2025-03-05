---
layout: page
title: FPGA Alarm Clock in Verilog
description: An alarm clock based on an FPGA board, utilizing VGA to show the clock on a monitor.
img: assets/img/fpga_alarm_clock.png
importance: 4
category: Work
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fpga_alarm_clock.png" title="Alarm clock image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Screenshot of the finished alarm clock.
</div>

This project was creating an alarm clock in Verilog, coded in Vivado 2023. The time is set utilizing the switches on the FPGA board, and the time is displayed on a monitor. When the real time matches the alarm time, the screen flashes green.

My role in this project was aiding in the combination of the Alarm + Clock modules, and to implement the VGA function.

### Parts List
- Nexys A7 100T FPGA Board
- VGA Cable

The code has 3 main segments:
- AlarmClock (Final/Combined)
- Alarm (Sound)
- Clock (Standalone)

The code for the project can be found at this repository: 

<div class="repo p-2 text-center"> 
    <a href="https://github.com/xenoQui/FPGA-AlarmClock" rel="external nofollow noopener" target="_blank"> 
        <img class="only-light w-100" alt="xenoQui/FPGA-AlarmClock" src="https://github-readme-stats.vercel.app/api/pin/?username=xenoQui&amp;repo=FPGA-AlarmClock&amp;theme=buefy&amp;locale=en&amp;show_owner=true&amp;description_lines_count=2"> 
        <img class="only-dark w-100" alt="xenoQui/FPGA-AlarmClock" src="https://github-readme-stats.vercel.app/api/pin/?username=xenoQui&amp;repo=FPGA-AlarmClock&amp;theme=midnight-purple&amp;locale=en&amp;show_owner=true&amp;description_lines_count=2"> 
    </a> 
</div>
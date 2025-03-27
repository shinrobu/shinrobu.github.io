---
layout: page
title: Arduino Midi Controller
description: A project to create a controller that would be able to play MIDI sounds when connected to a computer.
img: assets/img/midi_controller_back.png
importance: 2
category: 2022
related_publications: false
---

This is a project to create a controller that plays Musical Instrument Digital Interface, or MIDI, files. Made using 16 Sanwa arcade buttons, a 3D printed case, and soldered wires. The main code stems from using <a href="https://github.com/arduino/tutorials/tree/master/ArduinoZeroMidi">one of Arduino's MIDI tutorials</a>, and an Arduino Leonardo.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/midi_controller_back.png" title="MIDI controller back image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid loading="eager" path="assets/video/midi_demo_video.mp4" title="Fightstick image 2" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Back of the MIDI controller alongside a demo video. In the video, the MIDI controller is connected to a laptop, playing audio as the buttons are pressed.
</div>

### Parts List
- Arduino Leonardo
- PLA
- 16x Sanwa Arcade Buttons
- Soldering Equipment

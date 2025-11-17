---
layout: page
title: Visual SLAM Mapping
description: A project to help develop the mapping systems of an autonomous racing car.
img: assets/img/SLAM_Screenshot.png
importance: 1
category: 2025
related_publications: false
---

This is a project to research solutions for mapping systems for Roboracer (formerly known as F1Tenth). Focusing on visual SLAM (Simultaneous Localization and Mapping), which uses a camera feed to plot key features and create a local map for autonomous navigation. Primarily uses <a href="https://github.com/UZ-SLAMLab/ORB_SLAM3">ORB-SLAM3's visual SLAM algorithm.</a> Uses Robot Operating System (ROS) for standardized data transfer.

My contributions to this project involves being able to run ORB-SLAM3 on a Raspberry Pi 4 on Ubuntu 20.04, getting the point cloud. Video feed is captured with a Playstation Eye. Further research is to be done on turning this point cloud into a more refined, outlined map, and to determine which factors affect performance the most (camera model, computer, etc.)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SLAM_Screenshot.png" title="point cloud image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The left window is a point cloud of a classroom laboratory. The window on the top right is the keyframe being analyzed by ORB-SLAM3's algorithm, and the bottom right image shows the ROS tree: raw video feed is fed into ORB-SLAM3 and is outputted as seen to the other two windows.
</div>

### Parts List and Software
- Raspberry Pi 4 (Ubuntu 20.04)
- Playstation Eye
- ORB-SLAM3
- USB Keyboard
- USB Mouse
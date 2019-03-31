---
layout: archive
title: "Projects"
permalink: /projects/

feature_row1:
  - image_path: https://i.imgur.com/1jfyYW5.png?1
    alt: "Visual-Inertial SLAM"
    title: "Visual-Inertial SLAM"
    excerpt: "This project uses IMU and visual features as sensing modalities, and the goal of the project is to track vehicle pose and landmark positions over time. The project uses Extended Kalman Filter to accomplish Simultaneous Localization and Mapping (SLAM)."
    url: "https://github.com/jamesdi1993/VisualSLAM"
    btn_label: "Code"
  - image_path: https://i.imgur.com/FNJ3DIi.png?1
    alt: "Particle-Filter SLAM"
    title: "Particle-Filter SLAM"
    excerpt: "The goal of the project is to map out the environment as well as the robot trajectory over time. The sensing  modalities in this project are IMU, encoders, Lidar and RGBD images. Finally, a texture map of the environment is created based on the images captured by the camera."
    url: "https://github.com/jamesdi1993/particle_filter_slam"
    btn_label: "Code"
---

{% include base_path %}
{% include feature_row id="feature_row1" %}
---
layout: archive
title: "Projects"
permalink: /projects/

feature_row1:
  - image_path: https://i.imgur.com/1jfyYW5.png?1
    alt: "Visual-Inertial SLAM"
    title: "Visual-Inertial SLAM"
    excerpt: "This project uses IMU and visual features as sensing modalities, and the goal of the project is to track vehicle pose and landmark positions over time. The project uses Extended Kalman Filter to accomplish Simultaneous Localization and Mapping (SLAM)."
    url: "https://github.com/jamesdi1993/ece276a-visual-slam"
    btn_label: "Code"
  - image_path: https://i.imgur.com/FNJ3DIi.png?1
    alt: "Particle-Filter SLAM"
    title: "Particle-Filter SLAM"
    excerpt: "The goal of the project is to map out the environment as well as the robot trajectory over time. The sensing modalities in this project are IMU, encoders, Lidar and RGBD images. Finally, a texture map of the environment is created based on the images captured by the camera."
    url: "https://github.com/jamesdi1993/particle-filter-slam"
    btn_label: "Code"
  - image_path: https://i.imgur.com/MbZU6zl.png
    alt: "Motion Planning"
    title: "Motion Planning"
    excerpt: "This project implements two motion planners of different classes, A* and Bi-directional RRT. Both planners are tested on six different 3D environments and performance metrics are compared for the two planners."
    url: "https://github.com/jamesdi1993/ece276b-motion-planning"
    btn_label: "Code"
  - image_path: https://i.imgur.com/r3VY9XT.gif
    alt: "Mountain Car RL"
    title: "Mountain Car RL"
    excerpt: "We solve the mountain car problem in OpenAI using Reinforcement techniques. We implemented On-policy and Off-policy TD-Learning for this project."
    url: "https://github.com/jamesdi1993/ece276b-rl"
    btn_label: "Code"
---

{% include base_path %}
{% include feature_row id="feature_row1" %}
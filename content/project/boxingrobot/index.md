---
title: Boxing Robot - Design and Motion Tracking
summary: A boxing robot that can mimics human movements using visual input.
tags:
  - Deep Learning
  - Computer Vision
  - Robotics
  - Mechanical Design
  - Machine Learning
date: '2021-12-08T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: 'https://www.youtube.com/watch?v=BDZE6ahYLlw'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In science fiction, it’s so cool to see those boxing robots fighting with each other by imitating human actions. In this project, we make it real by designing a boxing robot and proposing a control pipeline to have it mimic human movements using only markerless visual input. As a result, our robot moves in a reasonable way, extremely like human boxing motion in real life. The main work of the project are as follows:

• Designed and assembled a kind of humanoid robot consisting of two arms and a trunk with 9 degrees of freedom, built a simulator using MATLAB robotics toolbox to simulate the dynamic motion of the robot designed. \
• Recorded a boxing motion from two views using two optical cameras and synchronized them by analyzing audio signals, extracted the 3D motion data of 8 upper body landmarks from the synchronized videos using MediaPipe Pose and designed a post-processing algorithm to integrate the motion data predicted from two videos and project it to the workspace of the robot.\
• Solved inverse kinematics to get the joint angle in each frame and designed a PID controller to follow the motion trajectory.\
• Proposed robot succeeded in mimicking human boxing motion by achieving a mae within 6 degrees for most joints during the following task.

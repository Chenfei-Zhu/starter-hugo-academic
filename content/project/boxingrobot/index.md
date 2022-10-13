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
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In science fiction, it’s so cool to see those boxing robots fighting with each other by imitating human actions. In this project, we make it real by designing a boxing robot and proposing a control pipeline to have it mimic human movements using only markerless visual input. As a result, our robot moves in a reasonable way, extremely like human boxing motion in real life. The main work of the project are as follows:

• Designed and assembled a kind of humanoid robot consisting of two arms and a trunk with 9 degrees of freedom, build a simulator using Rigid Body Tree structure in MATLAB robotics toolbox to simulate the dynamic motion of the robot designed.

• Recorded the boxing motion of our model from two angles by two optical cameras, synchronized them by extracting and analyzing the audio signals in both videos.\
• Extracted the 3D motion data of 8 upper body landmarks from synchronized videos using MediaPipe Pose, an ML solution for high-fidelity body pose tracking. \
• Designed a post-data-processing algorithm to integrate the motion data collect from different cameras to reduce the error caused by occlusions of some key points in motion, and project the position of all the landmarks onto the workspace of the robot designed to smooth the motion.\
• Solved inverse kinematics to get joints angle corresponding to each frame, designed a PID controller to follow the motion trajectory of our model.\
• With a mae within 6 degrees for most joints in the following task, our robot moves in a reasonable way, extremely like human boxing motion in real life.

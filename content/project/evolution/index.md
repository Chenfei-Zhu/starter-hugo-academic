---
title: Evolutionary Robot
summary: Use evolutionary algorithms to evolve a novel robot.
tags:
  - Evolutionary Algorithm
  - Robotics
  - Machine Learning
date: '2021-12-07T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
 # caption: Photo by rawpixel on Unsplash
  #focal_point: Smart

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

In this project, we used evolutionary algorithms to evolve a novel robot and let it learn how to walk and run faster. The main contributions are as follows:

• Built a physics simulator in Python to simulate the motion of robots in the real world. The simulator covers physical and mechanical properties including gravity, resistance, ground force, damping, etc. \
• Designed several mass-spring robots with different parameters, simulated their behaviors in the physical simulator, let them compete with each other in a running game to select the most competitive robot. \
• Used evolutionary algorithms to evolve the robot on its mass-spring parameters. Robots in newer generations usually perform better than those from older generations in the running game.

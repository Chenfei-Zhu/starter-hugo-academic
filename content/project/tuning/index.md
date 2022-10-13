---
title: Neural Network Hyperparameters Tuning - Reinforcement Learning Approach
summary: A method to efficiently optimize the hyperparameters of a CNN network without human intervention.
tags:
  - Deep Learning
  - Reinforcement Learning
  - Machine Learning
  - Computer Vision
date: '2021-12-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image:
 # focal_point: Smart

links:
url_code: ''
url_pdf: "uploads/tuning.pdf"
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Hyperparameter tuning is critical for the performance of deep learning models. However, a noticeable limitation is the high computational cost of hyperparameters searching for complex models or for large datasets, which makes the tuning process highly inefficient. In this project, we proposed a method to efficiently optimize the parameters of a CNN network without human intervention. The CNN network is designed to track the position of human hands in Parkinson's finger tapping test proposed by the Movement Disorder Society. The main work of the project includes:

• Collected a dataset of about 18k RGB images of subjects performing Parkinson’s finger tapping test; each image contains a human hand with four hand joint annotations, built a simple CNN network for hand joint tracking.\
• Proposed a model-based reinforcement learning method for efficient hyperparameter optimization: Designed a reinforcement learning environment to provide observation, action, and reward based on the network's hyperparameters and performance and built a DQN agent to learn how to improve the structure of the network.\
• The agent learned how to optimize the hyperparameters of the network from a bad setting within a short time period and achieve human-level accuracy.

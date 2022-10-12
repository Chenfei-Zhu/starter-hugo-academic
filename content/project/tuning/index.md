---
title: Neural Network Hyperparameters Tuning - Reinforcement Learning Approach
summary: A method to efficiently optimize the hyperparameters of a CNN network without human intervention.
tags:
  - Deep Learning
  - Reinforcement Learning
date: '2021-12-27T00:00:00Z'

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

Hyperparameter tuning is critical for the performance of deep learning models. However, a noticeable limitation is the high computational cost of hyperparameters searching for complex models or for large datasets, which makes the tuning process highly inefficient. In this project, we proposed a method to efficiently optimize the parameters of a CNN network without human intervention. The CNN network is designed to track the position of human hands in Parkinson's finger tapping test proposed by the Movement Disorder Society. The main work of the project includes:

• Collected and labeled about 18k images of people performing the finger tapping exam, each image contains a human hand and was labeled by four key points.\
• Designed a CNN network structure to track the position of human hands.\
• Proposed a method to reduce the searching space of models by building a unique mapping between models and the combinations of model dimensions and several parameter groups choosing from pre-determined value boxes.\
• Proposed a novel model-based reinforcement method for efficient hyperparameter optimization. Designed the environment, built a DQN agent, trained it on a subset of our dataset.\
• The agent learned how to optimize the parameters of the network from a bad setting within a short time period, and achieve human-level accuracy, resulting in the lowest mae of 0.0036( in pixel).\

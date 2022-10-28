---
title: "A Deep-Learning Based Real-Time Prediction of Seated Postural Limits and its Application in Trunk Rehabilitation"
authors:
- Xupeng Ai
- Santamaria Victor
- Jiawei Chen
- Boce Hu
- admin
- Sunil K, Agrawal
date: "2022-08-25T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "TechRxiv"
publication_short: "TechRxiv, 2022. Accessed 25 Aug 2022. Preprint"

abstract: Seated postural limit defines the region from beyond which a subject cannot return the trunk to the neutral position without additional external support. The seated postural limits can be used as a reference to provide assistive support to the torso by an appropriately designed robotics, e.g., Trunk Support Trainer (TruST). However, fixed boundary representations of seated postural limits in the literature cannot capture the dynamically changing seated postural limits during training. In this study, we propose a conceptual model of the dynamic boundary of the trunk center using a boundary vector designed to track the postural-goal direction and trunk movement amplitude during a sitting task. We experimented with 20 healthy subjects. The results support our hypothesis that TruST intervention with an assist-as-needed controller based on the proposed dynamic boundary representation could achieve more significant sitting workspace area improvements than a fixed boundary representation. The second contribution of this paper is that we provide an approach to effectively introduce deep learning into TruST's real-time controller design. We compiled a 3D trunk movement dataset which is currently the largest in the literature. We designed a loss capable of solving the gate-controlled regression problem. We proposed a novel roadmap for the exploration study. Following the roadmap, we developed a deep learning architecture, modified the widely used Inception module, and then obtained a deep learning model capable of accurately predicting the dynamic boundary in real-time. We believe this approach can be extended across other rehabilitation robots towards designing intelligent dynamic boundary-based assist-as-needed controllers.

# Summary. An optional shortened abstract.
# summary: 


featured: false

links:
url_pdf: https://doi.org/10.36227/techrxiv.20499006.v1
url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---



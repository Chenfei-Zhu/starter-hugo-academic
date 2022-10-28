---
title: "ACRNet: Attention Cube Regression Network for Multi-view Real-time 3D Human Pose Estimation in Telemedicine"
authors:
- Boce Hu
- admin
- Xupeng Ai
- Sunil K, Agrawal
date: "2022-10-11T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv, 2022. Accessed 11 Oct 2022. Preprint"

abstract: Human pose estimation (HPE) for 3D skeleton reconstruction in telemedicine has long received attention. Although the development of deep learning has made HPE methods in telemedicine simpler and easier to use, addressing low accuracy and high latency remains a big challenge. In this paper, we propose a novel multi-view Attention Cube Regression Network (ACRNet), which regresses the 3D position of joints in real time by aggregating informative attention points on each cube surface. More specially, a cube whose each surface contains uniformly distributed attention points with specific coordinate values is first created to wrap the target from the main view. Then, our network regresses the 3D position of each joint by summing and averaging the coordinates of attention points on each surface after being weighted. To verify our method, we first tested ACRNet on the opensource ITOP dataset; meanwhile, we collected a new multi-view upper body movement dataset (UBM) on the trunk support trainer (TruST) to validate the capability of our model in real rehabilitation scenarios. Experimental results demonstrate the superiority of ACRNet compared with other state-of-theart methods. We also validate the efficacy of each module in ACRNet. Furthermore, Our work analyzes the performance of ACRNet under the medical monitoring indicator. Because of the high accuracy and running speed, our model is suitable for real-time telemedicine settings

# Summary. An optional shortened abstract.
# summary: 

featured: false

links:
url_pdf: https://arxiv.org/pdf/2210.05130.pdf
url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

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


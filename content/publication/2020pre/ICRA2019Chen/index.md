---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Adaptive Probabilistic Vehicle Trajectory Prediction Through Physically Feasible Bayesian Recurrent Neural Network"
authors:
  - Chen Tang
  - Jianyu Chen
  - Masayoshi Tomizuka
date: 2019-05-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-05-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation* (**ICRA**), 2019
# publication_short: In *IROS 2022*

abstract: Probabilistic vehicle trajectory prediction is essential for robust safety of autonomous driving. Current methods for long-term trajectory prediction cannot guarantee the physical feasibility of predicted distribution. Moreover, their models cannot adapt to the driving policy of the predicted target human driver. In this work, we propose to overcome these two shortcomings by a Bayesian recurrent neural network model consisting of Bayesian-neural-network-based policy model and known physical model of the scenario. Bayesian neural network can ensemble complicated output distribution, enabling rich family of trajectory distribution. The embedded physical model ensures feasibility of the distribution. Moreover, the adopted gradient-based training method allows direct optimization for better performance in long prediction horizon. Furthermore, a particle-filter-based parameter adaptation algorithm is designed to adapt the policy Bayesian neural network to the predicted target online. Effectiveness of the proposed methods is verified with a toy example with multi-modal stochastic feedback gain and naturalistic car following data.
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

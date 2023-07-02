---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Intention-aware Long Horizon Trajectory Prediction of Surrounding Vehicles using Dual LSTM Networks"
authors:
  - Long Xin
  - Pin Wang
  - Ching-Yao Chan
  - Jianyu Chen
  - Shengbo Eben Li
  - Bo Cheng
date: 2018-10-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-10-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Transportation Systems Conference* (**ITSC**), 2018
# publication_short: In *IROS 2022*

abstract: As autonomous vehicles (AVs) need to interact with other road users, it is of importance to comprehensively understand the dynamic traffic environment, especially the future possible trajectories of surrounding vehicles. This paper presents an algorithm for long-horizon trajectory prediction of surrounding vehicles using a dual long short term memory (LSTM) network, which is capable of effectively improving prediction accuracy in strongly interactive driving environments. In contrast to traditional approaches which require trajectory matching and manual feature selection, this method can automatically learn high-level spatial-temporal features of driver behaviors from naturalistic driving data through sequence learning. By employing two blocks of LSTMs, the proposed method feeds the sequential trajectory to the first LSTM for driver intention recognition as an intermediate indicator, which is immediately followed by a second LSTM for future trajectory prediction. Test results from real-world highway driving data show that the proposed method can, in comparison to state-of-art methods, output more accurate and reasonable estimate of different future trajectories over 5s time horizon with root mean square error (RMSE) for longitudinal and lateral prediction less than 5.77m and 0.49m, respectively.
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

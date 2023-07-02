---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Autonomous Driving Motion Planning With Constrained Iterative LQR"
authors:
  - Jianyu Chen
  - Wei Zhan
  - Masayoshi Tomizuka
date: 2019-02-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Vehicles* (**T-IV**), 2019
# publication_short: In *IROS 2022*

abstract: Motion planning is a core technique for autonomous driving. Nowadays, there still exists a lot of challenges in motion planning for autonomous driving in complicated environments due to：1) the need of both spatial and temporal planning in highly dynamic environments; 2) nonlinear vehicle dynamic models and non-convex collision avoidance constraints; and 3) the need of high computation efficiency for real-time implementation. Iterative linear quadratic regulator (ILQR) is an algorithm to solve the optimal control problem with nonlinear system very efficiently. However, it can not deal with constraints. In this paper, the constrained iterative LQR (CILQR) is proposed to efficiently solve the optimal control problem with nonlinear system dynamics and general form of constraints. An autonomous driving motion planning problem is then formulated and solved using CILQR. Simulation case studies show the capability of the CILQR algorithm to solve these kind of problems and the computation efficiency of CILQR is shown to be much higher than the standard SQP solver.
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

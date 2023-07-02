---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Constrained Iterative LQG for Real-Time Chance-Constrained Gaussian Belief Space Planning"
authors:
  - Jianyu Chen
  - Yutaka Shimizu
  - Liting Sun
  - Masayoshi Tomizuka
  - Wei Zhan
date: 2021-10-25T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-25T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems* (**IROS**), 2021
# publication_short: In *IROS 2022*

abstract: Motion planning under uncertainty is of significant importance for safety-critical systems such as autonomous vehicles. Such systems have to satisfy necessary constraints (e.g., collision avoidance) with potential uncertainties coming from either disturbed system dynamics or noisy sensor measurements. However, existing motion planning methods cannot efficiently find the robust optimal solutions under general nonlinear and non-convex settings. In this paper, we formulate such problem as chance-constrained Gaussian belief space planning and propose the constrained iterative Linear Quadratic Gaussian (CILQG) algorithm as a real-time solution. In this algorithm, we iteratively calculate a Gaussian approximation of the belief and transform the chance-constraints. We evaluate the effectiveness of our method in simulations of autonomous driving planning tasks with static and dynamic obstacles. Results show that CILQG can handle uncertainties more appropriately and has faster computation time than baseline methods.
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

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Motion Planning for Autonomous Driving With Extended Constrained Iterative LQR"
authors:
  - Yutaka Shimizu
  - Wei Zhan
  - Liting Sun
  - Jianyu Chen
  - Shinpei Kato
  - Masayoshi Tomizuka
date: 2020-10-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Dynamic Systems and Control Conference* (**DSCC**), 2020
# publication_short: In *IROS 2022*

abstract: Autonomous driving planning is a challenging problem when the environment is complicated. It is difficult for the planner to find a good trajectory that navigates autonomous cars safely with crowded surrounding vehicles. To solve this complicated problem, a fast algorithm that generates a high-quality, safe trajectory is necessary. Constrained Iterative Linear Quadratic Regulator (CILQR) is appropriate for this problem, and it successfully generates the required trajectory in realtime. However, CILQR has some deficiencies. Firstly, CILQR uses logarithmic barrier functions for hard constraints, which will cause numerical problems when the initial trajectory is infeasible. Secondly, the convergence speed is slowed with a bad initial trajectory, which might violate the real-time requirements. To address these problems, we propose the extended CILQR by adding two new features. The first one is using relaxed logarithmic barrier functions instead of the standard logarithmic barrier function to prevent numerical issues. The other one is adding an efficient initial trajectory creator to generate a good initial trajectory. Moreover, this initial trajectory helps CILQR to converge to a desired local optimum. These new features extend CILQR’s usage to more practical autonomous driving applications. Simulation results show that our algorithm is effective in challenging driving environments.
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

url_pdf: https://proceedings.neurips.cc/paper/2021/file/4ebccfb3e317c7789f04f7a558df4537-Paper.pdf
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

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Policy-Iteration-Based Finite-Horizon Approximate Dynamic Programming for Continuous-Time Nonlinear Optimal Control"
authors:
  - Ziyu Lin
  - Jingliang Duan
  - Shengbo Eben Li
  - Haitong Ma
  - Jie Li
  - Jianyu Chen
  - Bo Cheng
  - Jun Ma
date: 2022-12-10T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-10T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems* (**TNNLS**), 2022
# publication_short: In *IROS 2022*

abstract: The Hamilton–Jacobi–Bellman (HJB) equation serves as the necessary and sufficient condition for the optimal solution to the continuous-time (CT) optimal control problem (OCP). Compared with the infinite-horizon HJB equation, the solving of the finite-horizon (FH) HJB equation has been a long-standing challenge, because the partial time derivative of the value function is involved as an additional unknown term. To address this problem, this study first-time bridges the link between the partial time derivative and the terminal-time utility function, and thus it facilitates the use of the policy iteration (PI) technique to solve the CT FH OCPs. Based on this key finding, the FH approximate dynamic programming (ADP) algorithm is proposed leveraging an actor–critic framework. It is shown that the algorithm exhibits important properties in terms of convergence and optimality. Rather importantly, with the use of multilayer neural networks (NNs) in the actor–critic architecture, the algorithm is suitable for CT FH OCPs toward more general nonlinear and complex systems. Finally, the effectiveness of the proposed algorithm is demonstrated by conducting a series of simulations on both a linear quadratic regulator (LQR) problem and a nonlinear vehicle tracking problem.
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

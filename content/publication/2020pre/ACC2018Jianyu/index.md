---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "FOAD: Fast Optimization-based Autonomous Driving Motion Planner"
authors:
  - Jianyu Chen
  - Changliu Liu
  - Masayoshi Tomizuka
date: 2018-09-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-09-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Annual American Control Conference* (**ACC**), 2018
# publication_short: In *IROS 2022*

abstract: Motion planning is one of the core modules for autonomous driving. Among the current motion planning techniques, optimization-based methods have unique advantages since they allow planning in continuous space and they can evaluate multiple objectives (such as hard constraints) in one formulation. However, it is hard to implement optimization-based methods in real-time in complicated environments due to 1) high computational complexity as the optimization problems are usually non-convex; and 2) difficulty to guarantee closed-loop performance because the low level trajectory tracking controller cannot perform perfect tracking. To solve the first challenge, convex feasible set algorithm (CFS) has been proposed for real time non-convex optimization. To solve the second challenge, a fast optimization-based autonomous driving motion planner (FOAD) is proposed in this paper which implements a soft constrained convex feasible set algorithm (SCCFS) as an enhanced version of CFS. The concept of closed-loop smoothness is defined and analyzed in this paper. Simulations and real vehicle experiments verify the efficiency and capability of the planner.
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

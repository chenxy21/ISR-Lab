---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Spatially-Partitioned Environmental Representation and Planning Architecture for On-Road Autonomous Driving"
authors:
  - Wei Zhan
  - Jianyu Chen
  - Ching-Yao Chan
  - Changliu Liu
  - Masayoshi Tomizuka
date: 2017-07-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2017-07-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Vehicles Symposium* (**IV**), 2017
# publication_short: In *IROS 2022*

abstract: Conventional layered planning architecture temporally partitions the spatiotemporal motion planning by the path and speed, which is not suitable for lane change and overtaking scenarios with moving obstacles. In this paper, we propose to spatially partition the motion planning by longitudinal and lateral motions along the rough reference path in the Frenét Frame, which makes it possible to create linearized safety constraints for each layer in a variety of on-road driving scenarios. A generic environmental representation methodology is proposed with three topological elements and corresponding longitudinal constraints to compose all driving scenarios mentioned in this paper according to the overlap between the potential path of the autonomous vehicle and predicted path of other road users. Planners combining A* search and quadratic programming (QP) are designed to plan both rough long-term longitudinal motions and short-term trajectories to exploit the advantages of both search-based and optimization-based methods. Limits of vehicle kinematics and dynamics are considered in the planners to handle extreme cases. Simulation results show that the proposed framework can plan collision-free motions with high driving quality under complicated scenarios and emergency situations.
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

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Enable Faster and Smoother Spatio-Temporal Trajectory Planning for Autonomous Vehicles in Constrained Dynamic Environment"
authors:
  - Long Xin
  - Yiting Kong
  - Shengbo Eben Li
  - Jianyu Chen
  - Yang Guan
  - Masayoshi Tomizuka
  - Bo Cheng
date: 2021-04-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Institution of Mechanical Engineers, Part D：Journal of Automobile Engineering*, 2021
# publication_short: In *IROS 2022*

abstract: Trajectory planning is of vital importance to decision-making for autonomous vehicles. Currently, there are three popular classes of cost-based trajectory planning methods -- sampling-based, graph-search-based, and optimization-based. However, each of them has its own shortcomings, for example, high computational expense for sampling-based methods, low resolution for graph-search-based methods, and lack of global awareness for optimization-based methods. It leads to one of the challenges for trajectory planning for autonomous vehicles, which is improving planning efficiency while guaranteeing model feasibility. Therefore, this paper proposes a hybrid planning framework composed of two modules, which preserves the strength of both graph-search-based methods and optimization-based methods, thus enabling faster and smoother spatio-temporal trajectory planning in constrained dynamic environment. The proposed method first constructs spatio-temporal driving space based on directed acyclic graph and efficiently searches a spatio-temporal trajectory using the improved A* algorithm. Then taking the search result as reference, locally convex feasible driving area is designed and model predictive control is applied to further optimize the trajectory with a comprehensive consideration of vehicle kinematics and moving obstacles. Results simulated in four different scenarios all demonstrated feasible trajectories without emergency stop or abrupt steering change, which is kinematic-smooth to follow. Moreover, the average planning time was 31 ms, which only took 59.05%, 18.87%, and 0.69%, respectively, of that consumed by other state-of-the-art trajectory planning methods, namely, maximum interaction defensive policy, sampling-based method with iterative optimizations, and Graph-search-based method with Dynamic Programming.
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

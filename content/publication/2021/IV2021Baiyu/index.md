---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Separated Proportional-Integral Lagrangian for Chance Constrained Reinforcement Learning"
authors:
  - Baiyu Peng
  - Yao Mu
  - Jingliang Duan
  - Yang Guan
  - Shengbo Eben Li
  - Jianyu Chen
date: 2021-10-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Vehicles Symposium* (**IV**), 2021 (**Best Student Paper Award Finalists**)
# publication_short: In *IROS 2022*

abstract: Safety is essential for reinforcement learning (RL) applied in real-world tasks like autonomous driving. Imposing chance constraints (or probabilistic constraints) is a suitable way to enhance RL safety under model uncertainty. Existing chance constrained RL methods like the penalty methods and the Lagrangian methods either exhibit periodic oscillations or learn an over-conservative or unsafe policy. In this paper, we address these shortcomings by elegantly combining these two methods and propose a separated proportional-integral Lagrangian (SPIL) algorithm. We first rewrite penalty methods as optimizing safe probability according to the proportional value of constraint violation, and Lagrangian methods as optimizing according to the integral value of the violation. Then we propose to add up both the integral and proportion values to optimize the policy, with an integral separation technique to limit the integral value within a reasonable range. Besides, the gradient of policy is computed in a model-based paradigm to accelerate training. The proposed method is proved to reduce oscillations and conservatism while ensuring safety by a car-following experiment.
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

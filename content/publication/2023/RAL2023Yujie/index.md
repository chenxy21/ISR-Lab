---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Model-Free Safe Reinforcement Learning through Neural Barrier Certificate"
authors:
  - Yujie Yang
  - Yuxuan Jiang
  - Yichen Liu
  - Jianyu Chen
  - Shengbo Eben Li
date: 2023-01-04T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-04T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters* (**RAL**), 2023
# publication_short: In *IROS 2022*

abstract: Safety is a critical concern when applying rein- forcement learning (RL) to real-world control tasks. However, existing safe RL works either only consider expected safety constraint violations and fail to maintain safety guarantees, or use safety certificate tools borrowed from safe control theory, which relies on analytic system models. This paper proposes a model-free safe RL algorithm with neural barrier certificate under stepwise state constraint setting. The barrier certificate is learned in a model-free manner by minimizing the violations of appropriate barrier properties on transition data collected by the policy. We extend the single-step invariant property of the barrier certificate to a multi-step version and construct the corresponding multi-step invariant loss. This loss balances the bias and variance of the barrier certificate and enhances both the safety and performance of the policy. We optimize the policy in a model-free manner by introducing an importance sampling weight in the constraint of the multi-step invariant property. We test our algorithm on multiple problems, including classic control tasks, robot collision avoidance, and autonomous driving. Results show that our algorithm achieves near-zero constraint violations and high performance compared to the baselines. Moreover, the learned barrier certificates successfully identify the feasible regions on multiple tasks.
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

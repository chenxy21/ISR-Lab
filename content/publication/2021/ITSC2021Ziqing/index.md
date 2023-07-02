---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Belief State Separated Reinforcement Learning for Autonomous Vehicle Decision Making under Uncertainty"
authors:
  - Ziqing Gu
  - Yujie Yang
  - Jingliang Duan
  - Shengbo Eben Li
  - Jianyu Chen
  - Wenhan Cao
  - Sifa Zheng
date: 2021-11-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-11-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Intelligent Transportation Systems Conference* (**ITSC**), 2021
# publication_short: In *IROS 2022*

abstract: In autonomous driving, the ego vehicle and its surrounding traffic environments always have uncertainties like parameter and structural errors, behavior randomness of road users, etc. Furthermore, environmental sensors are noisy or even biased. This problem can be formulated as a partially observable Markov decision process. Existing methods lack a good representation of historical information, making it very challenging to find an optimal policy. This paper proposes a belief state separated reinforcement learning (RL) algorithm for decision-making of autonomous driving in uncertain environments. We extend the separation principle from linear Gaussian systems to general nonlinear stochastic environments, where the belief state, defined as the posterior distribution of the true state, is found to be a sufficient statistic of historical information. This belief state is estimated by action-enhanced variational inference from historical information and is proved to satisfy the Markovian property, thus allowing us to obtain the optimal policy using traditional RL algorithms for Markov decision processes. The policy gradient of a task-specific prior model is mixed with that of the interaction data to improve learning performance. The proposed algorithm is evaluated in a multi-lane autonomous driving task, where the surrounding vehicles are subject to behavior uncertainty and observation noise. The simulation results show that compared with existing RL algorithms, the proposed method can achieve a higher average return with better driving performance.
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

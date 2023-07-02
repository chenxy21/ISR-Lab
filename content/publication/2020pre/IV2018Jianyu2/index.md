---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Deep Hierarchical Reinforcement Learning for Autonomous Driving with Distinct Behaviors"
authors:
  - Jianyu Chen
  - Zining Wang
  - Masayoshi Tomizuka
date: 2018-07-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-07-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Intelligent Vehicles Symposium* (**IV**), 2018
# publication_short: In *IROS 2022*

abstract: Deep reinforcement learning has achieved great progress recently in domains such as learning to play Atari games from raw pixel input. The model-free characteristics of reinforcement learning free us from hand-encoding complex policies. However, for real world tasks such as autonomous driving, there are some complex sequential decision making processes that contain distinct behaviors. Due to the delayed rewards and the averaged gradient, it is pretty difficult for a flat deep reinforcement learning algorithm to learn a good policy. In this paper, we design a hierarchical neural network policy and propose a hierarchical policy gradient method to train the network with the semi markov decision process (SMDP) temporal abstraction formulation. We apply this method to a traffic light passing scenario in autonomous driving, where the vehicle has two distinct behaviors (e.g., pass and stop) and its primitive actions (e.g., acceleration) should follow the corresponding behavior. We show via simulation that our method is able to select correct decision and acts appropriately when the traffic light turns yellow. On the contrary, the flat reinforcement learning algorithm is not able to achieve a good performance and exhibits a large variance. Furthermore, the trained neural network modules are reusable in the future to cover more scenarios.
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

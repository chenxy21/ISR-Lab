---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Interpretable End-to-End Urban Autonomous Driving with Latent Deep Reinforcement Learning"
authors:
  - Jianyu Chen
  - Shengbo Eben Li
  - Masayoshi Tomizuka
date: 2021-03-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Transportation Systems* (**T-ITS**), 2021
# publication_short: In *IROS 2022*

abstract: Unlike popular modularized framework, end-to-end autonomous driving seeks to solve the perception, decision and control problems in an integrated way, which can be more adapt- ing to new scenarios and easier to generalize at scale. However, existing end-to-end approaches are often lack of interpretability, and can only deal with simple driving tasks like lane keeping. In this article, we propose an interpretable deep reinforcement learning method for end-to-end autonomous driving, which is able to handle complex urban scenarios. A sequential latent environment model is introduced and learned jointly with the reinforcement learning process. With this latent model, a seman- tic birdeye mask can be generated, which is enforced to connect with certain intermediate properties in today’s modularized framework for the purpose of explaining the behaviors of learned policy. The latent space also significantly reduces the sample complexity of reinforcement learning. Comparison tests in a realistic driving simulator show that the performance of our method in urban scenarios with crowded surrounding vehicles dominates many baselines including DQN, DDPG, TD3 and SAC. Moreover, through masked outputs, the learned model is able to provide a better explanation of how the car reasons about the driving environment.
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

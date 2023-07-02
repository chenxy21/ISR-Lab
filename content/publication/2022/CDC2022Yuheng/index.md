---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Performance-Driven Controller Tuning via Derivative-Free Reinforcement Learning"
authors:
  - Yuheng Lei
  - Jianyu Chen
  - Shengbo Eben Li
  - Sifa Zheng
date: 2022-06-10T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-10T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Decision and Control* (**CDC**), 2022
# publication_short: In *IROS 2022*

abstract: Choosing an appropriate parameter set for the designed controller is critical for the final performance but usually requires a tedious and careful tuning process, which implies a strong need for automatic tuning methods. However, among existing methods, derivative-free ones suffer from poor scalability or low efficiency, while gradient-based ones are often unavailable due to possibly non-differentiable controller structure. To resolve the issues, we tackle the controller tuning problem using a novel derivative-free reinforcement learning framework, which integrates derivative-free policy updates into the state-of-the-art actor-critic RL architecture to achieve high versatility and efficiency. To demonstrate the framework's efficacy, we conduct numerical experiments on two concrete examples from autonomous driving, namely, adaptive cruise control with PID controller and trajectory tracking with MPC controller. Experimental results show that the proposed method outperforms several popular baselines and highlight its strong potential for automatic controller tuning. 

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

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Contact-Safe Reinforcement Learning Framework for Contact-Rich Robot Manipulation"
authors:
  - Xiang Zhu
  - Shucheng Kang
  - Jianyu Chen
date: 2022-06-30T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-30T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems* (**IROS**), 2022
# publication_short: In *IROS 2022*

abstract: Reinforcement learning shows great potential to solve complex contact-rich robot manipulation tasks. However, the safety of using RL in the real world is a crucial problem, since unexpected dangerous collisions might happen when the RL policy is imperfect during training or in unseen scenar- ios. In this paper, we propose a contact-safe reinforcement learning framework for contact-rich robot manipulation, which maintains safety in both the task space and joint space. When the RL policy causes unexpected collisions between the robot arm and the environment, our framework is able to immediately detect the collision and ensure the contact force to be small. Furthermore, the end-effector is enforced to perform contact-rich tasks compliantly, while keeping robust to external disturbances. We train the RL policy in simulation and transfer to the real robot. Real world experiments on robot wiping tasks show that our method is able to keep the contact force small both in task space and joint space even when the policy is under unseen scenario with unexpected collision, while rejecting the disturbances on the main task.

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

url_pdf: https://arxiv.org/pdf/2207.13438.pdf
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

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Joint Synthesis of Safety Certificate and Safe Control Policy using Constrained Reinforcement Learning"
authors:
  - Haitong Ma
  - Changliu Liu
  - Shengbo Eben Li
  - Sifa Zheng
  - Jianyu Chen
date: 2022-06-05T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-05T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Annual Conference on Learning for Dynamics and Control* (**L4DC**), 2022 (**Best Paper Award Finalists**)
# publication_short: In *IROS 2022*

abstract: Safety is the major consideration in controlling complex dynamical systems using reinforcement learning (RL), where the safety certificates can provide provable safety guarantees. A valid safety certificate is an energy function indicating that safe states are with low energy, and there exists a corresponding safe control policy that allows the energy function to always dissipate. The safety certificates and the safe control policies are closely related to each other and both challenging to synthesize. Therefore, existing learning-based studies treat either of them as prior knowledge to learn the other, limiting their applicability to general systems with unknown dynamics. This paper proposes a novel approach that simultaneously synthesizes the energy-function-based safety certificates and learns the safe control policies with constrained reinforcement learning (CRL). We do not rely on prior knowledge about either a prior control law or a perfect safety certificate. In particular, we formulate a loss function to optimize the safety certificate parameters by minimizing the occurrence of energy increases. By adding this optimization procedure as an outer loop to the Lagrangian-based CRL, we jointly update the policy and safety certificate parameters, and prove that they will converge to their respective local optima, the optimal safe policies and valid safety certificates. Finally, we evaluate our algorithms on multiple safety-critical benchmark environments. The results show that the proposed algorithm learns solidly safe policies with no constraint violation. The validity, or feasibility of synthesized safety certificates is also verified numerically.
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

url_pdf: https://proceedings.mlr.press/v168/ma22a/ma22a.pdf
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

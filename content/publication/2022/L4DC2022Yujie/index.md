---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning POMDP Models with Similarity Space Regularization: a Linear Gaussian Case Study"
authors:
  - Yujie Yang
  - Jianyu Chen
  - Shengbo Li
date: 2022-06-04T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-06-04T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Annual Conference on Learning for Dynamics and Control* (**L4DC**), 2022
# publication_short: In *IROS 2022*

abstract: Partially observable Markov decision process (POMDP) is a principled framework for sequential decision making and control under uncertainty. Classical POMDP methods assume known system models, while in real-world applications, the true models are usually unknown. Recent researches propose learning POMDP models from the observation sequences rolled out by the true system using maximum likelihood estimation (MLE). However, we find that such methods usually fail to find a desirable solution. This paper makes a profound study of the POMDP model learning problem, focusing on the linear Gaussian case. We show the objective of MLE is a high-order polynomial function, which makes it easy to get stuck in local optima. We then prove that the global optimal models are not unique and constitute a similarity space of the true model. Based on this view, we propose Similarity Space Regularization (SimReg), an algorithm that smooths out the local optima but keeps all the global optima. Experiments show that given only a biased prior model, our algorithm achieves a higher log-likelihood, more accurate observation reconstruction and state estimation compared with the MLE-based method.
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

url_pdf: https://proceedings.mlr.press/v168/yang22a/yang22a.pdf
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

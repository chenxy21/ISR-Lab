---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learn to Grasp with Less Supervision: A Data-Efficient Maximum Likelihood Grasp Sampling Loss"
authors:
  - Xinghao Zhu
  - Yefan Zhou
  - Yongxiang Fan
  - Lingfeng Sun
  - Jianyu Chen
  - Masayoshi Tomizuka
date: 2022-05-15T16:30:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-15T16:30:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Robotics and Automation* (**ICRA**), 2022
# publication_short: In *IROS 2022*

abstract: Robotic grasping for a diverse set of objects is essential in many robot manipulation tasks. One promising approach is to learn deep grasping models from large training datasets of object images and grasp labels. However, empirical grasping datasets are typically sparsely labeled (i.e., a small number of successful grasp labels**Labels refer to marking the image to indicate a successful robotic grasp. in each image). The data sparsity issue can lead to insufficient supervision and false-negative labels, and thus results in poor learning results. This paper proposes a Maximum Likelihood Grasp Sampling Loss (MLGSL) to tackle the data sparsity issue. The proposed method supposes that successful grasps are stochastically sampled from the predicted grasp distribution and maximizes the observing likelihood. MLGSL is utilized for training a fully convolutional network that generates thousands of grasps simultaneously. Training results suggest that models based on MLGSL can learn to grasp with datasets composing of 2 labels per image. Compared to previous works, which require training datasets of 16 labels per image, MLGSL is 8× more data-efficient. Meanwhile, physical robot experiments demonstrate an equivalent performance at a 90.7% grasp success rate on household objects. Codes and videos are available at [1].

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

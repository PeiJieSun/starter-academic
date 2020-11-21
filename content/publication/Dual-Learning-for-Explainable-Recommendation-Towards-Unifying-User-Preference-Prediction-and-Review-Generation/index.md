---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Dual Learning for Explainable Recommendation Towards Unifying User Preference Prediction and Review Generation"
authors: [Peijie Sun, Le Wu, Kun Zhang, Yanjie Fu, Richang Hong, Meng Wang]
date: 2020-04-20T19:43:41+08:00
doi: "https://doi.org/10.1145/3366423.3380164"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-21T19:43:41+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "WWW 2020"
publication_short: "WWW 2020"

abstract: "In many recommender systems, users express item opinions through two kinds of behaviors: giving preferences and writing detailed reviews. As both kinds of behaviors reflect users’ assessment of items, review enhanced recommender systems leverage these two kinds of user behaviors to boost recommendation performance. On the one hand, researchers proposed to better model the user and item embeddings with additional review information for enhancing preference prediction accuracy. On the other hand, some recent works focused on automatically generating item reviews for recommendation explanations with related user and item embeddings. We argue that, while the task of preference prediction with the accuracy goal is well recognized in the community, the task of generating reviews for explainable recommendation is also important to gain user trust and increase conversion rate. Some preliminary attempts have considered jointly modeling these two tasks, with the user and item embeddings are shared. These studies empirically showed that these two tasks are correlated, and jointly modeling them would benefit the performance of both tasks. In this paper, we make a further study of unifying these two tasks for explainable recommendation. Instead of simply correlating these two tasks with shared user and item embeddings, we argue that these two tasks are presented in dual forms. In other words, the input of the primal preference prediction task p(R|C) is exactly the output of the dual review generation task p(C|R), with R and C denote the preference value space and review space. Therefore, we could explicitly model the probabilistic correlation between these two dual tasks with p(R, C)=p(R|C)p(C)=p(C|R)p(R). We design a unified dual framework of how to inject the probabilistic duality of the two tasks in the training stage. Furthermore, as the detailed preference and review information are not available for each user-item pair in the test stage, we propose a transfer learning based model for preference prediction and review generation. Finally, extensive experimental results on two real-world datasets clearly show the effectiveness of our proposed model for both user preference prediction and review generation."

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

url_pdf: https://app.box.com/s/7kj6k40r0ik0jmb2r97qkhnwt1tjsv0j
url_code: https://github.com/www772/www2020_paper_772
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

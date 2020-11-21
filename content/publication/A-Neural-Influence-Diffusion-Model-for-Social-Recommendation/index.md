---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Neural Influence Diffusion Model for Social Recommendation"
authors: [Le Wu, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang, Meng Wang]
date: 2019-07-21T19:41:08+08:00
doi: "https://doi.org/10.1145/3331184.3331214"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-21T19:41:08+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "SIGIR 2019"
publication_short: "SIGIR 2019"

abstract: "Precise user and item embedding learning is the key to building a successful recommender system. Traditionally, Collaborative Filtering (CF) provides a way to learn user and item embeddings from the user-item interaction history. However, the performance is limited due to the sparseness of user behavior data. With the emergence of online social networks, social recommender systems have been proposed to utilize each user’s local neighbors’ preferences to alleviate the data sparsity for better user embedding modeling. We argue that, for each user of a social platform, her potential embedding is influenced by her trusted users, with these trusted users are influenced by the trusted users’ social connections. As social influence recursively propagates and diffuses in the social network, each user’s interests change in the recursive process. Nevertheless, the current social recommendation models simply developed static models by leveraging the local neighbors of each user without simulating the recursive diffusion in the global social network, leading to suboptimal recommendation performance. In this paper, we propose a deep influence propagation model to stimulate how users are influenced by the recursive social diffusion process for social recommendation. For each user, the diffusion process starts with an initial embedding that fuses the related features and a free user latent vector that captures the latent behavior preference. The key idea of our proposed model is that we design a layer-wise influence propagation structure to model how users’ latent embeddings evolve as the social diffusion process continues. We further show that our proposed model is general and could be applied when the user (item) attributes or the social network structure is not available. Finally, extensive experimental results on two real-world datasets clearly show the effectiveness of our proposed model, with more than 13% performance improvements over the best baselines for top-10 recommendation on the two datasets."

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

url_pdf: https://app.box.com/s/svgrucstfa5y6ng9xybunbmrpddxdt79
url_code: https://github.com/PeiJieSun/diffnet
url_dataset:
url_poster: https://app.box.com/s/49rmh3xh0t2o1jad17sgneyegji3yo2q
url_project:
url_slides: https://app.box.com/s/60ybnf0brv68s5vcz651a0p40frxtxyp
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

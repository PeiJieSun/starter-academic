---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Attentive Recurrent Social Recommendation"
authors: [Peijie Sun, Le Wu, Meng Wang]
date: 2018
doi: "https://doi.org/10.1145/3209978.3210023"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-20T19:24:37+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "SIGIR 2018"
publication_short: "SIGIR"

abstract: "Collaborative Filtering (CF) is one of the most popular techniques for building recommender systems. To alleviate the data sparsity issue in CF, social recommendation has emerged by leveraging social influence among users for better recommendation performance. In these systems, uses’ preferences over time are determined by their temporal dynamic interests as well as the general static interests. In the meantime, the complex interplay between users’ internal interests and the social influence from the social network drives the evolution of users’ preferences over time. Nevertheless, traditional approaches either neglected the social network structure for temporal recommendation or assumed a static social influence strength for static social recommendation. Thus, the problem of how to leverage social influence to enhance temporal social recommendation performance remains pretty much open. To this end, in this paper, we present an attentive recurrent network based approach for temporal social recommendation. In the proposed approach, we model users’ complex dynamic and general static preferences over time by fusing social influence among users with two attention networks. Specifically, in the dynamic preference modeling process, we design a dynamic social aware recurrent neural network to capture users’ complex latent interests over time, where a temporal attention network is proposed to learn the temporal social influence over time. In the general static preference modeling process, we characterize each user’s static interest by introducing a static social attention network to model the stationary social influence among users. The output of the dynamic preferences and the static pref- erences are combined together in a unified end-to-end framework for the temporal social recommendation task. Finally, experimental results on two real-world datasets clearly show the superiority of our proposed model compared to the baselines."

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

url_pdf:https://app.box.com/s/gboxhz7kcjmi0w7zc451cqqoleaanpcl
url_code:
url_dataset:
url_poster:https://app.box.com/s/t7hzalnvpxyl3p3gi9v21a2gon0o73h5
url_project:
url_slides:https://app.box.com/s/r26esy90svl17bfpgg09b68kntlo6h3q
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

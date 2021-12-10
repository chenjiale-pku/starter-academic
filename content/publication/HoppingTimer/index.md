---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "HoppingTimer: A Near-optimal Framework for Basic Estimation of Data Streams in Hopping Windows"
authors: [Kaicheng Yang, Jianyu Wu, Pu Yi, Jiale Chen, Cheng Chen, Tong Yang, Bin Cui]
date: 2020-06-01T00:00:00+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-01T00:00:00+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In high-speed data streams, recent items are often much more significant than outdated ones. Therefore, basic estimation of data streams in hopping windows is an important topic. Basic estimation tasks include cardinality estimation and membership query. There are three classic algorithms for basic tasks in fixed windows. The design goal of this paper is to devise a generic and near-optimal framework to adapt them to hopping windows. In this paper, we propose the HoppingTimer, a generic and near-optimal framework which can adapt fixed-window
algorithms to time-based and count-based hopping windows for basic tasks. The key idea of HoppingTimer is to use hopping timestamps and local cleaning to clean outdated items. We apply HoppingTimer to three algorithms for basic tasks. Experimental results show that HoppingTimer is near-optimal in hopping windows, and achieves false positive rate about 1000 times lower than the state-of-the-art when using metrics of sliding-window model. All source codes are open-sourced and released at Github."

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

url_pdf: file/HoppingTimer.pdf
url_code: https://github.com/ImananAkihc/Hopping-Timer
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
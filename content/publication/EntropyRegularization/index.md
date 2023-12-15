---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Entropy Regularization and Faster Decremental Matching in General Graphs"
authors: [admin, Aaron Sidford and Ta-Wei Tu]
date: 2023-12-15T00:00:00-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-12-15T00:00:00-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "We provide an algorithm that maintains, against an adaptive adversary, a (1−ε)-approximate maximum matching in n-node m-edge general (not necessarily bipartite) undirected graph undergoing edge deletions with high probability with (amortized) O(poly(ε^{−1}, log n)) time per update. We also obtain the same update time for maintaining a fractional approximate weighted matching (and hence an approximation to the value of the maximum weight matching) and an integral approximate weighted matching in dense graphs. Our unweighted result improves upon the prior state-of-the-art which includes a poly(log n)⋅2^O(ε^{-2}) update time [Assadi-Bernstein-Dudeja 2022] and an O(√m ε^{−2}) update time [Gupta-Peng 2013], and our weighted result improves upon the O(√m ε^{−O(1/ε)} log n) update time due to [Gupta-Peng 2013].
To obtain our results, we generalize a recent optimization approach to dynamic algorithms from [Jambulapati-Jin-Sidford-Tian 2022]. We show that repeatedly solving entropy-regularized optimization problems yields a lazy updating scheme for fractional decremental problems with a near-optimal number of updates. To apply this framework we develop optimization methods compatible with it and new dynamic rounding algorithms for the matching polytope."

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

url_pdf: https://arxiv.org/abs/2312.09077
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

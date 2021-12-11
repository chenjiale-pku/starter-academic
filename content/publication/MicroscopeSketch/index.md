---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MicroscopeSketch: Accurate Sliding Estimation Using Adaptive Zooming"
authors:
- Zheng Zhong$^{\star}$
- Jiale Chen$^{\star}$
- Shiqi Jiang
- Yutong Hu
- Tong Yang
- Bin Cui
- Uhlig Steve
date: 2021-02-01T00:00:00+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-01T00:00:00+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Approximate estimation of data streams provides real-time information for various applications. Estimation based on a sliding window has attracted much interest recently. The state-of-the-art approaches cannot achieve high accuracy, generality in algorithms and models, with limited memory usage, all at once. We propose MicroscopeSketch and its key technique, adaptive zooming. The key idea of adaptive zooming is to automatically zoom in or zoom out, to get a better view of the window. We theoretically analyze the error bound, the unilateral error, and the unbiased rounding error of MicroscopeSketch. We apply MicroscopeSketch to three tasks: frequency estimation, finding top-𝑘 frequent items, and finding top-𝑘 heavy changes. Compared to existing works, our experimental results show that the error of MicroscopeSketch is 363 times smaller in estimating the frequency and 15.2 smaller in finding top-𝑘 items than the existing works. All the related source code is (anonymously) provided open-source on Github."

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

url_pdf: file/MicroscopeSketch.pdf
url_code: https://github.com/MicroscopeSketch/MicroscopeSketch
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

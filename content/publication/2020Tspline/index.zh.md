---
title: "A fast T-spline fitting method based on efficient region segmentation"
authors:
- Zehong Lu
- Xin Jiang
- Guanying Huo
- Danlei Ye
- admin
- Zhiming Zheng
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computational and Applied Mathematics 39 (2), 55"
publication_short: ""

abstract: T-spline has been recently developed to represent objects of arbitrary shapes in computer-aided design, computer graphics, and reverse engineering. In fact, fitting a T-spline over a point cloud is usually ineffective by using traditional iterative fit-and-refine paradigm. In traditional T-spline least-square fitting method, all control points are recomputed in each iteration, which costs large amount of calculations. In this paper, we propose a fast T-spline fitting method based on T-mesh segmentation. The segmentation technology is introduced to identify the inactive and active region of T-mesh. Computational costs can be largely reduced since only the control points in the active part need to be recalculated in the upcoming process, while those in inactive part are kept invariant once the fitting accuracy is achieved. Classical datasets are used to validate the proposed fast fitting method, and the experimental results …

# Summary. An optional shortened abstract.

tags: []
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

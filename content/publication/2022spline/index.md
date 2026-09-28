---
title: "Scattered points interpolation with globally smooth b-spline surface using iterative knot insertion"
authors:
- Xin Jiang
- admin
- Guanying Huo
- Cheng Su
- Dong-Ming Yan
- Zhiming Zheng
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2022-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computer-Aided Design 148, 103244"
publication_short: ""

abstract: We introduce a new method to interpolate scattered 3D data points with a single B-spline surface patch which is globally smooth. Given a set of scattered 3D data points and their corresponding parametrization, our method first constructs a set α of B-spline bases using a weighted strategy, and inserts knots to the knot vectors based on α. Then, the knot insertion procedure is iterated until a set β of B-spline bases exists, which indicates the existence of the interpolation surface. Finally, by applying the fairing energy minimizing with interpolation constraints, a globally smooth B-spline surface which interpolates the data points can be produced. Experimental results demonstrate that the generated B-spline surfaces often have fewer control points than those of traditional methods, while keeping the scattered data points interpolated accurately. 

# Summary. An optional shortened abstract.

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://github.com/wangbolun300/Scattered_Points_Interpolation/blob/master/fig/BSplineInterpolation-compressed.pdf
url_code: 'https://github.com/wangbolun300/Scattered_Points_Interpolation'
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

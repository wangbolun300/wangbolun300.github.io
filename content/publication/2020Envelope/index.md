---
title: "Exact and efficient polyhedral envelope containment check"
authors:
- admin
- Teseo Schneider
- Yixin Hu
- Marco Attene
- Daniele Panozzo

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2020-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Trans. Graph. 39 (4), 114"
publication_short: ""

abstract: We introduce a new technique to check containment of a triangle within an envelope built around a given triangle mesh. While existing methods conservatively check containment within a Euclidean envelope, our approach makes use of a non-Euclidean envelope where containment can be checked both exactly and efficiently. Exactness is crucial to address major robustness issues in existing geometry processing algorithms, which we demonstrate by integrating our technique in two surface triangle remeshing algorithms and a volumetric tetrahedral meshing algorithm. We provide a quantitative comparison of our method and alternative algorithms, showing that our solution, in addition to being exact, is also more efficient. Indeed, while containment within large envelopes can be checked in a comparable time, we show that our algorithm outperforms alternative methods when the envelope becomes thin.

# Summary. An optional shortened abstract.

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://cims.nyu.edu/gcl/papers/2020-Fast-Envelope.pdf
url_code: 'https://github.com/wangbolun300/fast-envelope'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=_Vm61nlxyBI'

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

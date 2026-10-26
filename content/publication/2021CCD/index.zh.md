---
title: "A Large-scale Benchmark and an Inclusion-based Algorithm for Continuous Collision Detection"
authors:
- admin
- Zachary Ferguson
- Teseo Schneider
- Xin Jiang
- Marco Attene
- Daniele Panozzo

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Graphics (TOG) 40 (5), 1-16"
publication_short: ""

abstract: We introduce a large-scale benchmark for continuous collision detection (CCD) algorithms, composed of queries manually constructed to highlight challenging degenerate cases and automatically generated using existing simulators to cover common cases. We use the benchmark to evaluate the accuracy, correctness, and efficiency of state-of-the-art continuous collision detection algorithms, both with and without minimal separation.We discover that, despite the widespread use of CCD algorithms, existing algorithms are (1) correct but impractically slow; (2) efficient but incorrect, introducing false negatives that will lead to interpenetration; or (3) correct but over conservative, reporting a large number of false positives that might lead to inaccuracies when integrated in a simulator.By combining the seminal interval root finding algorithm introduced by Snyder in 1992 with modern predicate design techniques, we propose a simple and efficient CCD algorithm. This algorithm is competitive with state-of-the-art methods in terms of runtime while conservatively reporting the time of impact and allowing explicit tradeoff between runtime efficiency and number of false positives reported.

# Summary. An optional shortened abstract.

tags: []
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://continuous-collision-detection.github.io/tight_inclusion/
url_code: 'https://github.com/Continuous-Collision-Detection/Tight-Inclusion'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=7cRg52cWL8c'

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

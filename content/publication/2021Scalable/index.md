---
title: "Time of Impact Dataset for Continuous Collision Detection and a Scalable Conservative Algorithm"
authors:
- David Belgrod
- admin
- Zachary Ferguson
- Xin Zhao
- Marco Attene
- Daniele Panozzo
- Teseo Schneider

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2112.06300"
publication_short: ""

abstract: We introduce a large-scale benchmark for broad- and narrow-phase continuous collision detection (CCD) over linearized trajectories with exact time of impacts and use it to evaluate the accuracy, correctness, and efficiency of 13 state-of-the-art CCD algorithms. Our analysis shows that several methods exhibit problems either in efficiency or accuracy. To overcome these limitations, we introduce an algorithm for CCD designed to be scalable on modern parallel architectures and provably correct when implemented using floating point arithmetic. We integrate our algorithm within the Incremental Potential Contact solver [Li et al . 2021] and evaluate its impact on various simulation scenarios. Our approach includes a broad-phase CCD to quickly filter out primitives having disjoint bounding boxes and a narrow-phase CCD that establishes whether the remaining primitive pairs indeed collide. Our broad-phase algorithm is efficient and scalable thanks to the experimental observation that sweeping along a coordinate axis performs surprisingly well on modern parallel architectures. For narrow-phase CCD, we re-design the recently proposed interval-based algorithm of Wang et al. [2021] to work on massively parallel hardware. To foster the adoption and development of future linear CCD algorithms, and to evaluate their correctness, scalability, and overall performance, we release the dataset with analytic ground truth, the implementation of all the algorithms tested, and our testing framework.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: False

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2112.06300
url_code: 'https://github.com/Continuous-Collision-Detection/Scalable-CCD'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

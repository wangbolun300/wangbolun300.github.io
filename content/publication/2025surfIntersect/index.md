---
title: "Improving the Watertightness of Parametric Surface/Surface Intersection"
authors:
- Wang, Yuqing 
- Jia, Xiaohong
- Yang, Jieyin 
- admin
- Bo, Pengbo  
- Liu, Yang
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-07-26T00:00:00Z"
doi: "10.1111/cgf.70298"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computer Graphics Forum. 2025: e70298."
publication_short: ""

abstract: The parametric surface/surface intersection (SSI) computation serves as a fundamental component in geometric modelling kernels for computer-aided design (CAD) systems. The geometric fidelity of intersection curves—particularly whether the computed intersection loci in the two parametric domains (mathematical equation-curves) under the two surface maps agree with the true intersection curve in the modelling space—determines the watertightness of the surface trimming. Despite abundant research and industrial developments for SSI algorithms, ensuring the watertightness of the intersection remains challenging, which directly impacts the stability and reliability of the modelling systems.
In this paper, we present a practical algorithm for computing parametric SSI with gap control between the maps in the modelling space of the two mathematical equation-curves. We first analyse the topology of the two mathematical equation-curves by solving lower-dimensional systems of equations and build a graph in each domain representing the topology. Then we refine the graphs through adaptive edge subdivision and construct initial approximation of mathematical equation-curves by interpolation. A constrained optimization framework incorporating distance and tangential information is employed to improve accuracy and minimize gaps. We demonstrate the effectiveness of our algorithm through extensive experiments and comparisons with the intersection package in the open source software OCCT and the commercial engine ACIS.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
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

---
title: "Boolean Operation for CAD Models Using a Hybrid Representation"
authors:
- Yang, Yingyu 
- Jia, Xiaohong
- admin
- Yang, Jieyin 
- Xin, Shiqing  
- Yan, Dong-Ming
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-07-26T00:00:00Z"
doi: "10.1145/3730908"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Trans. Graph. 44, 4, Article 114 (July 2025), 17 pages."
publication_short: ""

abstract: Boolean operations for Boundary Representation (B-Rep) models are among the most commonly used functions in Computer Aided Design (CAD) systems. They are also one of the most delicate soft modules, with challenges arising from complex algorithmic flows and efficiency and accuracy issues, especially in extreme cases. Common issues encountered in processing complex models include low efficiency, missing results, and non-watertightness. In this paper, we propose a novel algorithm for efficient and accurate Boolean operations on B-Rep models. This is achieved by establishing a bijective mapping between B-Rep models and the corresponding triangle meshes with controllable approximation error, thus mapping B-Rep Boolean operations to mesh Boolean operations. By using conservative intersection detection on the mesh to locate all surface intersection curves and carefully handling degeneration and topology errors, we ensure that the results are consistently watertight and correct. We demonstrate the superior efficiency of the proposed method using the open-source geometry engine OCCT, the commercial engine ACIS, and the commercial software Rhino as benchmarks.
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
  preview_only: true

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

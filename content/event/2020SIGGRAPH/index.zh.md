---
title: Exact and Efficient Polyhedral Envelope Containment Predicate

event: SIGGRAPH2020
event_url: https://s2020.siggraph.org/

location: Washington, D.C. the U.S. (online)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: We introduce a new technique to check containment of a triangle within a polyhedral envelope. Our method is at the same time exact and efficient.
abstract: 'The computation of distances between surfaces is a basic building block in geometry processing. In particular, the computation of the Hausdorff distance between an individual triangle T and a triangle mesh M is often used by meshing and remeshing algorithms (eg,[Cheng et al. 2019; Hu et al. 2020, 2018]) to ensure geometric preservation up to a small distance ϵ. This distance allows algorithms to smooth out small details, fill small gaps, remove noise, and perform other operations to generate a high quality mesh, while at the same time bounding the geometrical approximation error. This bound is used, for example, in graphics applications to ensure sub pixels accuracy, or in finite element analysis to bound the error on the solution.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-08-01T13:00:00Z'
#date_end: '2020-08-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2020-08-01T13:00:00Z'

authors:
- admin
- Teseo Schneider
- Yixin Hu
- Marco Attene
- Daniele Panozzo

tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/wangbolun300/fast-envelope'
url_pdf: 'https://cims.nyu.edu/gcl/papers/2020-Fast-Envelope.pdf'
# url_slides: 'https://slideshare.net'
url_video: 'https://www.youtube.com/watch?v=_Vm61nlxyBI'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---


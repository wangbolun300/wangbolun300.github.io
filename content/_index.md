---
title: ""
date: 2022-10-24
lastmod: 2026-10-26
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black

  - block: collection
    id: papers
    content:
      title: Featured Publications
      count: 100
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 5
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 30
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      fill_image: false
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3

---

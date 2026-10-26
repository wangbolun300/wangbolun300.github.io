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
      title: 代表性论文
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
      title: 近期论文
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
      title: 学术报告
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3

---

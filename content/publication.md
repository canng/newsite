---
title: 'Publications'
date: 2025-06-16
type: landing

design:
  # Section spacing
  spacing: '2rem'

# Page sections



sections:
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3

  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

---

![cover](cover_publication.png)

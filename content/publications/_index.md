---
title: Publications
type: landing

design:
  spacing: '5rem'

sections:
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation
---

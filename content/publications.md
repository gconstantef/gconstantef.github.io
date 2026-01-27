---
title: Publications
type: landing
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
      title: All Publications
      filters:
        folders:
          - publications
        exclude_featured: false   # set to true if you DON'T want featured repeated below
    design:
      view: citation
---

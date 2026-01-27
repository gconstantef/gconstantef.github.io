---
title: 'Constante bio'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Gonzalo_Constante.pdf
      headings:
        about: About me
        education: ''
        interests: Research interests
    design:
      name:
        size: md
      background:
        gradient_mesh:
          enable: true

      avatar:
        size: large
        shape: circle
  - block: resume-experience
    content:
      username: me
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: me
  - block: resume-awards
    content:
      title: Awards
      username: me
---

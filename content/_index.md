---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-25
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: ''

  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: ''
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: 1

  - block: collection
    id: working-papers
    content:
      title: Working Papers
      subtitle: ''
      text: ''
      filters:
        folders:
          - working_paper
        exclude_featured: false
    design:
      view: citation
      columns: 1

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      subtitle: ''
      text: ''
      filters:
        folders:
          - talk
    design:
      view: card
      columns: 1
---

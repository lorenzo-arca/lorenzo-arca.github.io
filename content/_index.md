---
title: ''
summary: ''
date: 2026-01-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      # CV download disabled — original PDF contains home address.
      # To enable later, drop a redacted PDF at static/uploads/cv.pdf and uncomment:
      # button:
      #   text: Download CV
      #   url: uploads/cv.pdf
      headings:
        about: 'Biography'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research lies at the intersection of **international trade**, **spatial economics**, **labor economics**, and **environmental economics**. I am particularly interested in how firms' sourcing and location decisions interact with imperfectly competitive labor markets, and in the regional implications of trade and environmental policy. My methods combine structural modeling with administrative micro-data (matched employer–employee, customs, balance sheets).

        **Advisors:** [Ralph Ossa](https://www.econ.uzh.ch/en/people/faculty/ossa.html), [Josef Zweimüller](https://www.econ.uzh.ch/en/people/faculty/zweimueller.html), and [Armin Schmutzler](https://www.econ.uzh.ch/en/people/faculty/schmutzler.html) (University of Zurich).
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        publication_type: 'article'
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: wip
    content:
      title: Work in Progress
      filters:
        folders:
          - publications
        publication_type: 'manuscript'
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: reports
    content:
      title: Reports and Policy Work
      filters:
        folders:
          - publications
        publication_type: 'report'
        exclude_featured: false
    design:
      view: citation

  - block: resume-experience
    id: experience
    content:
      username: me

  # Other Projects — currently hidden. To show:
  #   1. Uncomment the block below.
  #   2. Remove `draft: true` from the relevant publication's index.md.
  # - block: collection
  #   id: other
  #   content:
  #     title: Other Projects
  #     filters:
  #       folders:
  #         - publications
  #       publication_type: 'other'
  #       exclude_featured: false
  #   design:
  #     view: citation

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        Email: [lorenzo.arca@econ.uzh.ch](mailto:lorenzo.arca@econ.uzh.ch)

        Drafts of any work in progress available on request.
    design:
      columns: '1'
---

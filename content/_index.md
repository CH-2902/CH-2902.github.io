---
title: ''
summary: ''
date: 2026-04-28
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download Resume
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: papers
    content:
      title: Featured Publication
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: featured-projects
    content:
      title: Featured Projects
      text: ''
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      fill_image: false

  - block: markdown
    id: contact
    content:
      title: Get in Touch
      subtitle: 'Open to AI/ML Engineer roles — Singapore-based, open to overseas.'
      text: |
        The fastest way to reach me is by email — I usually reply within a day.

        - 📧 **Email:** [limchienherlim@gmail.com](mailto:limchienherlim@gmail.com)
        - 💼 **LinkedIn:** [linkedin.com/in/limchienher](https://www.linkedin.com/in/limchienher)
        - 💻 **GitHub:** [github.com/CH-2902](https://github.com/CH-2902)
        - 📄 **Resume:** [Download PDF](uploads/resume.pdf)
    design:
      columns: '1'
---

---
title: ''
summary: ''
date: 2026-05-13
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |
        I work on trustworthy and reasoning-centric AI systems, with a current focus on reinforcement learning for large reasoning models, transparent monitoring, and interpretability.
      button:
        text: Download CV
        url: uploads/cv.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ''
      text: |-
        I am a first-year Ph.D. student at Shanghai Jiao Tong University, jointly trained with Shanghai AI Laboratory, advised by Dr. Jing Shao. I received my bachelor's degrees from Shanghai Jiao Tong University in Information Security and Mathematics and Applied Mathematics.

        My research asks how large language models can reason more effectively while remaining transparent and monitorable. Recent work spans reinforcement learning for large reasoning models, trustworthy AI, looped transformers, latent reasoning, and masked diffusion language models.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications and Reports
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
  - block: collection
    content:
      title: All Publications and Reports
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
      count: 4
    design:
      view: card
      columns: 2
  - block: collection
    id: news
    content:
      title: News
      page_type: blog
      count: 5
      filters:
        folders:
          - blog
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
---

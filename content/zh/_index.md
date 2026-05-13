---
title: ''
summary: ''
date: 2026-05-13
type: landing

sections:
  - block: markdown
    id: about
    content:
      title: 陈冠旭
      subtitle: 上海交通大学博士生 | 上海人工智能实验室联合培养
      text: |-
        我是上海交通大学博士一年级学生，与上海人工智能实验室联合培养，导师为邵婧博士。本科毕业于上海交通大学，专业为信息安全与数学与应用数学。

        我的研究关注可信大模型、大推理模型强化学习、模型透明性与可解释性、循环 Transformer 与潜在推理。

        [下载简历](/uploads/cv.pdf) · [Google Scholar](https://scholar.google.com/citations?user=2TzpwC0AAAAJ) · [GitHub](https://github.com/biuboomc)
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 代表论文与技术报告
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
  - block: collection
    content:
      title: 全部论文与报告
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: 项目
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
      title: 动态
      page_type: blog
      count: 5
      filters:
        folders:
          - blog
        exclude_featured: false
      order: desc
    design:
      view: card
---

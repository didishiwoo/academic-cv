---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: |-
        谢德晨，安徽医科大学生物医学工程专业本科生。研究聚焦于经颅电刺激（TES）、生物组织介电特性以及脑内电磁场计算建模。相关成果以第一作者在 IEEE EMBC 2025 国际会议上发表并作口头汇报，同时担任省级大创项目"智控脑阈：个性化经颅时域干涉刺激系统的研制"负责人。
      button:
        text: 下载简历
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
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: research
    content:
      title: '📚 我的科研'
      subtitle: ''
      text: |-
        我的研究聚焦于**神经工程**与**计算生物电磁学**的交叉领域，主要围绕以下三个方向：

        ### 1. 时域干涉刺激（TIS）建模
        我将磁共振电导率成像与弥散张量成像结合 NODDI 模型，构建了个性化各向异性电导率模型用于 TIS 仿真。研究发现，与传统各向同性模型相比，各向异性建模在白质区域的电场强度差异约为 **20%**，灰质和全脑差异均超过 10%。

        ### 2. 生物组织介电特性
        我在 100–4000 MHz 频段对 127 例新鲜离体甲状腺样本进行宽频介电特性测量，发现相对介电常数可显著区分恶性与正常组织（**p < 0.001**），为肿瘤分期提供了新的潜在生物标志物。

        ### 3. 神经刺激系统研制
        作为项目负责人，研制了一套四通道经颅时域干涉刺激系统，实现高精度恒流输出（误差 ≤ 1%），涵盖硬件设计、STM32 固件开发和 PySide6 上位机软件开发。

        我致力于推动无创脑刺激技术向更高精度和临床实用化方向发展。欢迎联系合作 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 代表性论文
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 最新论文
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: 学术报告
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: 最新动态
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---

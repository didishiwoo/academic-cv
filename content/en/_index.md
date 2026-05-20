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
        Dechen Xie is an undergraduate student in Biomedical Engineering at Anhui Medical University. His research focuses on transcranial electrical stimulation (TES), dielectric properties of biological tissues, and computational modeling of electromagnetic fields in the brain. He has published at IEEE EMBC 2025 and is the lead of a provincial-level innovation project on personalized temporal interference stimulation systems.
      button:
        text: Download CV
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
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research lies at the intersection of **neural engineering** and **computational bioelectromagnetics**. I focus on three main areas:

        ### 1. Temporal Interference Stimulation (TIS) Modeling
        I develop personalized anisotropic conductivity models for TIS by integrating magnetic resonance electrical conductivity tomography with diffusion tensor imaging and the NODDI model. My work reveals that anisotropic conductivity modeling yields approximately **20% differences in electric field intensity** in white matter regions compared to conventional isotropic models.

        ### 2. Dielectric Properties of Biological Tissues
        I characterize the broadband dielectric properties of fresh ex vivo thyroid tissue (100–4000 MHz) and explore their correlation with tumor staging. My findings show that the relative permittivity can significantly distinguish malignant from normal tissues (**p < 0.001**), offering a potential new biomarker for cancer diagnosis.

        ### 3. Neural Stimulation System Development
        As project lead, I developed a 4-channel temporal interference stimulation system with high-precision constant current output (≤1% error), integrating hardware design, STM32 firmware, and PySide6-based PC control software.

        I am passionate about advancing non-invasive brain stimulation techniques toward higher precision and clinical applicability. Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
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
      title: Recent Publications
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
      title: Recent Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
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

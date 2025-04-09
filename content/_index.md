---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # Original Biography Section
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  # New Projects Section
  - block: markdown
    content:
      title: "🔬 Research Projects"
      subtitle: "Selected initiatives and contributions"
      text: "Below are highlights of my research work across multiple domains."
    design:
      columns: '1'
      spacing:
        padding: ["20px", "0", "10px", "0"]

  - block: features
    content:
      items:
        - name: "Enhancing Visual Detail Perception in VLMs"
          description: |
            - Designed spectral layer for CLIP vision encoder  
            - 12.6% accuracy boost on MMVP benchmark  
            - 7.4% improvement over diffusion methods
          icon: eye
          icon_pack: fas
          image: project-vlm.jpg
        - name: "Explaining Neural Network Decisions in Go"
          description: |
            - Game-theoretical framework for AI interpretation  
            - Python algorithms for pattern extraction  
            - Discovered novel strategic patterns
          icon: gamepad
          icon_pack: fas
          image: project-go.jpg
        - name: "Course Assignment Algorithm"
          description: |
            - Hungarian-inspired matching system  
            - Optimized student preferences  
            - 'Excellent' rating at SJTU
          icon: algorithm
          icon_pack: fas
          image: project-matching.jpg
    design:
      columns: '3'
      spacing:
        padding: ["10px", "0", "20px", "0"]
      background:
        color: "rgba(240, 242, 246, 0.3)"
      card:
        css_class: "shadow-sm"
        css_style: "border-radius: 8px;"

  # Optional: Publications section (from original)
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: ["30px", "0", "20px", "0"]
---
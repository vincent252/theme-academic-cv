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

  - block: markdown
    content:
      title: '<span id="projects">Projects</span>'
      subtitle: "Research & Development"
      text: |
          ### <span style="display: inline-flex; align-items: center;">
          <img src="pic1.jpg" style="width:30px; height:30px; margin-right:8px;">
          <strong>Enhancing Visual Detail Perception in Vision-Language Models</strong>
          </span>  
          - Aimed to improve fine-grained alignment between language and vision in models like CLIP by enhancing perception of visual details.  
          - Designed a novel plug-and-play spectral layer using frequency analysis to diversify image patch embeddings.  
          - Achieved a **12.6% accuracy boost** on the MMVP benchmark and surpassed diffusion-based methods by **7.4%**.  

          ### <span style="display: inline-flex; align-items: center;">
          <img src="pic2.jpg" style="width:18px; height:18px; margin-right:8px;">
          <strong>Exploring How a Neural Network Plays the Go Game</strong>
          </span>  
          - Developed a game-theoretical framework to explain AI decision-making in Go.  
          - Identified crucial stone shapes influencing KataGo's predictions.  
          - Discovered novel strategic patterns beyond traditional human knowledge.  

          ### <span style="display: inline-flex; align-items: center;">
          <img src="pic3.jpg" style="width:18px; height:18px; margin-right:8px;">
          <strong>Research on Algorithms for Course Project Assigning</strong>
          </span>  
          - Designed a constraint-based matching algorithm inspired by the Hungarian algorithm.  
          - Optimized assignments to maximize student preferences.  
          - Received an **'Excellent'** rating in SJTU's Research Program. 
    design:
      columns: "1"  # Single column layout
      spacing:
        padding: ["30px", "0", "30px", "0"]
---
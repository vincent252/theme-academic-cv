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
        ### **Enhancing Visual Detail Perception in Vision-Language Models** 
        - Aimed to improve fine-grained alignment between language and vision in vision-language models like CLIP by enhancing the model’s ability to perceive fine-grained visual details not captured through natural language supervision.
        - Designed and integrated a novel plug-and-play spectral layer utilizing frequency analysis into the CLIP vision encoder. This layer diversified image patch token embeddings, amplifying visual detail information to improve the model’s capacity for fine-grained visual recognition.
        - Initiated the use of frequency domain transformation in deep learning model embeddings to amplify subtle visual details.
        - Achieved a 12.6% increase in CLIP model’s accuracy on the Multimodal Visual Patterns (MMVP) benchmark and surpassed diffusion-based approach by 7.4%, demonstrating a substantial improvement in visual detail perception and better alignment between language and vision modalities. 
     
        ### **Exploring How a Neural Network Plays the Go Game**  
        - Addressed the challenge of explaining AI decision-making in Go by identifying crucial stone shapes that significantly influence the KataGo value network’s predictions.
        - Contributed to developing a game-theoretical framework and implementing Python algorithms to extract stone shapes.
        - Identified patterns aligned with human knowledge and discovered novel shapes that expanded the traditional understanding of Go

        ### **Research on Algorithms for Course Project Assigning**  

        - Assigned students to projects based on their preferences under specific constraints.
        - Designed a matching algorithm inspired by the Hungarian algorithm and implemented the algorithm in Python.
        - Optimized assignments to maximize the number of students matched to their top project choices.
        - Achieved an ‘Excellent’ rating in the Participation in Research Program.
    design:
      columns: "1"  # Single column layout
      spacing:
        padding: ["30px", "0", "30px", "0"]
---
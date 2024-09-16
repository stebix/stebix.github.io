---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  
  - block: resume-awards
    content:
      title: Awards
      username: admin
      
  - block: markdown
    content:
      title: 'Detailed Skills'
      subtitle: ''
      text: |-
        ### Coding Languages
        #### 🐍 Python
        - Scientific Stack: numpy, scipy, matplotlib, sklearn, pandas, plotly
        - Machine Learning: PyTorch, jax, sklearn
        - (JIT-) Compilation: numba, Cython 
        - GPU: cupy, triton

        #### 🇯 julia
          DiffEq.jl, makie.jl, plots.jl, SciML Ecosystem
        
        #### ⌨️ Other
          MATLAB, Javascript, CUDA, Rust


        ### 🛠️ Tooling:
          Git, LaTeX, Jupyter, Bash, tmux

        ### 🌐 Infrastructure, Virtualization & Orchestration
          Linux, Docker, Proxmox, Kubernetes

        ### Natural Languages
          🇩🇪    German (native) <br>
          🇺🇸🇬🇧  English (full professional working capacity)<br>
          🇫🇷   French (elementary) <br>
          🇪🇸    Spanish (elementary)

    design:
      columns: '1'
---

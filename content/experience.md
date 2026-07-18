---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Page sections
sections:
  - block: resume-experience
    content:
      username: me  # <-- Remis sur 'me' pour faire réapparaître vos expériences
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false

  - block: markdown
    id: skills
    content:
      title: '🛠️ Skills & Hobbies'
      text: |-
        ### 💻 Programming Languages
        * **Python**
        * **MATLAB**
        * **R**
        * **Scilab / C**

        ### 📚 Libraries & Software
        * **PyTorch / TensorFlow**
        * **Scikit-learn / Pandas / Numpy**
        * **Git / GitHub**
        * **LaTeX / Markdown**
    design:
      columns: '1'

  - block: markdown
    id: languages
    content:
      title: '🗣️ Languages'
      text: |-
        * **French** (Native)
        * **English** (Professional)
        * **Spanish** (Basic / Intermediate)
    design:
      columns: '1'
---

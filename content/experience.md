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
        * **English** (Professional working proficiency, B2)
        * **Spanish** (Intermediate)
    design:
      columns: '1'

  - block: markdown
    id: courses
    content:
      title: '📚 Courses, Schools & Talks'
      text: |-
        * [**Specialized courses & summer schools**](/courses/specialized-courses/): MaLGa Summer Schools (University of Genova, 2024), RKHS for Machine Learning (BCAM, 2023), AI & Data Science training (2024–2025).
        * [**Academic presentations**](/courses/academic-presentations/): workshop talk on AEs and VAEs (BCAM, 2024) and course presentations at AIMS Rwanda (2022).
    design:
      columns: '1'
---

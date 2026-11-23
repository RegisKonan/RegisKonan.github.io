---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      title: ""
      text: |-
        **Regis Konan Marcel Djaha** is an AI Researcher specializing in the intersection of Applied Mathematics, Deep Probabilistic Modeling, and Scientific Machine Learning (SciML). He is currently pursuing an MSc in [Computational Engineering and Intelligent Systems](https://www.ehu.eus/es/web/master/master-ingenieria-computacional-sistemas-inteligentes) at the [University of the Basque Country (UPV/EHU)](https://www.ehu.eus/) (2026–2027), where he is directing his research toward the synergy between deep learning and numerical analysis in preparation for a PhD.

        Prior to this, Regis worked as a full-time Research Technician at the [Basque Center for Applied Mathematics (BCAM)](https://www.bcamath.org/) within the Statistical Machine Learning Group. His research focused on deep latent variable models, particularly Variational Autoencoders (VAEs), and their applications to both unsupervised and supervised learning tasks. He also collaborated with researchers at the [University of Oxford](https://www.ox.ac.uk/) through the [Mfano Africa program](https://www.maths.ox.ac.uk/outreach/miorpa), investigating the visibility network structure of complex multivariate time series.

        His academic background bridges rigorous foundations in mathematics, physical sciences, and modern artificial intelligence:
        * **African Master’s in Machine Intelligence (AMMI)** – [AIMS Senegal](https://aims-senegal.org/) (2023–2024)
        * **MSc in Mathematical Sciences** – [AIMS Rwanda](https://aims.ac.rw/) (2021–2022)
        * **MSc in Mechanics and Energetics (Fluid Dynamics)** – [Université Félix Houphouët-Boigny](https://w.univ-fhb.edu.ci/), Côte d'Ivoire (2018–2020)
        * **BSc in Mathematics** – [Université Félix Houphouët-Boigny](https://w.univ-fhb.edu.ci/), Côte d'Ivoire (2015–2018)

        > 🎓 **Open to PhD positions (starting 2027)** in Scientific Machine Learning, Probabilistic Deep Learning, and AI for science & engineering. [Get in touch](mailto:regiskonan056@gmail.com).

        *También puede descargar mi [🇪🇸 CV en Español (PDF)](uploads/resume_esp.pdf).*
      button:
        text: 🇬🇧 Download CV (English)
        url: uploads/resume_eng.pdf
      headings:
        about: ''
        education: "Education"
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
      title: '📚 Research'
      subtitle: 'Bridging Mathematics, Deep Learning, and Computational Engineering'
      text: |-
        Regis's research lies at the intersection of mathematical modeling, numerical analysis, and statistical machine learning. He develops robust, physics-aware, data-driven methods that combine solid theoretical foundations with modern deep learning, with particular attention to uncertainty quantification.

        ### 🧠 Core Research Pillars
        * **Scientific Machine Learning (SciML):** Physics-informed neural networks (PINNs), neural operators (FNO, DeepONet), surrogate modeling for partial differential equations (PDEs), and computational fluid dynamics (CFD).
        * **Deep Generative & Probabilistic Models:** Deep latent variable models, Variational Autoencoders (VAEs, $\beta$-VAEs), Bayesian deep learning, and representation learning.
        * **Complex Dynamical Systems:** Multivariate time-series analysis, visibility graphs, and complex network theory.

        His current MSc work at UPV/EHU, including his Master's Thesis (TFM), focuses on Scientific Machine Learning.
    design:
      columns: '1'

  - block: markdown
    id: awards
    content:
      title: '🏆 Awards & Scholarships'
      subtitle: 'Research grants and academic scholarships'
      text: |-
        * **Research Technician Grant in Statistical Machine Learning** (2023)  
          Funded by La Caixa Junior Leader — Basque Center for Applied Mathematics (BCAM), Bilbao, Spain.
        
        * **Research Grant in Mathematical Sciences** (2023)  
          Mfano Africa – Oxford Virtual Mentorship Programme — Oxford, United Kingdom.
        
        * **Full Master's Degree Scholarship — AMMI** (2023)  
          Funded by Meta (Facebook) and Google — African Master's in Machine Intelligence, Mbour, Senegal.
        
        * **Full Master's Degree Scholarship — AIMS** (2021)  
          African Institute for Mathematical Sciences — Kigali, Rwanda.
    design:
      columns: '1'

  - block: markdown
    id: certificates
    content:
      title: '📜 Certificates'
      subtitle: 'Professional certifications, workshops, and academic honors'
      text: |-
        Here is the complete list of certifications and credentials obtained throughout my academic and research journey:

        ***

        ### Data Science Workshop: From Theory to Practice
        * **Institution:** African Institute for Mathematical Sciences (AIMS) Research Innovation Centre
        * **Description:** Active participation and completion of the practical Data Science workshop focused on transitioning from theory to real-world applications.

        ***

        ### Participation in the national phase of the second edition of the CAMES Olympiad
        * **Institution:** African and Malagasy Council for Higher Education (CAMES)
        * **Description:** Participated in the national phase of the second edition of the CAMES University Olympiads, representing University Felix Houphouët-Boigny (UFHB).

        ***

        ### Virtual Mentorship Programme in Mathematical Sciences
        * **Institution:** Mfano Africa - Oxford Mathematics
        * **Description:** Completed the intensive virtual research mentorship program in mathematical sciences conducted in collaboration with Oxford University.

        ***

        ### Reproducing Kernel Hilbert Spaces for Machine Learning
        * **Institution:** Basque Center for Applied Mathematics (BCAM), Spain
        * **Description:** Certificate of completion for the advanced specialized course on the theoretical and practical foundations of Reproducing Kernel Hilbert Spaces (RKHS) applied to statistical learning.

        ***

        ### Training in Python and Scilab: Application to the study of Partial Differential Equations
        * **Institution:** Mathematical Society of Ivory Coast (SMCI) & Mathematical School of Yamoussoukro (EMY)
        * **Description:** Technical training certificate covering scientific programming in Python and Scilab, with a solid application to the study and numerical modeling of Partial Differential Equations (PDEs).
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: '📝 Publications'
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
      title: '💻 Featured Projects'
      subtitle: 'Selected open-source repositories and research implementations'
      text: ''
      filters:
        folders:
          - projects
        exclude_featured: false
    design:
      columns: '1'
      view: card
---

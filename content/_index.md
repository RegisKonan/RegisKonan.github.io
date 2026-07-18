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
      text: |-
        Regis Konan Marcel Djaha is a Data Scientist specializing in the intersection of mathematics and artificial intelligence. Beginning in September 2026, Regis will pursue an MSc in Computational Engineering and Intelligent Systems (Master KISA) at the [University of the Basque Country (UPV/EHU)](https://www.ehu.eus/), with the program running through June 2027.
    
        Before this, Regis worked as a full-time Research Technician at the [Basque Center for Applied Mathematics (BCAM)](https://www.bcamath.org/) within the Statistical Machine Learning Group. His research focused on deep latent variable models, particularly Variational Autoencoders (VAEs), and their applications to both unsupervised and supervised learning.
    
        His academic background includes an [African Master's in Machine Intelligence (AMMI)](https://aimsammi.org/) from the [African Institute for Mathematical Sciences (AIMS) Senegal](https://aims-senegal.org/) (2023–2024) and a Master's degree in Mathematical Sciences from the [African Institute for Mathematical Sciences (AIMS) Rwanda](https://aims.ac.rw/) (2021–2022). Before specializing in artificial intelligence, Regis earned a Bachelor's degree in Mathematics (2018) and a Master's degree in Mechanics and Energetics (2020) from the [Université Félix Houphouët-Boigny](https://w.univ-fhb.edu.ci/) in Côte d'Ivoire.

        In addition, he collaborated with the [University of Oxford](https://www.ox.ac.uk/) through the Mfano Africa program, researching the Visibility Network Structure of Time Series from Real-World Systems. His research interests include machine learning, probabilistic modeling, deep generative models, scientific computing, and physics-informed artificial intelligence. Regis's research interests include deep latent variable generative models (Autoencoders, Variational Autoencoders, and β-VAEs), stochastic partial differential equations (SPDEs), scientific computing, time-series analysis and complex network theory through visibility graphs, as well as fluid mechanics and computational fluid dynamics (CFD).

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
    content:
      title: '📚 My Research'
      subtitle: 'Bridging Mathematics, Deep Learning, and Computational Engineering'
      text: |-
        My research lies at the intersection of mathematical modeling and Statistical Machine Learning. I am deeply interested in developing robust, data-driven solutions by combining solid theoretical foundations with advanced deep learning frameworks.

        ### 🧠 Core Research Interests:
        * **Deep Latent Variable Models:** Investigating the theory, architecture, and applications of Autoencoders (AEs) and Variational Autoencoders (VAEs) for both unsupervised representation learning and supervised tasks.
        * **Complex Time-Series & Network Theory:** Analyzing real-world dynamical systems using horizontal and vertical visibility graphs to map complex time-series data into network structures.
        * **Physics-Informed ML & Computational Fluid Dynamics:** Leveraging my background in Partial Differential Equations (PDEs) and fluid mechanics to explore how machine learning can accelerate numerical simulations in porous media and climate science.
        * **Intelligent Systems:** Preparing to expand my work into advanced computational engineering, focusing on autonomous intelligence and generative systems.

        With my upcoming MSc at the University of the Basque Country (UPV/EHU), my goal is to further bridge advanced generative AI with scalable computational engineering methods. 

        Please feel free to reach out for collaborations! 😃
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

  - block: markdown
    id: awards
    content:
      title: '🏆 Awards & Scholarships'
      subtitle: 'Research grants and academic scholarships'
      text: |-
        * **Research Technician Grant in Statistical Machine Learning** (2023)  
          Funded by La Caixa Junior Leader (€19,188) — Basque Center for Applied Mathematics (BCAM), Bilbao, Spain.
        
        * **Research Grant in Mathematical Sciences** (2023)  
          Mfano Africa - Oxford Virtual Mentorship Programme (£230) — Oxford, United Kingdom.
        
        * **Full Master's Degree Scholarship — AMMI** (2023)  
          Funded by Facebook and Google — African Master's in Machine Intelligence, Mbour, Senegal.
        
        * **Full Master's Degree Scholarship — AIMS** (2021)  
          African Institute for Mathematical Sciences ($25,000) — Kigali, Rwanda.
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

        ### Data Science Workshop: From theory to Practice
        * **Institution:** African Institute for Mathematical Sciences (AIMS) Research Innovation Centre
        * **Description:** Active participation and completion of the practical Data Science workshop focused on transitioning from theory to real-world applications.

        ***

        ### Participation in the national phase of the second edition of the CAMES Olympiad
        * **Institution:** African and Malagasy Council for Higher Education (CAMES)
        * **Description:** Participated in the national phase of the second edition of the CAMES university Olympiads, representing University Felix Houphouët-Boigny (UFHB).

        ***

        ### Virtual Mentorship Programme in Mathematical Sciences
        * **Institution:** Mfano Africa - Oxford Mathematics
        * **Description:** Successfully completed the intensive virtual research mentorship program in mathematical sciences conducted in collaboration with Oxford University.

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
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: cta-card
    demo: true
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
        css_style: ''
---

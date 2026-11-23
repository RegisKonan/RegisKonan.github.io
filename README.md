# Regis Konan Marcel Djaha — Personal Website

**Scientific Machine Learning · Probabilistic Deep Learning**

🌐 **[regiskonan.github.io](https://regiskonan.github.io/)**

[![Website](https://img.shields.io/badge/Website-regiskonan.github.io-2a5db0?style=flat-square)](https://regiskonan.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=9HYn9mUAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--5252--759X-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0004-5252-759X)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-regisdjaha-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/regisdjaha)
[![Email](https://img.shields.io/badge/Email-regiskonan056%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:regiskonan056@gmail.com)

---

## About

I am an AI researcher working at the intersection of **applied mathematics**, **deep probabilistic modeling** and **scientific machine learning**. I am currently an MSc student in [Computational Engineering and Intelligent Systems](https://www.ehu.eus/es/web/master/master-ingenieria-computacional-sistemas-inteligentes) at the **University of the Basque Country (UPV/EHU)** (2026–2027).

Before that, I was a Research Technician in the Statistical Machine Learning group at the [Basque Center for Applied Mathematics (BCAM)](https://www.bcamath.org/), working on deep latent variable models. I also hold master's degrees from AIMS Rwanda, AMMI (AIMS Senegal) and Université Félix Houphouët-Boigny.

> 🎓 **Open to PhD positions starting in 2027** in Scientific Machine Learning, Probabilistic Deep Learning and AI for science & engineering.

## Research interests

- Scientific Machine Learning: PINNs, neural operators (FNO, DeepONet), surrogate models for PDEs
- Deep generative and probabilistic models: VAEs, β-VAEs, Bayesian deep learning
- Uncertainty quantification
- Numerical methods for PDEs and computational fluid dynamics
- Complex networks and multivariate time series

## Featured projects

| Project | Topic | Links |
|---|---|---|
| **Understanding Autoencoders & VAEs** | Effect of depth, latent dimension, prior and β on AEs/VAEs (MNIST, FashionMNIST, FreyFace) | [Code](https://github.com/RegisKonan/ae_vae_understanding) |
| **Kernel Methods for DNA Binding-Site Prediction** | SVMs and multiple spectrum kernels, 6th on the private leaderboard (67.0%) | [Report](https://github.com/RegisKonan/Kernel_Methods_report-) |
| **Darcy's Law in a 2D Porous Embankment** | Seepage through horizontal, multilayer and inclined embankments (AIMS thesis) | [Thesis](https://github.com/RegisKonan/AIMS_master_embankment) |
| **Saltwater Intrusion in Anisotropic Porous Media** | Finite element simulation (FreeFem++) of the salt wedge (UFHB thesis) | [Thesis](https://github.com/RegisKonan/UFHB_master_Fluid_mechanics) |

## Publications

- D.-D. Fangnon, A. S. Kouyim Meli, V. R. Mbingui, P. D. Negho, **R. K. M. Djaha**, L. L. Seknewna. *A comparative study of Bitcoin and Ripple cryptocurrencies trading using Deep Reinforcement Learning.* Deep Learning Indaba 2024. [arXiv:2505.07660](https://arxiv.org/abs/2505.07660)
- J. K. Mutinda, A. Langat, **R. K. M. Djaha**, J. N. Munyao, L. Whitaker, M. A. Omondi. *Enhancing Obesity Detection Through SMOTE-based Classification Models: A Comparative Study.* Interdisciplinary Journal of Epidemiology and Public Health (iJEPH), 2024. [Link](https://revistas.unilibre.edu.co/index.php/iJEPH/article/view/115320)

---

## About this repository

This repository contains the source code of my website, built with [Hugo](https://gohugo.io/) and the [HugoBlox](https://hugoblox.com/) *Academic CV* template.

### Structure

```
content/
├── _index.md            # Home page: bio, research, awards, certificates, publications
├── experience.md        # Experience, skills and languages
├── projects/            # One Markdown file per project
├── publications/        # One folder per publication (index.md + cite.bib)
└── courses/             # Courses and academic presentations
data/authors/me.yaml     # Profile: name, role, links, education, experience, awards
assets/media/            # Avatar and project images
static/uploads/          # CVs (English / Spanish)
config/_default/         # Site configuration and menus
```

### Run locally

Requirements: [Hugo extended](https://gohugo.io/installation/), [Go](https://go.dev/dl/) and [Node.js](https://nodejs.org/) with [pnpm](https://pnpm.io/).

```bash
git clone https://github.com/RegisKonan/RegisKonan.github.io.git
cd RegisKonan.github.io
pnpm install
hugo server
```

Then open http://localhost:1313.

### Deployment

Every push to `main` runs the GitHub Actions workflow [`.github/workflows/build.yml`](.github/workflows/build.yml). It builds the site with Hugo and publishes it to the `gh-pages` branch, which GitHub Pages serves at [regiskonan.github.io](https://regiskonan.github.io/). In *Settings → Pages*, the source must be **Deploy from a branch → `gh-pages` / root**.

## License

Website content © Regis Konan Marcel Djaha. The underlying template is released under the [MIT License](LICENSE.md) by HugoBlox.

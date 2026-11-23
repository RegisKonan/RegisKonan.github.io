---
title: "Understanding Autoencoders & Variational Autoencoders"
summary: "A systematic study of how depth, latent dimension, prior choice and β-weighting shape AEs and VAEs, on MNIST, FashionMNIST and FreyFace. AMMI Master's project, carried out at BCAM."
tags:
  - Deep Learning
  - Generative Models
  - Probabilistic Modeling
date: 2024-07-31
image:
  filename: project-vae-priors.jpg
  caption: "VAE latent spaces on MNIST (D_z = 2) under four different Gaussian priors."
  focal_point: Center
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/RegisKonan/ae_vae_understanding
---

## Motivation

Autoencoders (AEs) and Variational Autoencoders (VAEs) are widely used for compression, representation learning and generation, yet the effect of their main design choices is often left to trial and error. This project asks a simple question: **how do architecture and probabilistic assumptions change what these models learn?**

## What I did

- Implemented **AE**, **VAE**, **VAE with a mean-conditional Gaussian prior** and **β-VAE** models in a single, configurable PyTorch codebase.
- Ran controlled experiments on three datasets: **MNIST**, **FashionMNIST** and **FreyFace**.
- **Depth sweep:** fixed latent dimension $D_z$, varying the number of layers $n_L$.
- **Latent-dimension sweep:** fixed depth, varying $D_z$.
- **Prior study:** replaced the standard Gaussian prior with a mean-conditional Gaussian prior.
- **β-VAE study:** varied $\beta \in \{0.02,\ 1,\ 1.5,\ 10\}$ to explore the trade-off between reconstruction quality and latent regularisation.

## Outputs

For each configuration, the pipeline produces evaluation metrics, latent-space visualisations, original vs. reconstructed samples, and parameter counts, making it easy to compare models side by side.

## Resources

- 💻 [Code on GitHub](https://github.com/RegisKonan/ae_vae_understanding)
- 📄 [Master's project report (PDF)](https://github.com/RegisKonan/ae_vae_understanding/blob/main/reports/Regis_Djaha_AMMI_project_2023.pdf)

*Work carried out with Iñigo Urteaga at the Basque Center for Applied Mathematics (BCAM), supported by the "la Caixa" Junior Leader programme.*

---
title: "Kernel Methods for DNA Binding-Site Prediction"
summary: "Kaggle challenge (AMMI): predicting whether DNA sequences bind a transcription factor, with SVMs and sequence kernels implemented by the team. Multiple spectrum-kernel learning ranked 6th on the private leaderboard (67.0% accuracy)."
tags:
  - Machine Learning
  - Kernel Methods
  - Computational Biology
date: 2024-12-22
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/RegisKonan/Kernel_Methods_report-
---

## The challenge

Transcription factors (TFs) regulate gene expression by binding to specific regions of the genome. In this Kaggle data challenge, the final project of the *Kernel Methods* course at the African Master's in Machine Intelligence (AMMI), the task was to **predict whether a DNA sequence region is a binding site for a given TF**.

- 3 datasets, each with 2,000 labelled training sequences and 1,000 test sequences.
- One binary classifier per dataset.
- Goal of the course project: implement the algorithms ourselves and adapt them to structured (sequence) data.

## What we did

We started with standard baselines, then moved to kernels designed for sequence data:

- **Hard- and soft-margin SVMs**
- **Kernel Logistic Regression** and **Kernel Ridge Regression** with linear, polynomial and RBF kernels
- **Spectrum and mismatch kernels**, which compare sequences through their shared *k*-mers
- **Multiple Kernel Learning (MKL):** a combination of k-spectrum kernels with *k* = 12, 13 and 15, with kernel weights optimised by gradient descent so that the model captures substrings of several lengths at once

## Results

| Model | Public score | Private score |
|---|---|---|
| Hard-margin SVM | 54.61% | 54.61% |
| Soft-margin SVM | 53.73% | 55.46% |
| Kernel Logistic Regression | 53.46% | 53.73% |
| Kernel Ridge Regression | 63.80% | 62.90% |
| **Multiple spectrum kernels (MKL)** | **68.13%** | **67.00%** |

Our best model, MKL with spectrum kernels, finished **6th on the private leaderboard**. Combining substrings of different lengths proved clearly more effective than any single kernel.

## Resources

- 📄 [Challenge report (PDF)](https://github.com/RegisKonan/Kernel_Methods_report-/blob/main/Kernel_Methods_report.pdf)
- 💻 [Repository](https://github.com/RegisKonan/Kernel_Methods_report-)

*Team "Overfitting": Elie N. Mulamba and Regis Konan Marcel Djaha.*

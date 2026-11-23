---
title: "Cassava Leaf Disease Classification with CNNs"
summary: "Classifying cassava leaf images into 4 diseases or healthy with ResNet-50 and EfficientNet-B0 (PyTorch). Kaggle challenge (AMMI ConvNets course): our team finished 3rd."
tags:
  - Deep Learning
  - Computer Vision
  - AI for Agriculture
date: 2023-06-30
image:
  filename: project-cassava.jpg
  caption: "The five classes: healthy leaves and four cassava diseases (CBB, CGM, CMD, CBSD)."
  focal_point: Center
links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/RegisKonan/-Cassava_report
---

## Motivation

Cassava is a staple food for hundreds of millions of people in sub-Saharan Africa, and Africa produces about half of the world's cassava. Viral and bacterial diseases cause major yield losses, so **early, automatic detection from simple leaf photos** can help farmers act before the disease spreads.

## The challenge

This Kaggle competition was organised for the *Convolutional Neural Networks* course at the African Master's in Machine Intelligence (AMMI). The task: **classify a cassava leaf image into one of 4 disease categories, or healthy**.

- **9,436 labelled images**, collected from farmers in Uganda and annotated by experts from the National Crops Resources Research Institute (NaCRRI) with the Makerere University AI Lab.
- **5 classes:** healthy, Cassava Bacterial Blight (CBB), Cassava Green Mottle (CGM), Cassava Mosaic Disease (CMD) and Cassava Brown Streak Disease (CBSD).

## What we did

- **Data augmentation:** random rotations, random resized crops, horizontal flips and random erasing, to fight overfitting on a relatively small and imbalanced dataset.
- **Transfer learning** with two CNN architectures in PyTorch: **ResNet-50** and **EfficientNet-B0**.
- **Optimiser comparison:** SGD vs Adam, with cross-entropy loss, plus model quantization for lighter inference.

## Results

- 🥉 **3rd place** on the Kaggle leaderboard.
- The best model, **EfficientNet-B0 trained with SGD**, reached **90% test accuracy**. ResNet-50 stayed far below in every setting.
- The choice of optimiser had a major impact: the same architecture could gain or lose tens of accuracy points depending on SGD vs Adam.

## Resources

- 📄 [Project report (PDF)](https://github.com/RegisKonan/-Cassava_report/blob/main/Project_cassava2%20(1).pdf)
- 🏆 [Kaggle competition](https://www.kaggle.com/competitions/ammi-2023-convnets)

*Team: Elie Mulamba and Regis Konan Marcel Djaha, AMMI – AIMS Senegal.*

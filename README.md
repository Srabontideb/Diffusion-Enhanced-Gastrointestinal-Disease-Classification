# Diffusion-Enhanced Gastrointestinal Disease Classification

This project explores the use of Diffusion model to improve gastrointestinal (GI) disease classification from endoscopic images, particularly using the Kvasir v2 dataset.

## 🧠 Project Overview

This repository contains whole work on a deep learning pipeline for GI image classification, aiming to:

- Enhance data diversity using Diffusion generated synthetic samples.
- Improve classification accuracy on underrepresented disease classes.
- Apply preprocessing techniques to improve lesion visibility.
- Visualize model decision-making using explainability tools.

## 🧰 Components Implemented So Far

- ✅ Preprocessing with CLAHE and Gaussian Smoothing (Color and Contrast Normalization) -> MSRCR (Multi-Scale Retinex with Color Restoration) to further enhance lesions and mucosal textures -> Bilateral filtering to suppress compression artifacts.
- ✅ ConvMixer-based classifier with External Attention (for original dataset)
- ✅ Experiment with ConvNeXt-T, Swin Transformer and Vision Transformer with Attention Rollout.
- ✅ Initial setup for training using cosine annealing and CutMix Regularization.
- ✅ Grad-CAM-based post-processing visualization.
- ✅ Generating Accuracy, F1-score, AUC, Precision/Recall(for original data)
- 🔄 (In progress) Diffusion-based data augmentation


📊 Dataset

Kvasir v2
 — Contains 8 GI classes such as polyp, esophagitis, ulcerative colitis, etc.
 




# Retinal-Vessel-Segmentation
This project implements a hybrid framework for **retinal vessel segmentation** by integrating an enhanced **U-Net architecture**, **latent space clustering with K-means**, and a **modified Dual Iterative Thresholding (DIT)** algorithm.

---

## 🔍 Overview

Retinal vessel segmentation is essential for diagnosing diseases like:
- Diabetic Retinopathy
- Glaucoma
- Hypertensive Retinopathy

This project improves upon traditional and deep learning-only approaches by introducing a composite architecture that is both **robust and generalizable** across multiple datasets.

---

## 🧠 Key Features

- ✅ **Enhanced U-Net** with composite convolutional blocks:
  - Parallel separable, pointwise, and standard convolutions
- ✅ **K-means Clustering** in latent space to improve vessel-background separation
- ✅ **Modified DIT Algorithm** for noise reduction and continuity preservation
- ✅ **Multi-dataset Support**: Tested on CHASE_DB1, STARE, and DRIVE

---

## 📁 Dataset

This project uses three standard datasets:
- **[CHASE_DB1](https://blogs.kingston.ac.uk/retinal/chasedb1/)** – High-res images from pediatric cases
- **[STARE](https://cecas.clemson.edu/~ahoover/stare/)** – Pathological fundus images
- **[DRIVE](https://drive.grand-challenge.org/)** – Diabetic screening images

Each dataset includes expert-annotated vessel masks for training and evaluation.

---

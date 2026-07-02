# 🧪 Multimodal Materials Property Prediction using Deep Learning

## 📌 Project Overview

This project predicts the **Yield Stress of metallic alloys** by combining:

- 🖼️ Microstructure Images
- 🧬 Alloy Composition Data

Unlike traditional machine learning models that rely only on tabular data, this project uses **Multimodal Deep Learning** to learn from both visual and compositional information.

---

## 🎯 Objective

Develop a multimodal deep learning model capable of predicting the Yield Stress of alloys by fusing:

- CNN-based image features
- Composition-based tabular features

---

# Dataset

The dataset contains:

- Alloy composition
- Mechanical properties
- Temperature
- Microstructure images

Target Variable:

- **Yield Stress (MPa)**

---

# Project Pipeline

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Image Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Image Encoder (ResNet18)
      │
      ▼
Composition Encoder (MLP)
      │
      ▼
Early Fusion
      │
      ▼
Regression Head
      │
      ▼
Yield Stress Prediction
```

---

# Technologies Used

- Python
- PyTorch
- TorchVision
- Pandas
- NumPy
- Matplotlib
- Pillow
- Scikit-Learn
- Jupyter Notebook

---

# Project Phases

## ✅ Phase 1
Dataset Exploration & Preprocessing

## ✅ Phase 2
Image Processing Pipeline

## ✅ Phase 3
CNN-based Regression

## ✅ Phase 4
Image-only Deep Learning Model

## ✅ Phase 5
Multimodal Fusion (Image + Composition)

- ResNet18
- MLP
- Early Feature Fusion

## ✅ Phase 6
Model Evaluation

- MAE
- R² Score
- Error Distribution
- Actual vs Predicted Analysis

## ✅ Phase 7
Explainability (Conceptual)

- SHAP
- Grad-CAM
- Model Interpretation

---

# Model Architecture

```
Image
      │
      ▼
 ResNet18
      │
      ▼
512 Features

+

Composition
      │
      ▼
MLP
      │
      ▼
32 Features

↓

Feature Concatenation

↓

Regression Head

↓

Yield Stress Prediction
```

---

# Evaluation Metrics

- Mean Absolute Error (MAE)
- R² Score

---

# Future Improvements

- SHAP Explainability
- Grad-CAM Visualization
- Hyperparameter Optimization
- K-Fold Cross Validation
- Larger Dataset
- Vision Transformer (ViT)

---

# Repository Structure

```
├── ML materials science project.ipynb
├── README.md
├── metadata.csv
├── images/
└── requirements.txt
```

---

# Author

**Ishita Malhotra**

B.Tech, Metallurgical & Materials Engineering

National Institute of Technology Karnataka (NITK Surathkal)

Interested in:

- Machine Learning
- Data Analytics
- Materials Informatics
- AI for Scientific Applications

---

# ⭐ If you found this project useful, consider giving it a star.

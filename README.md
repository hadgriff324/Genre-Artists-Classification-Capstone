# Art Classification with Deep Learning

## Project Summary: 
This project explores how artificial intelligence can classify fine art by both **genre** and **artist** using a multi-output Convolutional Neural Network (CNN). Built as a master's capstone in Data Science at Northwestern University, the project investigates how machines interpret visual style — and what that reveals about the complexity of artistic classification.

## Problem Statement
The authentication and classification of fine art is often subjective, error-prone, and expensive. Misattributions can lead to multimillion-dollar losses, while proper recognition enhances valuation, provenance, and preservation.

## Methodology
- Dataset: ~15,000 paintings from WikiArt, labeled by genre and artist
- Model: Multi-output CNN (EfficientNetB3, ResNet50, VGG16 variants)
- Tasks:
  - Genre classification (27 classes)
  - Artist identification (200+ classes)
- Tools: TensorFlow, Python, scikit-learn, Grad-CAM, PCA

## Key Results
- Achieved **86% Top-5 accuracy** for genre classification
- Model learned meaningful visual patterns (e.g., brushstroke textures, color palettes)
- Abstract art had high misclassification rates — underscoring its subjectivity

## Why It Matters
This work supports:
- **Museums & Collectors** in attribution and valuation
- **Cultural researchers** exploring style boundaries
- **AI/ML practitioners** working on complex image interpretation

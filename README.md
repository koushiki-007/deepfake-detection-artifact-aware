# Artifact-Aware Explainable Deepfake Detection

## 📌 Overview

This project focuses on improving deepfake detection by ensuring the model learns **high-frequency forensic artifacts**, not just surface-level patterns.

## 🚀 Key Features

* EfficientNet-B0 based deepfake classifier
* Grad-CAM for explainability
* FFT-based high-frequency artifact extraction
* Novel **Fake-Only Alignment Loss**
* Improved interpretability without accuracy loss

## 📊 Results

* Accuracy: **99.96%**
* Alignment Gap improved from **0.013 → 0.262**

## 🧠 Methodology

1. Train baseline EfficientNet model
2. Extract frequency-domain features using FFT
3. Generate attention maps using Grad-CAM
4. Compute cosine similarity between attention & artifacts
5. Apply fake-only alignment loss

## 📁 Files

* `deepfake_detection.ipynb` → Model training & evaluation
* `research_paper.pdf` → Full research paper

## 🔮 Future Work

* Extend to video deepfake detection
* Cross-domain dataset testing
* Transformer-based models

## 👩‍💻 Authors

* Koushiki Das
* Aditya Dev Mishra
* Suman Mahapatra
* Mayank Sisodia



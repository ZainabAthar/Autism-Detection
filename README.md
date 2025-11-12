# Autism Detection Using Brain MRI Scans

This project focuses on detecting **Autism Spectrum Disorder (ASD)** using **structural MRI (sMRI)** and **functional MRI (fMRI)** scans. We leverage state-of-the-art deep learning models to analyze brain imaging data from **ABIDE I** and **ABIDE II** datasets.

---

## **Datasets**

- **ABIDE I & ABIDE II:**  
  Large-scale datasets containing brain MRI scans of individuals with ASD and healthy controls.  
  - sMRI: Structural images capturing anatomical details.  
  - fMRI: Functional images capturing brain activity patterns.

---

## **Models Used**

We experimented with several deep learning architectures:

1. **Convolutional Neural Network (CNN):** Baseline model for feature extraction from MRI scans.  
2. **ResNet:** Deep residual network to improve learning of complex patterns.  
3. **EfficientNet:** Optimized network providing high accuracy with fewer parameters.  

---

## **Approach**

1. Preprocess MRI scans (normalization, resizing, and augmentation).  
2. Train models on ABIDE I dataset and validate on ABIDE II dataset.  
3. Evaluate models using metrics like **accuracy, precision, recall, and F1-score**.  
4. Compare performance across different architectures to identify the most effective model for ASD detection.

---

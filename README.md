# Predictive-Maintenance-Nuclear-Operations

(This was presented as a solution to a hackathon organised by Atkins Realis.)

A machine learning pipeline for predicting pump failures using sensor data, featuring:
- Dimensionality reduction with PCA
- Transformer-based sequence modeling
- Class imbalance handling techniques

## 📌 Project Overview

This project develops a predictive maintenance system for industrial pumps using:
1. **PCA** for feature reduction (from 50+ sensors to 15 principal components)
2. **Transformer models** for temporal pattern recognition
3. Advanced techniques to handle class imbalance (focal loss, class weights, threshold tuning)

Key achievements:
- Achieved **92% recall** for critical "Broken" class
- Reduced training time by **40%** through PCA optimization

# Autism Spectrum Disorder (ASD) Prediction

## Overview
A hybrid deep learning and machine learning system for Autism Spectrum Disorder (ASD) prediction using eye-tracking scanpath images. The model combines transfer learning, PCA-based feature reduction, and ensemble learning to enable accurate and non-invasive ASD screening.

## Features
- Eye-tracking based ASD classification
- Feature extraction using MobileNet and ResNet50
- PCA dimensionality reduction
- Stacking Ensemble (SVM + KNN + Logistic Regression)
- Automated prediction pipeline

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy
- Pandas
- Matplotlib

## Project Workflow
Dataset → Preprocessing → Data Augmentation → Feature Extraction → PCA → Stacking Ensemble → Evaluation

## Results
- Best Accuracy: 92.69%
- Best Model: MobileNet + PCA + Stacking Ensemble
- PCA improved performance while reducing computational complexity.
- MobileNet provided the best speed-accuracy tradeoff.

## Repository Contents
- ASD_EyeTracking_Pipeline.ipynb – Complete implementation of the project
- Model training and evaluation code
- Performance analysis and results

## Author
Rathod Nandini 
B.Tech, Computer Science and Engineering  
National Institute of Technology, Jamshedpur

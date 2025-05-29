# Master's Thesis – Alzheimer's Disease MRI Classification

**Program:** MSc in Information Systems – Business Analytics  
**Thesis Title:** Deep Learning and Explainable AI for MRI Based Alzheimer’s Diagnosis: Enhancing Accuracy, Interpretability, and Trust 

## Overview

This repository contains the full codebase developed for the master's thesis in collaboration with my partner Casper Skovholt. The project focuses on using deep learning techniques to classify Alzheimer's disease stages based on brain MRI images. Multiple architectures are explored and evaluated based on performance and explainability.

## Repository Structure

The code is organized into three Python scripts:

- `baseline.py`:  
  Implements the baseline model using the VGG19 architecture pretrained on ImageNet.

- `sota.py`:  
  Implements a state-of-the-art model based on the ResNet50 architecture.

- `novel.py`:  
  Contains the novel approach using a Vision Transformer (ViT), also pretrained on ImageNet. This script includes:
  - ViT model setup using PyTorch
  - Integration of explainable AI techniques (LIME) for interpretability

## Dataset

The dataset used in this study consists of MRI images categorized into four stages of Alzheimer's Disease:

- Non Demented  
- Very Mild Dementia  
- Mild Dementia  
- Moderate Dementia  

**Source:** Alzheimer MRI Dataset, Kaggle  
[Link to dataset](https://www.kaggle.com/datasets/ninadaithal/imagesoasis/data?select=Data)  
Accessed: 9 May 2025

## Evaluation Metrics

All models were evaluated using the following metrics:

- Accuracy  
- Sensitivity (Recall)  
- F1 Score  
- Confusion Matrix  
- Training vs. Validation Loss and Accuracy  
- Explainability output (only for the ViT model)

## License and Usage

This repository is part of a joint academic project submitted for a Master's degree in Business Analytics.  
If you use or reference any part of this work, please provide proper attribution.

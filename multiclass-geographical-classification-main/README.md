# Multi-Class Geographical Classification from Satellite Images

This repository contains the implementation of a deep learning framework for classifying satellite images into three geographical categories: desert, mountain, and lake.

The proposed approach leverages pre-trained DenseNet models for deep feature extraction and applies a serial feature fusion strategy to combine complementary features from multiple models. Classification is performed using SoftMax, Decision Tree, and Random Forest classifiers, and model interpretability is analyzed using Grad-CAM visualizations.

## Features
- Multi-class satellite image classification
- DenseNet-121 and DenseNet-201 feature fusion
- Feature reduction and serial concatenation
- Multiple classifiers for performance comparison
- Grad-CAM-based interpretability
- Threefold cross-validation

## Dataset
The Kaggle SkyView dataset is used. Please see `dataset/README.md` for download instructions.

## Requirements
- Python 3.10
- TensorFlow 2.8
- NumPy
- scikit-learn
- OpenCV
- Matplotlib

## Usage
1. Download and organize the dataset.
2. Install dependencies:

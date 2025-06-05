# Dogs vs Cats Image Classification

A computer vision project focusing on traditional image processing techniques for binary classification of dogs and cats using machine learning algorithms. A Project for the CC516 Image Processing & Pattern Recognition Course at AAST.

## 📋 Project Overview

This project implements a dogs vs cats binary classifier with emphasis on **image processing and feature extraction** rather than deep learning approaches. The goal was to explore how traditional computer vision techniques combined with classical machine learning algorithms perform on image classification tasks.

## 🔧 Technical Approach

### Image Processing Pipeline
1. **Preprocessing**:
   - Image resizing to 128x128 pixels for consistency
   - Grayscale conversion
   - Gaussian blur for noise reduction

2. **Feature Extraction**:
   - Edge detection using Canny edge detector
   - Morphological transformations (closing operation)
   - Histogram equalization for image enhancement

3. **Classification**:
   - Feature flattening for traditional ML algorithms
   - Decision Tree classifier
   - Random Forest classifier

### Key Image Processing Techniques
- **Canny Edge Detection**: Extracts structural features
- **Gaussian Blur**: Reduces noise and smooths images
- **Morphological Operations**: Enhances edge connectivity
- **Histogram Equalization**: Improves contrast and feature visibility

## 📊 Dataset

- **Source**: Kaggle Dogs vs Cats Dataset
- **Structure**: 
  - Training set with cat and dog images
  - Validation set for model tuning
  - Test set for final evaluation

## 🚀 Models & Results

### Decision Tree Classifier
- Basic tree-based classification on processed image features
- Baseline model for comparison

### Random Forest Classifier
- Ensemble method with 100 estimators
- Better performance through multiple decision trees
- Reduces overfitting compared to single decision tree

## 💻 Tech Stack

**Languages & Libraries:**
- Python
- OpenCV (cv2) - Image processing
- NumPy - Numerical operations
- Matplotlib - Visualization
- Scikit-learn - Machine learning algorithms
- Pandas - Data manipulation

**Environment:**
- Google Colab
- Kaggle API for dataset download

## Running the Project
1. **Clone the repository**
2. **Set up Kaggle API**:
   - Download `kaggle.json` from your Kaggle account
   - Place it in the appropriate directory
3. **Run the notebook**:
   - Execute cells sequentially
   - Dataset will be automatically downloaded from Kaggle
4. **View results**:
   - Model accuracy metrics
   - Sample processed images visualization
   - Prediction examples with actual vs predicted labels


# Robust Traffic Sign Recognition Using Deep Learning: A Comparative Analysis

**Course:** AAI-521: Computer Vision  
**Program:** Master of Science in Applied Artificial Intelligence  
**University:** University of San Diego (USD)  
**Project Status:** In Progress

## Project Overview

This project focuses on developing and comparing deep learning models for traffic sign classification using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The goal is to evaluate how accurately different models recognize traffic signs under normal and challenging visual conditions.

Two deep learning models will be compared:

- **Custom Convolutional Neural Network (CNN):** A model developed and trained from scratch.
- **MobileNetV2:** A pretrained model that will be fine-tuned using transfer learning.

The project will also examine how reduced lighting, motion blur, and image noise affect model performance. The results will help identify the strengths and limitations of each approach.

## Team Members

Dina Othman
Zinah Othman
Christina Sadiq

## Dataset

**German Traffic Sign Recognition Benchmark (GTSRB)**

Dataset source: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

The GTSRB dataset contains 51,839 labeled traffic sign images across 43 categories, including speed limits, warning signs, and regulatory signs.

The dataset includes:

- 39,209 training images
- 12,630 testing images
- 43 traffic sign classes
- Images with varying sizes, lighting conditions, and viewing angles

The original training dataset will be divided into training and validation sets, while the official test dataset will be kept separate for final evaluation.

## Project Components

### 1. Dataset Preparation and Exploratory Data Analysis

- Load and explore the GTSRB dataset.
- Examine class distributions and image dimensions.
- Check for missing, duplicate, or corrupted data.
- Resize and normalize images.
- Prepare training, validation, and testing datasets.
- Explore data augmentation techniques.
- Create visualizations and document preprocessing steps.

### 2. Custom CNN Development and Evaluation

- Design and implement a custom CNN architecture.
- Train the model using the prepared dataset.
- Perform hyperparameter tuning to improve performance.
- Evaluate accuracy, precision, recall, and F1-score.
- Generate confusion matrices and training visualizations.
- Analyze model performance and limitations.

### 3. MobileNetV2 Development and Evaluation

- Implement a pretrained MobileNetV2 model.
- Apply transfer learning and fine-tuning.
- Train and optimize the model using the same dataset splits.
- Evaluate performance using the same metrics as the custom CNN.
- Generate confusion matrices and training visualizations.
- Analyze model performance and limitations.

### 4. Model Comparison and Robustness Testing

Both models will be compared based on:

- Accuracy
- Precision
- Recall
- F1-score
- Training performance
- Performance under reduced lighting
- Performance under motion blur
- Performance under image noise

The final comparison will identify which model performs better under normal and challenging conditions and discuss the reasons for the differences.


## Technologies

- Python
- Google Colab
- GitHub
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

## Collaboration and Workflow

Google Colab will be used for developing and training the models, while GitHub will be used to organize project files and track contributions.

## Academic Use

This repository is intended for academic use as part of the University of San Diego's Master of Science in Applied Artificial Intelligence program.

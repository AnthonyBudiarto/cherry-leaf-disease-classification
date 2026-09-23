# Cherry Leaf Disease Classification

A deep learning project for classifying cherry leaf diseases using Convolutional Neural Networks (CNN).

## Project Overview

This project focuses on image classification of cherry leaves into 5 different disease classes. The model is based on an AlexNet-inspired CNN architecture and explores the impact of data augmentation, batch normalization, and dropout on model performance.

## Methodology

- Image preprocessing and resizing to 224×224 RGB
- CNN-based image classification
- AlexNet-inspired architecture
- Data augmentation
- Batch normalization
- Dropout
- Model evaluation using Accuracy, Precision, Recall, and F1-Score

## Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Baseline CNN | 74.7% | 75.5% | 74.7% | 74.8% |
| Modified CNN | 78.4% | 82.6% | 78.4% | 77.8% |

The modified CNN achieved higher overall performance after incorporating data augmentation, batch normalization, and dropout.

## Technologies

- Python
- TensorFlow / Keras
- CNN
- AlexNet
- Computer Vision
- Jupyter Notebook

## Project Structure

```text
cherry-leaf-disease-classification/
├── CherryLeafCNN_project.ipynb
└── README.md

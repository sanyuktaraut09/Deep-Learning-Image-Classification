
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sanyuktaraut09/Image-Classification-CNN/blob/main/CNN_PROJECT.ipynb)
# Image Classification using Custom CNN & Transfer Learning

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)]()
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)]()
[![Keras](https://img.shields.io/badge/Keras-DeepLearning-red.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

## Overview

This project implements an end-to-end image classification pipeline using Deep Learning. Two different approaches are developed and compared:

- A **Custom Convolutional Neural Network (CNN)** built from scratch.
- A **Transfer Learning model** using a pre-trained CNN (ResNet50/VGG16).

The objective is to evaluate the effectiveness of transfer learning against a custom CNN in terms of classification performance, convergence, computational efficiency, and generalization.

---

## Features

- Custom CNN architecture implementation
- Transfer Learning using pre-trained ResNet50/VGG16
- Global Average Pooling (GAP)
- Data preprocessing and augmentation
- Model training and validation
- Performance comparison
- Evaluation using multiple classification metrics
- Visualization of training curves and confusion matrix

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Dataset

**Dataset:** Cats vs Dogs

The dataset contains images belonging to two classes:

- Cats
- Dogs

Images are preprocessed before training by resizing and normalization. Data is divided into training and testing sets for model evaluation.

---

## Model Architectures

### 1. Custom CNN

The custom CNN consists of:

- Convolution Layers
- Max Pooling Layers
- Global Average Pooling
- Softmax Output Layer

---

### 2. Transfer Learning

A pre-trained CNN (ResNet50/VGG16) is used as a feature extractor.

Key steps include:

- Loading ImageNet pretrained weights
- Freezing base layers
- Adding Global Average Pooling
- Adding a custom classification layer
- Fine-tuning the model

---

## Evaluation Metrics

Both models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

Additional comparisons include:

- Training Loss
- Validation Loss
- Training Time
- Model Complexity

---

## Results

The project compares the performance of both models based on:

- Classification Accuracy
- Model Convergence
- Computational Cost
- Transfer Learning Effectiveness

Overall, the Transfer Learning model demonstrated improved feature extraction and faster convergence compared to the custom CNN.

---

## Project Structure

```
Image-Classification-CNN
│
├── CNN_PROJECT.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
└── images
    ├── architecture.png
    ├── training_accuracy.png
    ├── training_loss.png
    ├── confusion_matrix.png
    └── sample_predictions.png
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Image-Classification-CNN.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
CNN_PROJECT.ipynb
```

4. Run all cells.

---

## Future Improvements

- Hyperparameter optimization
- Data augmentation techniques
- Model quantization
- Mobile deployment using TensorFlow Lite
- Multi-class image classification
- Explainable AI using Grad-CAM

---

## Author

**Sanyukta Raut**

B.Tech Electronics & Telecommunication Engineering

Interested in Deep Learning, Computer Vision, Artificial Intelligence, and Software Development.

---

## License

This project is licensed under the MIT License.

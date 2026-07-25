# Multi-Layer Perceptron (MLP) for Fashion-MNIST Image Classification using TensorFlow/Keras

## Overview

This project implements a **Multi-Layer Perceptron (MLP)** using **TensorFlow/Keras** to classify images from the Fashion-MNIST dataset. The experiment demonstrates the complete deep learning workflow, including data preprocessing, model construction, training, evaluation, and hyperparameter optimization using **RandomizedSearchCV** with the **SciKeras** wrapper.

The objective is to understand how an MLP learns image features, evaluate its classification performance, and improve the model through systematic hyperparameter tuning.

---

## Objectives

- Load and preprocess the Fashion-MNIST dataset.
- Build a baseline Multi-Layer Perceptron (MLP) model.
- Train the model using TensorFlow/Keras.
- Evaluate the model using standard classification metrics.
- Visualize training and validation performance.
- Optimize model hyperparameters using RandomizedSearchCV.
- Compare the baseline and optimized models.

---

## Dataset

**Dataset:** Fashion-MNIST

The Fashion-MNIST dataset consists of grayscale images of clothing items.

- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10

Classes include:

- T-shirt/Top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

---

## Project Structure

```
MLP-FashionMNIST/
│
├── README.md
├── requirements.txt
├── mlp_fashion_mnist.ipynb
├── images/
│   ├── sample_images.eps
│   ├── class_distribution.eps
│   ├── training_accuracy.eps
│   ├── validation_accuracy.eps
│   ├── training_loss.eps
│   ├── validation_loss.eps
│   ├── confusion_matrix.eps
│   ├── hyperparameter_search.eps
│   └── best_model_accuracy_comparison.eps
│
└── report/
    └── Deep_Learning_Report.pdf
```

---

## Software Requirements

- Python 3.11+
- TensorFlow 2.20.0
- SciKeras 0.13.0
- Scikit-learn 1.5.2
- NumPy 2.3.1
- Pandas 2.3.1
- Matplotlib 3.10.3

---

## Installation

Clone the repository.

```bash
git clone <repository-url>
```

Move into the project folder.

```bash
cd MLP-FashionMNIST
```

Install the required libraries.

```bash
pip install -r requirements.txt
```

---

## Experiment Workflow

### Step 1

Load the Fashion-MNIST dataset.

### Step 2

Preprocess the data by

- Normalizing pixel values
- Flattening images
- One-hot encoding labels

### Step 3

Construct the baseline MLP model using TensorFlow/Keras.

### Step 4

Train the model.

### Step 5

Evaluate the model using

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Step 6

Visualize

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

### Step 7

Perform hyperparameter optimization using

- RandomizedSearchCV
- SciKeras
- 5-Fold Cross Validation

### Step 8

Compare the baseline and optimized models.

---

## Hyperparameters Optimized

The following hyperparameters were tuned:

- Number of Hidden Layers
- Number of Hidden Neurons
- Learning Rate
- Optimizer
- Activation Function
- Batch Size
- Number of Epochs
- Dropout Rate

---

## Performance Metrics

The models were evaluated using

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Output

The experiment generates

- Sample Images
- Class Distribution
- Model Summary
- Training Accuracy vs Epoch
- Validation Accuracy vs Epoch
- Training Loss vs Epoch
- Validation Loss vs Epoch
- Confusion Matrix
- Hyperparameter Search Results
- Baseline vs Optimized Accuracy Comparison

---

## Learning Outcomes

After completing this experiment, the following concepts are understood:

- Image preprocessing for deep learning
- Multi-Layer Perceptron architecture
- Forward propagation and backpropagation
- TensorFlow/Keras model development
- Model evaluation techniques
- Hyperparameter optimization
- Cross-validation
- Performance comparison of deep learning models

---

## Conclusion

The experiment successfully demonstrates the implementation of a Multi-Layer Perceptron for Fashion-MNIST image classification using TensorFlow/Keras. The baseline model achieved high classification accuracy, while RandomizedSearchCV systematically explored different hyperparameter combinations to identify an alternative configuration with comparable performance. The experiment highlights the importance of preprocessing, model evaluation, and hyperparameter tuning in developing reliable deep learning models.

---

## Author

**Name:** Chalamalasetti Asmita

**Course:** Deep Learning Laboratory

**Institution:** Shiv Nadar University Chennai

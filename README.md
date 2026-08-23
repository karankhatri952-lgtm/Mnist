# MNIST Digit Recognition Using Machine Learning

## 📌 Project Overview

This project focuses on building a Machine Learning model that can recognize and classify handwritten digit images from **0 to 9** using the **MNIST dataset**.

The project covers the complete Machine Learning workflow, including data loading, preprocessing, visualization, model training, prediction, and evaluation.

## 🎯 Objectives

- Load and explore the MNIST dataset.
- Preprocess handwritten digit images.
- Normalize pixel values.
- Visualize sample digit images.
- Train a Machine Learning classification model.
- Predict handwritten digits from 0 to 9.
- Evaluate the model using accuracy.
- Generate a classification report.
- Analyze results using a confusion matrix.

## 📊 Dataset

The project uses an MNIST dataset in CSV format.

Each image contains:

- **28 × 28 pixels**
- **784 pixel features**
- One `label` column representing the digit.

The labels range from:

`0, 1, 2, 3, 4, 5, 6, 7, 8, 9`

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🤖 Machine Learning Model

The project uses the **K-Nearest Neighbors (KNN)** classification algorithm.

The model is trained using the processed MNIST images and their corresponding labels.

### Model Configuration

```python
KNeighborsClassifier(n_neighbors=3)

# Breast Cancer Detection using PyTorch

## Overview
This project showcases a complete pipeline using PyTorch to perform binary classification for breast cancer detection. It builds a neural network to classify tumors as malignant or benign based on diagnostic features from the dataset.

## 📂 Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset. It is loaded directly from a GitHub repository:

- Source: [Breast Cancer Dataset CSV](https://raw.githubusercontent.com/gscdit/Breast-Cancer-Detection/refs/heads/master/data.csv)

## 📊 Features

- **Data Preprocessing:** Handling null values, dropping irrelevant columns, encoding labels, feature scaling.
- **Train-Test Split:** Using `train_test_split` to create training and testing datasets.
- **Model Building:** A simple feedforward neural network implemented in PyTorch.
- **Training:** The model is trained using Binary Cross Entropy Loss.
- **Evaluation:** Accuracy is calculated on the test set.

## 🧠 Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
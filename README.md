# 🧠 Handwritten Digit Classification – MNIST Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GorohovskiMax/MNIST-handwritten-dataset---ML-implementations/blob/main/MNIST.ipynb)

This project explores and compares three classic machine learning algorithms for classifying handwritten digits using the **MNIST dataset** – a benchmark dataset of 70,000 images (28x28 grayscale) representing digits from 0 to 9.

---

## 🔍 Objective

To classify handwritten digits using various machine learning algorithms implemented **from scratch**, and compare their strengths, weaknesses, and performances.

---

## 📌 Implemented Algorithms

### 🔹 Multi-Class Perceptron (Pocket Algorithm)
- Extended using One-vs-All (OvA) approach.
- Handles linearly inseparable data using a "pocket" for the best weights found.

### 🔹 Softmax Regression
- Generalization of logistic regression for multi-class classification.
- Uses cross-entropy loss for optimization.
- Outputs class probabilities for each image.

### 🔹 Linear Regression
- Adapted for classification through thresholding.
- Explores the potential of regression models in classification tasks.

---

## 📈 Evaluation
- All models are evaluated based on accuracy on the MNIST test set.
- Detailed analysis of classification performance and model behavior is included in the notebook.

---

## 🛠️ Technologies
- Python (NumPy, Matplotlib)
- Jupyter Notebook / Google Colab
- No external ML libraries (e.g., no scikit-learn, TensorFlow, etc.)

---

## 🚀 Getting Started
You can explore the notebook directly in Colab:

➡️ [Open in Google Colab](https://colab.research.google.com/github/GorohovskiMax/MNIST-handwritten-dataset---ML-implementations/blob/main/MNIST.ipynb)

Or clone and run locally:
```bash
git clone https://github.com/GorohovskiMax/MNIST-handwritten-dataset---ML-implementations.git
cd MNIST-handwritten-dataset---ML-implementations
jupyter notebook

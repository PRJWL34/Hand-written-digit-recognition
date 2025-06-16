# 🧠 Handwritten Digit Recognition

Educational project for recognizing handwritten digits using machine learning techniques on the MNIST dataset. Built for learning, experimentation, and understanding neural networks in action.

---

## 📌 Introduction

This project is a simple implementation of a neural network to classify handwritten digits (0–9) using the MNIST dataset. It is designed as an educational tool for understanding the fundamentals of image classification and deep learning.

---

## ⚙️ How It Works

1. **Load the Dataset** – The MNIST dataset is loaded directly from TensorFlow/Keras.
2. **Preprocess the Data** – Normalize pixel values to scale from 0–1.
3. **Build the Model** – A neural network is built using `Sequential` API.
4. **Train the Model** – The model is trained on the training set using `model.fit()`.
5. **Evaluate the Model** – Accuracy is measured using the test set.
6. **Predict** – The model can predict unseen digits.

---

## 📊 Dataset Used

Dataset Name**: MNIST (Modified National Institute of Standards and Technology)
Size**:
  - 60,000 training images
  - 10,000 testing imagesImage Format: 28x28 grayscale images of digits (0–9)
-  Source: [MNIST](http://yann.lecun.com/exdb/mnist/)

---

🛠️ Tech Stack

- **Programming Language**: Python 3.x
- **Libraries Used**:
  - NumPy
  - Matplotlib (optional for visualization)
  - TensorFlow / Keras

---

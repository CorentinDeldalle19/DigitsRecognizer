# 🧠 Neural Network from Scratch with NumPy

Welcome to this project where I built a **neural network from scratch**, without using any machine learning frameworks like TensorFlow or PyTorch. Just **NumPy**, lots of matrix operations, and a strong desire to understand how deep learning works under the hood 💻.

---

## 📌 Objective

The main goal of this project was to **deeply understand how a neural network functions**, including:

- How data flows through the network (**forward propagation**)
- How errors are calculated and propagated (**backpropagation**)
- How the model learns using **gradient descent**

---

## 🔧 Architecture

This project implements a **3-layer neural network**:

- **Layer 1 (Input → 128 neurons)**: ReLU activation  
- **Layer 2 (128 → 64 neurons)**: ReLU activation  
- **Output Layer (64 → 10 classes)**: Softmax activation for classification

---

## 🗂️ Dataset

The model is trained on the **MNIST dataset**, a classic benchmark containing **70,000 handwritten digit images** (28x28 grayscale):

- **Training set**: 69,000 images  
- **Validation set (Dev set)**: 1,000 images

---

## ⚙️ Features

✅ Forward propagation  
✅ Backpropagation  
✅ Training using gradient descent  
✅ One-hot encoding of labels  
✅ Cross-entropy loss function  
✅ Real-time prediction and loss display  
✅ Visual testing with custom image predictions

---

## 📊 Results

The final model is able to **accurately recognize handwritten digits**, fully implemented from scratch using only NumPy — no deep learning frameworks involved.
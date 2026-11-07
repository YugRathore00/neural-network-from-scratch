# Neural Network from Scratch (MNIST)

A two-layer neural network built entirely from scratch using only Python, NumPy, and Pandas—without relying on high-level deep learning frameworks like TensorFlow or PyTorch. 

This project implements the core mechanics of deep learning from first principles, demonstrating the underlying linear algebra and calculus behind model training.

---

## 🚀 Key Features

* **Manual Forward & Backward Propagation:** Built custom matrix operations, transposes, and gradient computations.
* **Activation Functions:** Implemented **ReLU** for non-linear hidden layer representation and **Softmax** for multi-class probability outputs.
* **Optimization:** Used standard Gradient Descent to iteratively update weights (`W1`, `W2`) and biases (`b1`, `b2`).
* **Preprocessing:** Handled pixel normalization ($0\text{–}255 \rightarrow 0.0\text{–}1.0$) to stabilize gradient updates.
* **Visualization:** Used **Matplotlib** to visually evaluate digit samples against the model's actual predictions.

---

## 📊 Performance

* **Dataset:** MNIST Handwritten Digits (28x28 grayscale images)
* **Accuracy:** Reached **~82% accuracy** within 500 iterations using pure NumPy matrix operations.

---

## 🛠️ Stack & Dependencies

| Tool | Purpose |
| :--- | :--- |
| **Python** | Primary Programming Language |
| **NumPy** | Vectorized Operations & Linear Algebra |
| **Pandas** | Data Loading & Matrix Manipulation |
| **Matplotlib** | Prediction Visualization |

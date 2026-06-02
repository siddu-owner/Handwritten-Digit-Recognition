# Handwritten-Digit-Recognition
CNN model to recognize handwritten digits using MNIST dataset
# ✏️ Handwritten Digit Recognition

## 📌 Objective
Identify handwritten digits (0-9) using Deep Learning.

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Network)
- MNIST Dataset

## 📊 Results
| Metric | Score |
|--------|-------|
| Test Accuracy | 99.23% |
| Test Loss | 0.0252 |
| Precision | 0.99 |
| Recall | 0.99 |
| F1-Score | 0.99 |

## 🗂️ Dataset
- MNIST — 70,000 handwritten digit images
- 60,000 training / 10,000 testing
- Image size: 28x28 pixels

## 🧠 Model Architecture
- Conv2D → MaxPooling
- Conv2D → MaxPooling
- Flatten → Dense(128) → Dropout → Dense(10)
- Total Parameters: 225,034

## 🚀 How to Run
1. Open notebook in Google Colab
2. Run all cells sequentially
3. Use the interactive canvas to draw and predict!

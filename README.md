# 🎭 Mamukka Lalettan Classifier

A deep learning-based image classifier that distinguishes between Malayalam actors **Mammootty** (Mamukka) and **Mohanlal** (Lalettan) using a Convolutional Neural Network (CNN) built with Keras and TensorFlow.

---

## 📌 Overview

This project implements a CNN model to classify images of Mammootty and Mohanlal. The model extracts visual features and uses them to accurately predict which actor appears in a given image.

---

## ⚠️ Disclaimer

The images used in this project are sourced from publicly available content on the internet and are included solely for educational and demonstrative purposes. We do not claim ownership of any image used.

---

## 🗂 Dataset Structure

The dataset is organized into `train` and `test` directories, each with two subdirectories:

dataset/
├── train/
│ ├── mammootty/
│ └── mohanlal/
└── test/
├── mammootty/
└── mohanlal/


Each subdirectory contains images of the respective actor.

---

## 🧠 Model Architecture

The CNN model is composed of:

- Three convolutional layers with ReLU activation
- MaxPooling layers to reduce spatial dimensions
- Dropout for regularization
- Fully connected dense layers
- Output layer with softmax activation

**Training Details:**

- Optimizer: `Adam`
- Learning Rate: `1e-6`
- Epochs: `500`
- Loss Function: `categorical_crossentropy`

---

## 📈 Performance

- **Training Accuracy:** 90.22%
- **Validation Accuracy:** 92.50%
- Evaluation metrics such as **Precision**, **Recall**, and **F1-Score** confirm the model's effectiveness.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/3idhun/image-classification-using-CNN.git
cd image-classification-using-CNN

pip install -r requirements.txt

python train.py

python evaluate.py

python predict.py path/to/image.jpg

.
├── dataset/
├── train.py
├── evaluate.py
├── predict.py
├── model/
│   └── cnn_model.h5
├── utils/
│   └── image_preprocessing.py
├── requirements.txt
└── README.md



---







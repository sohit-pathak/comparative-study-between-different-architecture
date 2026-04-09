# Comparative Study Between Different Deep Learning Architectures

A research project comparing **VGG16** and **AlexNet** deep learning architectures for **Potato Disease Classification** using image data. This was a team project (Team 4) submitted as part of an academic course.

---

## 📌 Project Overview

This project investigates how different Convolutional Neural Network (CNN) architectures perform on the task of classifying potato plant diseases from images. The two architectures compared are:

- **VGG16** — A deep 16-layer network known for its simplicity and effectiveness
- **AlexNet** — One of the pioneering deep CNN architectures

---

## 📁 Repository Structure

```
├── potato_disease_classification_using_Vgg16_model (2).ipynb       # VGG16 model notebook
├── potato_disease_classification_using__AlexNet_model (2).ipynb    # AlexNet model notebook
├── Final PPT Team 4 (2).pdf                                         # Presentation slides
├── Report Team 4 (2).pdf                                            # Full project report
└── README.md
```

---

## 🌿 Task: Potato Disease Classification

The models classify potato plant images into categories such as:
- **Early Blight**
- **Late Blight**
- **Healthy**

---

## 🔬 Models Compared

### 🏗️ VGG16
- **Architecture:** 16-layer deep CNN with 3×3 convolution filters
- **Pre-trained:** Transfer learning from ImageNet
- Known for uniformity in architecture and high accuracy on image tasks

### 🏗️ AlexNet
- **Architecture:** 8-layer CNN (5 convolutional + 3 fully connected)
- Pioneer of deep learning for image classification
- Uses ReLU activations and dropout for regularization

---

## 📏 Evaluation Metrics

- Accuracy
- Loss (Cross-Entropy)
- Confusion Matrix
- Precision / Recall / F1-Score

---

## ⚙️ Tech Stack

| Library        | Purpose                          |
|---------------|----------------------------------|
| `TensorFlow` / `Keras` | Model building & training |
| `numpy`        | Numerical operations             |
| `matplotlib`   | Visualization                    |
| `PIL`          | Image preprocessing              |
| `sklearn`      | Evaluation metrics               |

---

## 🚀 Getting Started

```bash
pip install tensorflow numpy matplotlib pillow scikit-learn
jupyter notebook "potato_disease_classification_using_Vgg16_model (2).ipynb"
```

---

## 📄 Reports

- 📊 **Presentation:** `Final PPT Team 4 (2).pdf`
- 📝 **Full Report:** `Report Team 4 (2).pdf`

---

## 👥 Team

Team 4 — IIT Madras

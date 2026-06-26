# 🐶🐱 Cats vs Dogs Image Classifier using Transfer Learning

A deep learning project that classifies images of cats and dogs using **Transfer Learning** with the **VGG16** pre-trained Convolutional Neural Network (CNN). The project leverages TensorFlow and Keras to build an accurate binary image classification model while reducing training time by utilizing learned ImageNet features.

---

## 📌 Project Overview

This project uses the **VGG16** model as a feature extractor for classifying images into two categories:
- 🐱 Cat
- 🐶 Dog

Instead of training a CNN from scratch, the model uses transfer learning to achieve better performance with fewer training samples and faster convergence.

---

## 🚀 Features

- Binary image classification (Cats vs Dogs)
- Transfer Learning using **VGG16**
- Image preprocessing and normalization
- Model training and validation
- Performance visualization using training history
- Built with TensorFlow and Keras

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- VGG16 (Pre-trained CNN)


---

## ⚙️ Model Architecture

- **Base Model:** VGG16 (ImageNet Weights)
- **Input Size:** 150 × 150 × 3
- **Top Layers:**
  - Flatten
  - Dense (256, ReLU)
  - Dense (1, Sigmoid)

---

## 📊 Workflow

1. Load and preprocess image dataset
2. Resize images to **150×150**
3. Load the pre-trained VGG16 model
4. Build a custom classification head
5. Train the model on the training dataset
6. Validate the model
7. Evaluate performance and visualize results

---

## 📈 Results

The model successfully learns to distinguish between cats and dogs using transfer learning, demonstrating the effectiveness of pre-trained CNNs for image classification tasks.

---

## 💡 Key Concepts Used

- Deep Learning
- Computer Vision
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Binary Classification
- Image Preprocessing
- Model Training & Validation

---

## 🎯 Learning Outcomes

- Implemented transfer learning with a pre-trained CNN.
- Built an end-to-end image classification pipeline using TensorFlow and Keras.
- Gained practical experience with image preprocessing, model training, and evaluation.
- Understood how transfer learning improves accuracy while reducing computational cost.

---

## 📦 Installation

```bash
git clone https://github.com/your-username/Cats-vs-Dogs-Classifier.git

cd Cats-vs-Dogs-Classifier

pip install tensorflow keras numpy matplotlib
```

---

## ▶️ Run the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```
dogsvscats transfer-learning-finetuning.ipynb
```

---

## 📷 Dataset

The project uses a Cats vs Dogs image dataset containing labeled images for binary classification. Place the dataset inside the appropriate training and validation directories before running the notebook.

---

## 👨‍💻 Author

**Utsav Sharma**

- B.Tech Information Technology
- Aspiring Data Scientist & Machine Learning Engineer

---

## ⭐ If you found this project useful, don't forget to star the repository!

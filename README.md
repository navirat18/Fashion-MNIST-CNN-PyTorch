# 👕 Fashion MNIST Classification using CNN (PyTorch)

## 📌 Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the Fashion MNIST dataset into 10 different clothing categories.

The model learns visual features from grayscale images and predicts the corresponding fashion category.

## 📊 Dataset Information
Fashion MNIST contains 70,000 grayscale images.

- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Color:** Grayscale
- **Number of Classes:** 10

## 👗 Fashion Categories

| Label | Category |
|---|---|
| 0 | T-shirt/Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle Boot |

## 🧠 CNN Architecture

The Convolutional Neural Network consists of:

- Convolutional Layers
- ReLU Activation Function
- Max Pooling Layers
- Flatten Layer
- Fully Connected Layers
- Output Layer with 10 classes

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn

## ⚙️ Project Workflow

1. Load the Fashion MNIST dataset.
2. Preprocess and normalize the images.
3. Convert images into PyTorch tensors.
4. Build the CNN architecture.
5. Train the model using an optimizer and loss function.
6. Evaluate the model using test data.
7. Visualize predictions and model performance.

## 📈 Model Evaluation

The model performance can be evaluated using:

- Training Accuracy
- Testing Accuracy
- Loss Curves
- Confusion Matrix
- Classification Report

## 🚀 Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Fashion-MNIST-CNN-PyTorch.git
```

### 2. Navigate to the project directory

```bash
cd Fashion-MNIST-CNN-PyTorch
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder.

## 🎯 Objective

The main objective of this project is to understand and implement Convolutional Neural Networks using PyTorch and gain practical experience in deep learning and computer vision.

## 👨‍💻 Author

**Naveen**

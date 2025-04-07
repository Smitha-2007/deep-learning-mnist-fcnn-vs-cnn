# deep-learning-mnist-fcnn-vs-cnn
# MNIST Handwritten Digit Classification using Deep Learning

This project implements and compares two deep learning models — a **Fully Connected Neural Network (FCNN)** and a **Convolutional Neural Network (CNN)** — to classify handwritten digits from the **MNIST dataset**.

## Project Overview

The MNIST dataset contains 70,000 grayscale images of handwritten digits (0–9), each sized 28x28 pixels. This project explores how different neural network architectures affect model performance on this dataset.

---

##  Models Used

### 1. Fully Connected Neural Network (FCNN)
- Simple dense layers
- Limited capacity for visual/spatial features

### 2. Convolutional Neural Network (CNN)
- Uses convolutional and pooling layers
- Better performance on image classification tasks

---

## Results

| Model | Test Accuracy |
|-------|---------------|
| FCNN  | ~97.4%        |
| CNN   | ~99.0%        |

- CNN outperforms FCNN due to its ability to learn spatial features from images.
- Confusion matrices and accuracy/loss curves are used for performance analysis.

---

## Performance Visualization

- Accuracy and Loss plots (training vs validation)
- Confusion matrix heatmaps
- Model evaluation summaries

---

## Dataset

- MNIST dataset (available via `tensorflow.keras.datasets`)
- 60,000 training images and 10,000 testing images

---

## How to Run

1. Open the notebook: `Deep_Learning_Proj_MNIST_dataset.ipynb`
2. Run all cells (in Google Colab or Jupyter Notebook)
3. View plots, model comparisons, and final predictions




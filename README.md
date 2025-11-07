#  Handwritten Digit Recognition using CNN (LeNet-5)

###  Introduction

This project implements a **Convolutional Neural Network (CNN)** based on the **LeNet-5 architecture** to classify handwritten digits (0–9) from the **MNIST dataset**.
It demonstrates how deep learning models can automatically learn spatial hierarchies of features from images, achieving high accuracy in image classification tasks.
The project is completed and finalized as part of my AI and Deep Learning learning journey.

---

###  Project Overview

The workflow includes:

1. **Data Loading** – Using the MNIST dataset of 70,000 grayscale digit images (28x28 pixels).
2. **Data Preprocessing** – Normalizing image pixel values and reshaping input data for CNNs.
3. **Model Architecture** – Building a CNN with:

   * Convolutional and pooling layers for feature extraction
   * Dense layers for classification
   * Softmax activation for multi-class output
4. **Model Training** – Compiling with **categorical cross-entropy** loss and the **Adam optimizer**.
5. **Evaluation** – Measuring model accuracy and visualizing predictions.

---

###  Tools & Libraries Used

* **Python 3.12**
* **TensorFlow** and **Keras** – Deep learning framework
* **NumPy**, **Matplotlib** – Data handling and visualization
* **MNIST Dataset** – Preloaded dataset from `keras.datasets`

---

###  Implementation Summary

* Loaded and normalized the MNIST dataset.
* Built a CNN using **Conv2D**, **MaxPooling2D**, **Flatten**, and **Dense** layers.
* Trained the model for multiple epochs to minimize validation loss.
* Achieved over **99% accuracy** on the test set.
* Visualized predictions and performance metrics (accuracy and loss curves).

---

###  Results

| Metric            | Value       |
| ----------------- | ----------- |
| Training Accuracy | ~99.2%      |
| Test Accuracy     | ~99.0%      |
| Loss              | <0.05       |
| Model             | LeNet-5 CNN |

The model successfully classifies handwritten digits with near-perfect accuracy on MNIST data.

---


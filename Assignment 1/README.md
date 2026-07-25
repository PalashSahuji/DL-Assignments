# Handwritten Digit Recognition using TensorFlow and Keras

## Overview
This project implements a simple Artificial Neural Network (ANN) using **TensorFlow** and **Keras** to recognize handwritten digits from the **MNIST dataset**. The project demonstrates the complete machine learning workflow, including dataset loading, preprocessing, model training, evaluation, and saving the trained model.

---

## Objective
- Load the MNIST handwritten digit dataset.
- Preprocess the image data by normalizing pixel values.
- Build a neural network using TensorFlow and Keras.
- Train the model on the training dataset.
- Evaluate the model using the test dataset.
- Save the trained model for future use.

---

## Technologies Used
- Python 3.x
- TensorFlow
- Keras
- Matplotlib

---

## Libraries Required

Install the required libraries using:

```bash
pip install tensorflow matplotlib
```

---

## Dataset

The project uses the **MNIST Handwritten Digits Dataset**, which is built into TensorFlow.

- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 pixels
- Number of Classes: 10 (Digits 0–9)

---

## Project Workflow

### 1. Import Libraries
Import TensorFlow and Matplotlib for deep learning and image visualization.

### 2. Load Dataset
Load the MNIST dataset and automatically split it into training and testing datasets.

### 3. Data Preprocessing
Normalize pixel values from the range **0–255** to **0–1** to improve model performance.

### 4. Data Visualization
Display sample handwritten digit images using Matplotlib.

### 5. Build the Neural Network
The model consists of:
- Flatten Layer
- Dense Hidden Layer (128 neurons, ReLU activation)
- Dense Output Layer (10 neurons, Softmax activation)

### 6. Compile the Model
The model uses:
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Metric: Accuracy

### 7. Train the Model
Train the neural network using the training dataset for **3 epochs**.

### 8. Evaluate the Model
Test the trained model using unseen test images and calculate the accuracy.

### 9. Save the Model
Save the trained model for future predictions.

---

## Model Architecture

| Layer | Description |
|--------|-------------|
| Flatten | Converts 28×28 images into a 784-dimensional vector |
| Dense (128, ReLU) | Hidden layer for feature extraction |
| Dense (10, Softmax) | Output layer for digit classification |

---

## Expected Output

- Displays sample handwritten digit images.
- Trains the neural network.
- Prints training accuracy and loss.
- Evaluates model performance on the test dataset.
- Achieves approximately **97–98% accuracy**.
- Saves the trained model as:

```
my_mnist_model
```

---

## Project Structure

```
Handwritten-Digit-Recognition/
│
├── Assignment1.py
├── README.md
└── my_mnist_model/
```

---

## How to Run

1. Install the required libraries.

```bash
pip install tensorflow matplotlib
```

2. Run the Python program.

```bash
python Assignment1.py
```

3. The program will:
- Load the dataset
- Display a sample image
- Train the model
- Evaluate the model
- Save the trained model

---

## Learning Outcomes

- Understand TensorFlow and Keras.
- Learn image preprocessing techniques.
- Build and train a neural network.
- Evaluate model performance.
- Save and reuse trained machine learning models.

---

## Conclusion

This project successfully demonstrates handwritten digit recognition using TensorFlow and Keras. By training an Artificial Neural Network on the MNIST dataset, the model learns to classify handwritten digits with high accuracy. The implementation covers the complete deep learning pipeline, making it an excellent introductory project for understanding neural networks and image classification.

---

## Author

**Name:** Palash Sahuji  
**Course:** Artificial Intelligence Laboratory  
**Assignment:** Implementation of TensorFlow and Keras – Dataset Split, Training, and Evaluation
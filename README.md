# Digit_Classification_using_CNN
This project demonstrates the implementation of a Convolutional Neural Network (CNN) for classifying handwritten digits using the MNIST dataset. The model is built using Keras and TensorFlow, leveraging the power of deep learning for image recognition tasks.

## Key Features

- **Data Preprocessing:** The MNIST dataset is loaded and preprocessed, including reshaping and min-max scaling, to optimize model training.
- **CNN Architecture:** A carefully designed CNN architecture is employed, incorporating convolutional, pooling, and fully connected layers to extract features and perform classification.
- **Model Training and Evaluation:** The model is trained on the training data and evaluated on the testing data to assess its performance. Accuracy and loss metrics are used to gauge the model's effectiveness.
- **Visualization:** Matplotlib is used to visualize the handwritten digits and display the model's predictions.

---

## 📊 Dataset

The **MNIST dataset** consists of 70,000 grayscale images of handwritten digits (0-9):

- **Training Set:** 60,000 images
- **Test Set:** 10,000 images

Each image is a 28x28 pixel matrix, with each pixel representing grayscale intensity.

---

## 🚀 Methodology

1. **Data Preprocessing:**
   - Normalized pixel values to a range of 0 to 1.
   - Reshaped images to include the channel dimension (28x28x1).
   - One-hot encoded the labels.

2. **Model Architecture:**
   - Convolutional Layers: Extract spatial features using 32 and 64 filters.
   - Pooling Layers: Reduce spatial dimensions and computational complexity.
   - Dense Layers: Perform high-level reasoning for classification.
   - Softmax Output: Predicts probabilities for each class.

3. **Training:**
   - **Loss Function:** Categorical Cross-Entropy.
   - **Optimizer:** sgd.
   - **Metrics:** Accuracy.

4. **Evaluation:**
   - Assessed model performance on the test set.
   - Visualized misclassified examples for deeper insights.

---

## 📈 Results

- **Training Accuracy:** 99%
- **Validation Accuracy:** 98%
- **Test Accuracy:** 98%

# Handwritten-Digit-Recognition-using-Deep-Learning
Handwritten Digit Recognition using Convolutional Neural Networks (CNN)

This project focuses on building a Convolutional Neural Network (CNN) model that can accurately recognize handwritten digits (0–9) from images. The model is trained on a custom dataset of 1000 grayscale images, aiming to achieve high accuracy while demonstrating the effectiveness of CNNs for image classification tasks.

⭐ Project Overview

Handwritten digit recognition is a classical problem in the fields of computer vision, machine learning, and pattern recognition. This project implements a CNN-based approach to classify handwritten digits, offering improved performance over traditional ML methods such as SVMs and ANN.

This model achieves an accuracy of ~91–92%, demonstrating strong performance on a custom dataset.

📌 Key Features

-->Custom dataset containing 1000 images of handwritten digits.

-->Preprocessing includes scaling, reshaping, and normalization.

-->CNN architecture implemented using TensorFlow and Keras.

-->Comparison of CNN with traditional approaches (SVM, ANN, K-Means, etc).

-->Visualization of digit samples, pixel representation, convolution operations, pooling, and network layers.

-->Final model trained on 80% training data and 20% testing data.

🧠 Why CNN?

Traditional machine learning algorithms like SVM, KNN, or ANN perform poorly on large image datasets due to:

-->High computational complexity

-->Difficulty capturing spatial information

-->Lack of feature extraction capabilities

-->CNNs overcome these limitations through:

-->Convolutional layers for feature extraction

-->Pooling layers for dimensionality reduction

-->Automatic feature learning

-->High scalability and accuracy

🏗️ System Architecture:

Dataset → Preprocessing → CNN Model → Training → Testing → Prediction

CNN Workflow Includes:

-->Convolution Layers

-->ReLU Activation

-->Max Pooling

-->Flattening

-->Fully Connected Layers

-->Softmax Output Layer

🔧 Technologies Used

-->Python

-->TensorFlow / Keras

-->scikit-learn

-->NumPy

-->Matplotlib

🧩 Model Architecture
Input: 28x28 grayscale image
    ↓
Conv2D (15 filters, 3x3, ReLU)
    ↓
MaxPooling2D (2x2)
    ↓
Flatten
    ↓
Dense (128 units, ReLU)
    ↓
Dense (10 units, Softmax)

📂 Dataset Details

Total images: 1000

Image dimension: 28×28 grayscale

Train–Test split: 80% train (800 images), 20% test (200 images)


📊 Results

Training Accuracy: ~92%

Testing Accuracy: ~91.4%

Successfully predicts digits from 0 to 9

CNN performs significantly better than SVM, ANN, K-Means, and Naive Bayes on this dataset

📌 Conclusion

This project demonstrates the effectiveness of Convolutional Neural Networks in image classification tasks such as handwritten digit recognition. The CNN model automatically learns distinguishing features and significantly outperforms traditional machine learning methods.

With further tuning, data augmentation, and larger datasets (like MNIST), accuracy can be further improved to near state-of-the-art levels.

📁 Future Enhancements

Extend model to recognize handwritten letters (A–Z)

Add data augmentation for improved generalization

Deploy model as a web application using Flask or Streamlit

Convert the model to TensorFlow Lite for mobile deployment

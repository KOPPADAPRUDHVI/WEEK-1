**Plastic Waste Classification using CNN**

📌 Project Overview

This project utilizes a Convolutional Neural Network (CNN) to classify images of plastic waste into two categories: Organic and Recyclable. The model is trained using a dataset of waste images and helps automate waste classification, improving waste management efficiency.

🎯 Learning Objectives

Develop a CNN-based image classification model.

Utilize TensorFlow and Keras for deep learning.

Preprocess image data using OpenCV and ImageDataGenerator.

Train, validate, and test the model on a waste classification dataset.

Evaluate model performance using accuracy and loss metrics.

🛠️ Tools and Technologies Used

Programming Language: Python

Libraries: TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib

Deep Learning Framework: Convolutional Neural Network (CNN)

Dataset: Waste Classification Dataset

Data Augmentation: ImageDataGenerator

📌 Dataset

The dataset consists of images categorized as:

Organic Waste (O): Biodegradable waste items.

Recyclable Waste (R): Items that can be recycled, such as plastic bottles.

Paths to dataset:

train_path = "/root/.cache/kagglehub/datasets/techsash/waste-classification-data/versions/1/DATASET/TRAIN"
test_path = "/root/.cache/kagglehub/datasets/techsash/waste-classification-data/versions/1/DATASET/TEST"

🚀 Methodology

Data Collection: Images of plastic waste are collected and categorized.

Data Preprocessing: Images are resized, normalized, and augmented.

Model Building: A CNN architecture is designed with Conv2D, MaxPooling, Flatten, Dense, and Dropout layers.

Training & Validation: The model is trained using ImageDataGenerator with real-time augmentation.

Performance Evaluation: Accuracy and loss are plotted to analyze the model’s effectiveness.

Prediction: The trained model is tested on new images for classification.

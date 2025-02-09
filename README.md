# Waste Classification Using CNN

## Overview
This project focuses on classifying waste images into two categories: **Organic** and **Recyclable**, using a **Convolutional Neural Network (CNN)**. The dataset consists of images labeled into these categories, and the model is trained to distinguish between them effectively.

## Learning Objectives
- Understand and implement image classification using CNN.
- Utilize **TensorFlow** and **Keras** for deep learning model development.
- Perform data preprocessing and augmentation for improved model accuracy.
- Evaluate model performance using visualization techniques.

## Tools and Technologies Used
- **Python**
- **TensorFlow/Keras**
- **OpenCV**
- **NumPy & Pandas**
- **Matplotlib**
- **ImageDataGenerator** (for image augmentation)

## Dataset
The dataset used for training and testing is sourced from Kaggle and consists of labeled images of waste materials. It is structured into **TRAIN** and **TEST** directories, each containing images categorized as **Organic** and **Recyclable**. 
[Link for the Dataset](https://www.kaggle.com/datasets/techsash/waste-classification-data)

## Methodology
1. **Data Preprocessing**
   - Loading and resizing images to a standard shape (**224x224** pixels).
   - Normalizing image pixel values for efficient learning.
   - Augmenting training images to improve model generalization.
   
2. **Model Development**
   - Building a **Sequential CNN** model with multiple convolutional layers.
   - Using **ReLU** activation for feature extraction.
   - Applying **MaxPooling** to reduce spatial dimensions.
   - Adding **Fully Connected Layers** for classification.
   - Using **Sigmoid activation** for binary classification.
   
3. **Model Compilation and Training**
   - Compiling the model with **Adam optimizer** and **binary cross-entropy loss**.
   - Training the model using the **ImageDataGenerator**.
   - Evaluating model performance on test data.

## Results and Visualization
- The training and validation accuracy/loss are plotted to analyze model performance.
- Sample images from the dataset are visualized with their predicted labels.
- The model is tested on unseen images to verify its classification ability.

## Conclusion
- The CNN model effectively classifies waste images into **Organic** and **Recyclable** categories.
- Data augmentation improves model generalization and prevents overfitting.
- The project demonstrates the potential of **Deep Learning** in environmental sustainability by aiding waste management.

## Future Enhancements
- Expanding the dataset with more diverse waste categories.
- Implementing a more complex model like **ResNet** for improved accuracy.
- Deploying the model as a web or mobile application for real-world usability.

## Author
**Koppada Prudhvi Vinayak**

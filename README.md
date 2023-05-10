# Face Recognition using PCA and SVM

This repository contains code for performing face recognition using Principal Component Analysis (PCA) and Support Vector Machine (SVM) classifier. It utilizes the Labeled Faces in the Wild (LFW) dataset for training and testing.

## Model Overview

The face recognition pipeline consists of the following steps:

1. **Data Preprocessing**: The input face images are standardized using the StandardScaler to improve the performance of the model.

2. **Dimensionality Reduction**: Principal Component Analysis (PCA) is applied to the standardized data to reduce the dimensionality. The top principal components, called eigenfaces, are extracted and used to represent the face images.

3. **Classification**: The reduced-dimensional face images are fed into a Support Vector Machine (SVM) classifier with a radial basis function (RBF) kernel. The classifier is trained to recognize different individuals based on the extracted features.

4. **Evaluation**: The trained model is evaluated on a separate test set. Classification metrics such as precision, recall, and F1-score are computed to assess the model's performance. Additionally, a confusion matrix is generated to visualize the classification results.

## Usage
Run the code in colab
This will execute the face recognition pipeline using PCA and SVM on the LFW dataset.

### View the results:

The classification report, confusion matrix, and image galleries will be displayed in the console.

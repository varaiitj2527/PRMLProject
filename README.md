#  **CSL2050 - Pattern Recognition and Machine Learning**  
##  *Course Project: Image Retrieval using Machine Learning*  
[![GitHub Repo](https://img.shields.io/badge/PRML%20Project-GitHub-blue)](https://github.com/varaiitj2527/PRMLProject/tree/main)
## Team Members
-  **Vara Prasad Reddy(B23CM1057)**  
- **Yadav Karan Subhashchandra(B23EE1103)**  
- **Priyanshu(B23CS1097)**  
- **Neeraj Mansingh(B23CS1095)**  
- **Kalkar TEJAS PREASAD(B23CM1051)**  
- **Kondakandla Manideep(B23CS1026)**

## Project Description

This project is developed as part of the course **CSL2050 - Pattern Recognition and Machine Learning**, focused on solving the **Image Retrieval** problem using various machine learning techniques. The main objective is to classify images from the **CIFAR-10 dataset** and retrieve similar images based on the input query.

The dataset consists of 60,000 32x32 color images in 10 different classes, with 50,000 for training and 10,000 for testing. Since raw image data is not directly suitable for most ML algorithms, **feature extraction** was a major focus of our work. We explored multiple techniques including **PCA**, **HOG**, and **QuickNet**, but **ResNet-based deep feature extraction** produced the most informative and discriminative features.

Once the features were extracted, we trained multiple classifiers including:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Artificial Neural Network (ANN)
- SVM
- XGBOAST

Among all combinations, the **ResNet + ANN** pipeline achieved the **highest accuracy and performance**. This is because ResNet (a deep convolutional network) is capable of capturing high-level abstract features, which when passed to an **Artificial Neural Network**, helped it learn complex patterns and non-linear decision boundaries more effectively than traditional ML models.


 Dataset
We used the **CIFAR-10** dataset:
- 50,000 training images  
- 10,000 testing images  
- 10 categories including: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

---

##  Preprocessing & Feature Extraction
We explored and compared different feature extraction techniques:
-  **ResNet**
-  **PCA (Principal Component Analysis)**
-  **HOG + PCA**
-  **QuickNet**
-  **PCA + HOG**
-  **HOG**
-  **EDA**

---

##  Models Evaluated
Each set of features was passed into multiple machine learning models:
-  Artificial Neural Network (**ANN**)  
-  Bayesian Classifier  
-  Clustering  
-  Decision Tree  
-  Logistic Regression  
-  K-Nearest Neighbors (**KNN**)  
-  Random Forest
-  SVM
-  Xgboast 

---

## Best Performing Configuration
**ResNet + ANN** achieved the best accuracy of **89%**, and was used in the final deployed application.

---

## Frontend Integration
A user-friendly frontend was developed to allow image uploads and display the top-5 most similar images.

###  Example:  

 ![WhatsApp Image 2025-04-10 at 19 52 20](https://github.com/user-attachments/assets/a3e65085-4009-46cc-8781-6aa70f61bd9c)


`
- **Predicted Class**: 5  
- **Top 5 Matches**: All belong to label 5 (dog)

Results confirm accurate retrieval based on learned features.

---

## Objective
- Compare different **feature extraction** techniques  
- Evaluate various **machine learning models**  
- Integrate everything into an end-to-end **image retrieval system**

---

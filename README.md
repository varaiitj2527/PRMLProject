#  **CSL2050 - Pattern Recognition and Machine Learning**  
##  *Course Project: Image Retrieval using Machine Learning*  
[![GitHub Repo](https://img.shields.io/badge/PRML%20Project-GitHub-blue)](https://github.com/varaiitj2527/PRMLProject/tree/main)
## Team Members
- **S Vara Prasad Reddy(B23CM1057)**  
- **Yadav Karan Subhashchandra(B23EE1103)**
- **Kodakandla Manideep(B23CS1026)**
- **Priyanshu(B23CS1097)**  
- **Neeraj Mansingh(B23CS1095)**  
- **Kalkar Tejas Prasad(B23CM1051)**  


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
- XGboost

Among all combinations, the **ResNet + ANN** pipeline achieved the **highest accuracy and performance**. This is because ResNet (a deep convolutional network) is capable of capturing high-level abstract features, which when passed to an **Artificial Neural Network**, helped it learn complex patterns and non-linear decision boundaries more effectively than traditional ML models.

**Repository Structure**
```bash
.
├── Cifar10Dataset/           # Original dataset files
├── Model/                    # Contains trained models and architecture definitions
├── PreProcessedData/         # Vectorized and transformed datasets (.pkl files)
├── EDA.ipynb                 # Exploratory Data Analysis on CIFAR-10
├── FeatureExtraction.ipynb   # Feature extraction using HOG, QuickNet, PCA, ResNet
├── Resnet.ipynb              # Deep feature extraction using ResNet
├── README.md                 # Project documentation
├── Report.pdf                # Final project report with complete analysis
├── presentation.pdf          # Project presentation slides
```

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
-  XGboost 

---

## Best Performing Configuration
**ResNet + ANN** achieved the best accuracy of **89%**, and was used in the final deployed application.

---

## Frontend Integration
A user-friendly frontend was developed to allow image uploads and display the top-5 most similar images.

<p align="center">
  <img src="https://github.com/user-attachments/assets/6a38c290-02d4-41c4-8f79-6057802e2b1c" alt="Result 1" width="400" height="400" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/cae3e034-7789-4f42-99ae-593f7cb73ee5" alt="Result 2" width="400" height="400"/>
</p>

<p align="center"><b>Results confirm accurate retrieval based on learned features.</b></p>
 learned features.</b></p>

---
**How to Run the Demo**






---
## Objective
- Compare different **feature extraction** techniques  
- Evaluate various **machine learning models**  
- Integrate everything into an end-to-end **image retrieval system**

---

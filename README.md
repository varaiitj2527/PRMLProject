# 🧠 Image Retrieval using Feature Extraction & Machine Learning  
[![GitHub Repo](https://img.shields.io/badge/PRML%20Project-GitHub-blue)](https://github.com/varaiitj2527/PRMLProject/tree/main)

## 👨‍💻 Team Members
-  **Vara Prasad Reddy**  
- **Yadav Karan Subhashchandra**  
- **Priyanshu**  
- **Neeraj Mansingh**  
- **Tejas Kalkar**  
- **Manideep**

---

📁 Dataset
We used the **CIFAR-10** dataset:
- 50,000 training images  
- 10,000 testing images  
- 10 categories including: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

---

## 🧪 Preprocessing & Feature Extraction
We explored and compared different feature extraction techniques:
- 🔬 **ResNet**
- 📉 **PCA (Principal Component Analysis)**
- 🧿 **HOG + PCA**
- ⚡ **QuickNet**
- 🧿 **PCA + HOG**

---

## 🤖 Models Evaluated
Each set of features was passed into multiple machine learning models:
- 🔁 Artificial Neural Network (**ANN**)  
- 🧠 Bayesian Classifier  
- 🧩 Clustering  
- 🌲 Decision Tree  
- 📈 Logistic Regression  
- 🧭 K-Nearest Neighbors (**KNN**)  
- 🌳 Random Forest  

---

## 🏆 Best Performing Configuration
🎯 **ResNet + ANN** achieved the best accuracy of **89%**, and was used in the final deployed application.

---

## 🌐 Frontend Integration
A user-friendly frontend was developed to allow image uploads and display the top-5 most similar images.

### 📸 Example:  
#### 🐶 `dogtestn.jpg`
- **Predicted Class**: 5  
- **Top 5 Matches**: All belong to label 5 (dog)

#### 🐕 `gdog.jpg`
- **Predicted Class**: 5  
- **Top 5 Matches**: All belong to label 5 (dog)

✅ Results confirm accurate retrieval based on learned features.

---

## 📌 Objective
- Compare different **feature extraction** techniques  
- Evaluate various **machine learning models**  
- Integrate everything into an end-to-end **image retrieval system**

---

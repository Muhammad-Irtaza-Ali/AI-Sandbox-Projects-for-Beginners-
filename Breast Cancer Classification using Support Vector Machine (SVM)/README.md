# 🎗️ Breast Cancer Classification using Support Vector Machine (SVM)  

This project implements **Support Vector Machine (SVM)** for **breast cancer classification** using the **Breast Cancer Wisconsin dataset**. It includes **data preprocessing, model training, hyperparameter tuning using RandomizedSearchCV, and accuracy evaluation**.  

## 📌 Overview  
- 📊 **Dataset**: Breast Cancer Wisconsin (from `sklearn.datasets`)  
- 🏷️ **Target Classes**:  
  - `0` → Malignant (cancerous)  
  - `1` → Benign (non-cancerous)  
- 🔎 **Goal**: Classify tumors as malignant or benign using **SVM**  

## ⚙️ Project Workflow  
1️⃣ **Load Dataset**  
2️⃣ **Data Preprocessing & Exploration**  
3️⃣ **Train/Test Split (70%-30%)**  
4️⃣ **Train SVM Model** with manually selected hyperparameters  
5️⃣ **Evaluate Model Performance**  
6️⃣ **Hyperparameter Tuning** using **RandomizedSearchCV**  
7️⃣ **Find the Best Model** and Evaluate Accuracy  

## 📊 Data Preprocessing  
✔️ Check for **missing values**  
✔️ Convert dataset to **Pandas DataFrame**  
✔️ Split into **train and test sets** (`70% training, 30% testing`)  

## 🤖 Model Training  
- Uses **Support Vector Classifier (SVC)** with **linear kernel**  
- Hyperparameters:  
  - `C=1` (Regularization parameter)  
  - `gamma=0.01` (Kernel coefficient)  
  - `kernel='linear'`  

## 🔍 Hyperparameter Tuning (RandomizedSearchCV)  
- Searches for the **best hyperparameters** from:  
  - Kernels: `linear, poly, rbf, sigmoid`  
  - C values: `[0.1, 1, 10]`  
  - Gamma values: `[0.00001, 0.0001, 0.001, 0.01, 0.1]`  
- Uses **3-fold cross-validation** with **5 iterations**  

## 🚀 How to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install numpy pandas scikit-learn
   ```
2️⃣ Run the Python script:  
   ```bash
   python breast_cancer_svm.py
   ```
3️⃣ View accuracy and best parameters from **RandomizedSearchCV**  

## 📈 Expected Output  
✔️ **Model Accuracy** (before tuning)  
✔️ **Best Parameters & Accuracy** (after tuning)  

## 🔥 Key Takeaways  
✅ **SVM is effective for classification problems**  
✅ **Hyperparameter tuning improves model performance**  
✅ **RandomizedSearchCV speeds up parameter search**  

## 👤 Author  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  

# 🏥 Diabetes Prediction using Logistic Regression  

This project **analyzes and predicts diabetes** using the **Pima Indians Diabetes Dataset (pdiabetes.csv)**. The goal is to explore data patterns and train a **Logistic Regression model** to classify whether a patient has diabetes or not.  

## 📌 Overview  
✔️ **Data Visualization**  
✔️ **Preprocessing & Scaling**  
✔️ **Model Training (with & without scaling)**  
✔️ **Model Evaluation**  
✔️ **Prediction on Sample Patients**  

## 📊 Dataset Details  
The dataset includes medical attributes such as:  
- **Pregnancies**  
- **Glucose Level**  
- **Blood Pressure**  
- **Skin Thickness**  
- **Insulin**  
- **BMI (Body Mass Index)**  
- **Diabetes Pedigree Function**  
- **Age**  
- **Outcome (1 = Diabetic, 0 = Non-Diabetic)**  

## 🚀 Project Workflow  
### 1️⃣ **Exploratory Data Analysis (EDA)**  
- Display first few rows.  
- **Count** of diabetic vs. non-diabetic patients.  
- **Bar chart** visualization.  
- Filtering **patients over 40** with diabetes.  

### 2️⃣ **Data Preprocessing**  
- Split dataset into **features (X) & target (y)**.  
- **Train-Test split (80-20%)**.  
- **Scaling the data** using `StandardScaler` for better performance.  

### 3️⃣ **Model Training & Evaluation**  
- Train **Logistic Regression** model with **& without scaling**.  
- Compute **accuracy** of both models.  

### 4️⃣ **Sample Predictions**  
- Select test samples and **predict diabetes status**.  

## 🔢 Results  
✔️ **Accuracy without scaling**: `{accuracy_without_scaling*100:.2f}%`  
✔️ **Accuracy with scaling**: `{accuracy_with_scaling*100:.2f}%`  

✅ **Sample Predictions:**  
- **Sample 1:** `{Diabetic / Non-Diabetic}`  
- **Sample 2:** `{Diabetic / Non-Diabetic}`  

## 📦 Installation & Usage  
1️⃣ Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```  
2️⃣ Run the Python script:  
   ```bash
   python diabetes_prediction.py
   ```  

## 📊 Key Insights  
✔️ **Feature scaling improves model accuracy**.  
✔️ **Older individuals have a higher chance of diabetes**.  
✔️ **Logistic Regression is effective for binary classification**.  

## 👤 Author  
Maintained by **Muhammad Irtaza Ali** as part of his AI & ML learning journey.  

📌 **Happy Coding! 🚀**  
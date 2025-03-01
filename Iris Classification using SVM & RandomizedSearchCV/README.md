# 🌸 **Iris Classification using SVM & RandomizedSearchCV**  

This project implements **Support Vector Machine (SVM)** classification on the famous **Iris dataset**. We optimize hyperparameters using **RandomizedSearchCV** to find the best model configuration.  

---

## 📌 **Overview**  
- The **Iris dataset** consists of **150 samples** of **3 species**: Setosa, Versicolor, and Virginica.  
- We use **SVM** for classification and tune hyperparameters with **RandomizedSearchCV**.  

---

## 📂 **Project Structure**  
✔️ **Dataset:** `sklearn.datasets.load_iris()`  
✔️ **Preprocessing:** Train-Test Split (`70% - 30%`)  
✔️ **Model:** Support Vector Machine (`SVC`)  
✔️ **Hyperparameter Tuning:** `RandomizedSearchCV`  
✔️ **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report  

---

## 🔧 **Dependencies**  
Install the required Python libraries:  
```bash
pip install numpy scikit-learn
```

---

## 🚀 **How to Run**  
1️⃣ **Load the dataset**  
2️⃣ **Split the data** into training and testing sets  
3️⃣ **Use RandomizedSearchCV** to optimize SVM hyperparameters  
4️⃣ **Train the model** on the best parameters  
5️⃣ **Evaluate performance** using accuracy, confusion matrix, and classification report  

Run the script:  
```bash
python iris_svm.py
```

---

## 🎯 **Hyperparameter Tuning**  
We use **RandomizedSearchCV** with the following search space:  

| Hyperparameter | Values |
|---------------|--------|
| `kernel`      | linear, poly, rbf, sigmoid |
| `C`           | 0.1, 1, 10 |
| `gamma`       | 0.00001, 0.0001, 0.001, 0.01, 0.1 |

Best hyperparameters are printed after training.

---

## 📊 **Model Evaluation**  
✔️ **Accuracy Score**  
✔️ **Confusion Matrix**  
✔️ **Classification Report**  

**Example Output:**  
```
Best Parameters: {'kernel': 'rbf', 'C': 10, 'gamma': 0.01}
Best Accuracy: 0.98
Test Accuracy: 0.977
```

---

## 👤 **Author**  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  


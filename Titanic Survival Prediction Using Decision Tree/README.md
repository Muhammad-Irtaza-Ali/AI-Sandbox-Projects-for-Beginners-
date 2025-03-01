# 🌳 Titanic Survival Prediction Using Decision Tree  

This project applies a **Decision Tree Classifier** to predict survival on the Titanic dataset. It explores **model tuning**, **visualization**, and **hyperparameter optimization** to improve performance.

## 📌 Overview  
- Loads and **preprocesses data**.  
- Splits data into **training and validation sets**.  
- Builds and **trains a Decision Tree model**.  
- **Optimizes the tree depth** for better accuracy.  
- **Visualizes the decision tree** using `graphviz`.  

## 📊 Dataset  
The dataset (`data_cleaned.csv`) includes:  
✔️ **Features**: Passenger attributes (age, fare, class, etc.).  
✔️ **Target Variable**: `Survived` (1 = Yes, 0 = No).  

## ⚙️ Steps  
### 1️⃣ Load & Preprocess Data  
- Check for missing values.  
- Split dataset into **training (75%)** and **validation (25%)** sets.  
- Ensure balanced class distribution.  

### 2️⃣ Train a Decision Tree Model  
- Train an initial **DecisionTreeClassifier**.  
- Evaluate performance using `accuracy_score`.  

### 3️⃣ Optimize Model Parameters  
- Tune `max_depth` and `max_leaf_nodes` to prevent overfitting.  
- Plot training vs validation accuracy.  

### 4️⃣ Visualize the Decision Tree  
- Export tree structure using `graphviz`.  
- Generate a **decision tree plot** (`tree.png`).  

## 🚀 How to Run  
1️⃣ Install required dependencies:  
   ```bash
   pip install pandas numpy matplotlib scikit-learn graphviz
   ```
2️⃣ Run the Python script:  
   ```bash
   python decision_tree.py
   ```
3️⃣ View the **decision tree visualization** (`tree.png`).  

## 📈 Model Performance  
✔️ **Initial Model Accuracy**  
- Training Accuracy: ~X%  
- Validation Accuracy: ~Y%  

✔️ **Optimized Model Accuracy**  
- Training Accuracy: ~A%  
- Validation Accuracy: ~B%  

## 📌 Key Learnings  
✔️ **Decision trees are interpretable but prone to overfitting.**  
✔️ **Hyperparameter tuning improves generalization.**  
✔️ **Graph visualization helps in understanding model decisions.**  

## 👤 Author  
Maintained by **Muhammad Irtaza Ali** as part of his AI coursework.  

📌 **Happy Coding! 🚀**  


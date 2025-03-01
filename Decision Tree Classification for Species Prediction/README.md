# 🌳 Decision Tree Classification for Species Prediction  

This project implements a **Decision Tree Classifier** to predict species classification using **Train.csv** and **Test.csv** datasets.  

## 📌 Overview  
- **Data Preprocessing**: Loading, checking for missing values, and exploring the dataset.  
- **Model Training**: Training a **Decision Tree Classifier**.  
- **Hyperparameter Tuning**: Finding the best tree depth using validation accuracy.  
- **Visualization**: Plotting accuracy vs. depth and generating a decision tree graph.  

---

## 📂 Dataset  
- `Train.csv` → Used to train the model.  
- `Test.csv` → Used for testing and validation.  
- The dataset contains numerical features and a **Class** column (target variable).  

## 🏗️ Steps  

### 1️⃣ **Data Exploration**  
✔️ Load `Train.csv` and `Test.csv`.  
✔️ Check missing values, dataset shape, and summary statistics.  
✔️ Identify **unique species** in the dataset.  

### 2️⃣ **Feature Selection**  
✔️ **X** (Features): All columns except `Class`.  
✔️ **y** (Target): The `Class` column.  

### 3️⃣ **Model Training**  
✔️ **Decision Tree Classifier** is trained on the dataset.  
✔️ Compute **train accuracy** and **test accuracy**.  

### 4️⃣ **Hyperparameter Tuning**  
✔️ **Train-Validation Split** (75% training, 25% validation).  
✔️ **Finding Best Depth**:  
   - Train model with different **tree depths (1-10)**.  
   - Store **train accuracy** and **validation accuracy**.  
   - **Plot Accuracy vs. Tree Depth** to select the best depth.  

### 5️⃣ **Decision Tree Visualization**  
✔️ Export decision tree as `tree.dot`.  
✔️ Convert it to **PNG** and display it using Matplotlib.  

---

## 📊 Results  
- **Optimal Depth**: The best tree depth is selected based on the validation set.  
- **Final Model**: A pruned tree with `max_depth=6` and `max_leaf_nodes=25`.  

---

## 🚀 How to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install pandas matplotlib scikit-learn
   ```  
2️⃣ Run the Python script.  
3️⃣ View accuracy scores and the **Decision Tree visualization**.  

---

## 📌 Key Learnings  
✔️ **Decision Trees can overfit** if the depth is too high.  
✔️ **Hyperparameter tuning** helps improve generalization.  
✔️ **Tree visualizations** help in understanding feature importance.  

---

## 👤 Author  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  


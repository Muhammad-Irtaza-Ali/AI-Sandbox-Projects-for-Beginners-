# 🌸 Iris Dataset Classification using Decision Tree  

This project demonstrates **classification of the Iris dataset** using a **Decision Tree Classifier**. The model predicts the species of an iris flower based on its **sepal and petal dimensions**.  

## 📌 Overview  
✔ **Dataset**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)  
✔ **Algorithm**: Decision Tree Classifier  
✔ **Libraries Used**: Pandas, Scikit-Learn  
✔ **Evaluation Metrics**: Accuracy Score, Classification Report, Confusion Matrix  

## 📂 Dataset Details  
The dataset contains **150 samples** of iris flowers categorized into three species:  
1️⃣ **Iris-setosa**  
2️⃣ **Iris-versicolor**  
3️⃣ **Iris-virginica**  

**Features:**  
- 🌿 **Sepal Length**  
- 🌿 **Sepal Width**  
- 🌸 **Petal Length**  
- 🌸 **Petal Width**  

## 🏗️ Project Workflow  

1️⃣ **Load and Preprocess Data**  
   - Read CSV file using Pandas  
   - Assign column names  
   - Handle missing values  
   - Encode categorical labels  

2️⃣ **Exploratory Data Analysis (EDA)**  
   - Check for null values  
   - Count unique values in the **Species** column  
   - Get min, max, and frequency counts of values  

3️⃣ **Train a Decision Tree Classifier**  
   - Split data into **training (80%)** and **testing (20%)** sets  
   - Train a **Decision Tree Classifier**  

4️⃣ **Make Predictions**  
   - Predict species using the trained model  
   - Convert encoded predictions back to species names  

5️⃣ **Evaluate Model Performance**  
   - Compute **Accuracy Score**  
   - Display **Classification Report**  
   - Generate a **Confusion Matrix**  

## 🚀 How to Run  

1️⃣ Install dependencies:  
   ```bash
   pip install pandas scikit-learn
   ```
2️⃣ Place `iris.csv` in the working directory.  
3️⃣ Run the Python script.  
4️⃣ View classification results and model performance metrics.  

## 📊 Results  
- The **accuracy** of the Decision Tree Classifier is approximately **98%**.  
- The model effectively classifies iris flowers into the correct species.  

## 📌 Key Takeaways  
✔ **Decision Trees provide an interpretable classification method.**  
✔ **Iris dataset is well-suited for ML beginners to understand classification problems.**  
✔ **High accuracy is achieved due to the dataset's clean and structured nature.**  

## 👤 Author  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  

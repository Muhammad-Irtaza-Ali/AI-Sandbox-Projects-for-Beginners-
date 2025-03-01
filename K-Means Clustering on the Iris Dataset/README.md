# 🌸 K-Means Clustering on the Iris Dataset  

This project applies **K-Means clustering** to the **Iris dataset** to find natural groupings in the data. The **Elbow Method** is used to determine the optimal number of clusters.  

## 📌 Overview  
- **Dataset**: [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris)  
- **Algorithm**: K-Means Clustering  
- **Goal**: Identify the optimal number of clusters using the **Elbow Method** and visualize the results.  

## 🚀 Steps in the Project  
1️⃣ **Load the Dataset**  
2️⃣ **Apply K-Means Clustering**  
3️⃣ **Use the Elbow Method** to determine the best value of `k`  
4️⃣ **Train the model** with the optimal `k`  
5️⃣ **Print final clustering score**  

## 📊 The Elbow Method  
To find the best number of clusters, we calculate **inertia (sum of squared distances)** for different values of `k`. The **Elbow Point** is where adding more clusters does not significantly decrease inertia.  

### 🔹 Inertia Formula  
\[
\text{Inertia} = \sum (\text{distance of each point from its cluster center})^2
\]  

## ⚙️ How to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install numpy pandas matplotlib scikit-learn
   ```
2️⃣ Run the script in Python.  
3️⃣ Observe the **Elbow Method Graph**.  
4️⃣ The model finds **4 clusters** as optimal.  

## 🏆 Key Takeaways  
✔️ K-Means is useful for **unsupervised learning**.  
✔️ The **Elbow Method** helps find the best `k`.  
✔️ The **Iris dataset naturally groups into 3-4 clusters**.  

## 👤 Author  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Clustering! 🚀**  

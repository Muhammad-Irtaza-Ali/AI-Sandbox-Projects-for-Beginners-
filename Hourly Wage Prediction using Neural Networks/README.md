# 💰 Hourly Wage Prediction using Neural Networks  

This project builds a **Deep Learning model** to predict hourly wages based on input features using **Keras** and **TensorFlow**.  

## 📌 Overview  
- The dataset contains **various features** affecting hourly wages.  
- A **Fully Connected Neural Network (FNN)** is built using **Keras Sequential API**.  
- The model is trained using the **Adam optimizer** with **Mean Squared Error (MSE)** as the loss function.  

## 📂 Dataset  
The dataset (`hourly_wages.csv`) is loaded using Pandas and structured as:  
- `X`: All features except the target variable (**wage_per_hour**).  
- `y`: The target variable (**wage_per_hour**).  

## 🏗️ Model Architecture  
✔️ **Input Layer**: Accepts `n` numerical features.  
✔️ **Hidden Layers**:  
   - 128 neurons, **ReLU activation**  
   - 64 neurons, **ReLU activation**  
   - 32 neurons, **ReLU activation**  
✔️ **Output Layer**: 1 neuron (for regression prediction).  

## 🚀 Steps to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install tensorflow pandas matplotlib seaborn
   ```
2️⃣ Load the dataset (`hourly_wages.csv`).  
3️⃣ Train the **Neural Network model** using `model.fit()`.  
4️⃣ Evaluate performance using **Mean Squared Error (MSE)**.  

## 📊 Results & Visualization  
- The trained model predicts hourly wages based on input data.  
- Further tuning (e.g., adding more layers, changing activation functions) can improve accuracy.  

## 🏆 Key Takeaways  
✔️ **Deep learning can be used for regression tasks.**  
✔️ **MSE is a good loss function for continuous numerical predictions.**  
✔️ **Feature scaling might further improve performance.**  

## 👤 Author  
This project is created by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  

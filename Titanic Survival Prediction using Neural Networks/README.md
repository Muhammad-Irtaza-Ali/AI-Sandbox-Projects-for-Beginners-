# 🚢 Titanic Survival Prediction using Neural Networks  

This project implements a **Deep Learning model** using **Keras and TensorFlow** to predict passenger survival on the Titanic.  

## 📌 Overview  
- The dataset (`titanic_all_numeric.csv`) contains numerical features related to passengers.  
- A **Fully Connected Neural Network (FNN)** is trained to classify passengers as **survived (1) or not (0)**.  
- The model uses the **softmax activation function** for binary classification.  

## 📂 Dataset  
The dataset consists of:  
- `X`: All features except the target variable (**survived**).  
- `y`: Target variable (**0 = Not Survived, 1 = Survived**).  
- `output_matrix`: One-hot encoded labels for classification.  

## 🏗️ Model Architecture  
✔️ **Input Layer**: Accepts `n` numerical features.  
✔️ **Hidden Layers**:  
   - 128 neurons, **ReLU activation**  
   - 64 neurons, **ReLU activation**  
   - 32 neurons, **ReLU activation**  
   - 16 neurons, **ReLU activation**  
   - 8 neurons, **ReLU activation**  
✔️ **Output Layer**: 2 neurons, **Softmax activation** (for binary classification).  

## 🚀 Steps to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install tensorflow pandas matplotlib seaborn
   ```
2️⃣ Load the dataset (`titanic_all_numeric.csv`).  
3️⃣ Preprocess the labels using **one-hot encoding** (`to_categorical`).  
4️⃣ Train the **Neural Network model** using `model.fit()`.  
5️⃣ Evaluate performance using **Categorical Crossentropy Loss**.  

## 📊 Results & Visualization  
- The trained model predicts **passenger survival probabilities**.  
- Further improvements (e.g., **feature selection, hyperparameter tuning**) can enhance accuracy.  

## 🏆 Key Takeaways  
✔️ **Deep learning is effective for classification problems.**  
✔️ **Softmax activation works well for multi-class classification.**  
✔️ **Feature engineering and data preprocessing are crucial for better predictions.**  

## 👤 Author  
This project is created by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  
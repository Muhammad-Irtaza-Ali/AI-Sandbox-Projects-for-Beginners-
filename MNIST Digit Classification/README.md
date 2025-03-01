# 🖥️ MNIST Digit Classification  

This project trains a **Neural Network (NN)** to classify handwritten digits from the **MNIST dataset** using **TensorFlow** and **Keras**.  

## 📌 Overview  
- The MNIST dataset consists of **70,000 grayscale images** of handwritten digits (0-9).  
- Each image is **28×28 pixels** and labeled with the corresponding digit.  
- A simple feedforward **neural network (NN)** is used to classify digits.  
- **Two models** are trained:  
  1️⃣ A basic NN with **one dense layer** (10 neurons, sigmoid activation).  
  2️⃣ An improved NN with **one hidden layer** (100 neurons, ReLU activation).  

## 📂 Dataset  
The dataset is loaded using `keras.datasets.mnist.load_data()`, which provides:  
- `X_train`, `y_train`: Training images & labels (60,000 samples)  
- `X_test`, `y_test`: Testing images & labels (10,000 samples)  

## 🚀 Steps to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install tensorflow matplotlib seaborn numpy
   ```
2️⃣ Open and run the script in Jupyter Notebook or a Python environment.  
3️⃣ The first model trains on **flattened images** (784 input neurons).  
4️⃣ The second model adds an **intermediate hidden layer** (100 neurons).  
5️⃣ Evaluate model accuracy and visualize predictions.  

## 📊 Results & Visualization  
- The trained model predicts digits with high accuracy.  
- A **confusion matrix** is plotted using Seaborn to analyze performance.  

## 🏆 Key Takeaways  
✔️ Data preprocessing is crucial (normalization improves performance).  
✔️ Adding hidden layers enhances accuracy.  
✔️ Softmax vs. Sigmoid: Sigmoid works but Softmax is better for multi-class classification.  

## 👤 Author  
This project is created by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  

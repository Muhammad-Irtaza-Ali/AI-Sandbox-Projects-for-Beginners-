# 🖼️ CIFAR-10 Image Classification with CNN  

This project implements a **Convolutional Neural Network (CNN)** to classify images from the **CIFAR-10 dataset** using **TensorFlow** and **Keras**.  

## 📌 Overview  
- The **CIFAR-10 dataset** consists of **60,000 color images (32x32 pixels) across 10 classes**.  
- A **CNN model** is built to recognize objects such as **airplanes, cars, birds, and more**.  
- The model is trained and evaluated for performance using **accuracy and loss metrics**.  

## 📂 Dataset  
The dataset is loaded using `keras.datasets.cifar10.load_data()`, which provides:  
- `X_train`, `y_train`: Training images & labels (**50,000 samples**)  
- `X_test`, `y_test`: Testing images & labels (**10,000 samples**)  

The dataset is **normalized** by scaling pixel values between **0 and 1** for better model performance.  

## 🏗️ Model Architecture  
The **CNN model** consists of:  
✔️ **3 Convolutional Layers** (`Conv2D`) with ReLU activation  
✔️ **2 Max Pooling Layers** (`MaxPooling2D`) for feature extraction  
✔️ **Flatten Layer** to convert features into a 1D array  
✔️ **Dense Layer (64 neurons, ReLU activation)** for learning patterns  
✔️ **Output Layer (Softmax activation, 10 classes)**  

## 🚀 Steps to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install tensorflow matplotlib seaborn numpy
   ```
2️⃣ Open and run the script in Jupyter Notebook or a Python environment.  
3️⃣ The model trains for **10 epochs** using the **Adam optimizer** and `sparse_categorical_crossentropy` loss.  
4️⃣ **Evaluate** the model’s performance on the test set.  
5️⃣ **Confusion Matrix** is plotted to analyze classification accuracy.  

## 📊 Results & Visualization  
- The trained CNN model **achieves high accuracy** in classifying CIFAR-10 images.  
- A **heatmap of the confusion matrix** is generated using Seaborn to visualize model predictions.  

## 🏆 Key Takeaways  
✔️ **CNNs are powerful** for image classification tasks.  
✔️ **More layers & filters improve feature extraction** but increase computation.  
✔️ **Normalization enhances training efficiency**.  

## 👤 Author  
This project is created by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  

# 🧠 Neural Network Forward Propagation  

This project demonstrates **forward propagation** in a simple **3-node hidden layer neural network**, with and without **activation functions**.  

## 📌 Overview  
- The network processes an **input array** `[1,1]`.  
- Weights are manually defined for each node.  
- The **output is computed** using different activation functions:  
  1️⃣ **Without Activation Function**  
  2️⃣ **With Tanh Activation**  
  3️⃣ **With ReLU Activation**  

## ⚙️ Network Structure  
✔️ **Input Layer**: `[1,1]`  
✔️ **Hidden Layer**: 3 nodes  
✔️ **Output Layer**: 1 node  

## 🔢 Computation  
### 🟢 **Without Activation Function**  
Each node computes a weighted sum:  
\[
\text{Node Output} = \sum (\text{Input} \times \text{Weight})
\]  
Final output is obtained by multiplying the **hidden layer output** with the **output weights**.  

### 🔵 **With Tanh Activation**  
Applies **tanh** function to introduce non-linearity:  
\[
\text{tanh}(x) = \frac{e^x - e^{-x}}{e^x + e^{-x}}
\]  

### 🔴 **With ReLU Activation**  
Applies **ReLU (Rectified Linear Unit)** function:  
\[
\text{ReLU}(x) = \max(0, x)
\]  

## 🚀 How to Run  
1️⃣ Install dependencies:  
   ```bash
   pip install numpy
   ```
2️⃣ Run the Python script.  
3️⃣ Observe **different outputs** based on the activation function used.  

## 📊 Key Takeaways  
✔️ **Activation functions help neural networks learn complex patterns.**  
✔️ **Tanh is useful for values centered around zero.**  
✔️ **ReLU is efficient and prevents vanishing gradients.**  

## 👤 Author  
This project is maintained by **Muhammad Irtaza Ali** as part of his AI learning journey.  

📌 **Happy Coding! 🚀**  



# Neural Network for Energy Gap Prediction (Eg(x, y))

## 📖 Project Overview
This mini project demonstrates how to use a **neural network** to predict the **energy gap Eg(x, y)** based on the compositions **x** and **y**.  
The goal is to build a simple regression model using **MLPRegressor (Multi-Layer Perceptron for regression)**

---

## ⚙️ Requirements

Make sure you have **Python 3.9+** installed, then install the following libraries before running the notebook.

### 🧩 Install Dependencies

In your **Jupyter Notebook**, create a new cell and run:
```python
!pip install numpy matplotlib scikit-learn
```

Or, from the terminal:
```bash
pip install numpy matplotlib scikit-learn
```

---

## 🧠 Model Description

- **Input:** 2 neurons (for x and y)  
- **Hidden Layers:** 2 fully connected (Dense) layers with ReLU activation  
- **Output:** 1 neuron (predicted Eg value)  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam  

The model is trained on synthetic data generated from the formula:

\[
E_g(x,y) = 1.35 + 0.668x - 1.068y + 0.758x^2 + 0.078y^2 - 0.069xy - 0.322x^2y + 0.03xy^2
\]

---

## 🚀 How to Run

1. Open the Jupyter Notebook file (`Eg_prediction.ipynb`).
2. Run the cell that installs the libraries.
3. Execute the code cells in order.
4. The output will show :
   - The real energy gap (mathematical formula)
   - The predicted energy gap (from the neural network)

---

## 🎯 Educational Goal
This project illustrates:
- The basic workflow of regression using neural networks.
- How to visualize and compare real vs. predicted data.
- The link between mathematical modeling and machine learning.

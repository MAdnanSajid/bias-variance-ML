# Polynomial Regression & Bias–Variance Analysis

## Project Description

This project demonstrates **Polynomial Regression** and analyzes the **Bias–Variance tradeoff** using synthetic data.  
The dataset is generated using a **quadratic function with Gaussian noise** to simulate real-world randomness.

Polynomial degrees tested:

- **Degree 1** — Underfitting (High Bias)  
- **Degree 3** — Balanced  
- **Degrees 5 & 9** — Overfitting (High Variance)

### Key Concepts Covered

- Underfitting & Overfitting behavior  
- Generalization on unseen data  
- Training vs Testing **Mean Squared Error (MSE)**  
- Visualization of polynomial curve fits  

This project is implemented and executed in **Google Colab**.

---

## Tools & Technologies Used

### Programming Language
- Python

### Platform
- Google Colab

### Notebook Format
- `.ipynb`

---

## Libraries & Dependencies

### a) Built-in (Google Colab)

- `numpy` — numerical operations  
- `matplotlib` — data visualization  

### b) External Libraries (Install via pip)

- `scikit-learn` (sklearn)  
  - Polynomial Regression  
  - Train–Test Split  
  - MSE Evaluation  

---

## Steps to Use Google Colab

### **Step 1: Create a Google Colab Account**
1. Visit: https://colab.research.google.com  
2. Sign in with your Google account  
3. Click **"New Notebook"**

---

### **Step 2: Upload Notebook**
1. Upload the given .ipynb file
2. Make changes to the code 

---

### **Step 3: Import Libraries and Load Data**
1. Install external libraries:

   ```bash
   !pip install scikit-learn
   ```

2. Import libraries in Python:

   ```python
   import numpy as np
   import matplotlib.pyplot as plt
   from sklearn.preprocessing import PolynomialFeatures
   ```

3. Load data using:

   ```python
   import pandas as pd
   df = pd.read_csv("filename.csv")
   ```

---

### **Step 4: Run Notebook**
1. Click the **Run All** to execute  
2. View the output below the cells  

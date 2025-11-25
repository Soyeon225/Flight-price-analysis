# Flight Price Analysis ✈️  
Machine Learning Project analyzing factors that affect flight ticket prices

## Overview
This project explores which variables most strongly influence airline ticket prices.  
Using machine learning (Linear Regression and Random Forest), the model evaluates predictive performance and identifies important factors that contribute to price fluctuations.

This project was prepared as part of my transfer application portfolio to demonstrate analytical and programming skills using real-world datasets.

---

## 🔍 Objectives
- Analyze the relationship between flight attributes and prices  
- Compare Linear Regression and Random Forest performance  
- Evaluate model accuracy using RMSE  
- Visualize results & interpret feature impact  

---

## 🧰 Tools & Libraries
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## 📊 Models Used
### **1. Linear Regression**
A baseline model that assumes a linear relationship between features and price.

### **2. Random Forest Regressor**
A tree-based ensemble model that captures nonlinear relationships and typically performs better with complex data.

---

## 📈 Results Summary
| Model | RMSE |
|-------|------------|
| Linear Regression | 6761.71 |
| Random Forest | 2795.07 |

**Random Forest significantly outperformed Linear Regression**  
→ Indicates the relationships between flight features and price are nonlinear.

---

## 🔎 Key Insights
- Route, distance, demand seasonality, and time-to-departure are strong predictors of price.  
- Random Forest captured complex interactions better than Linear Regression.  
- Demonstrates how ensemble models reduce error in real-world datasets.

---

## 📁 Repository Structure


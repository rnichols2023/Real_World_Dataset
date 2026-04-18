# Real_World_Dataset

# 🌸 Iris Dataset — Linear SVM Classification  
A simple, interpretable machine learning model demonstrating linear classification, decision boundaries, and support vectors using the classic Iris dataset.

## 📘 Project Overview
This project uses a **Linear Support Vector Machine (SVM)** to classify two Iris flower species — *Setosa* and *Versicolor* — based on **petal length** and **petal width**.  
The goal is to visualize how a linear classifier separates the two classes and to illustrate the concept of **maximum margin classification**.

This project was completed as part of my graduate coursework in Data Science and is included in my GitHub portfolio as an example of real‑world dataset analysis and machine learning fundamentals.

---

## 🌱 Dataset
The Iris dataset is a well‑known, publicly available dataset included in the `sklearn.datasets` module.  
It contains 150 samples of iris flowers with four features:

- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

For this project, I used only:

- **Petal length (cm)**  
- **Petal width (cm)**  

And only two species:

- Iris Setosa  
- Iris Versicolor  

---

## ⚙️ Methods Used
### **1. Linear SVM Classifier**
- Kernel: `linear`  
- Regularization parameter: `C = 1e10` (large C to enforce a hard margin)  
- Trained on two features: petal length and petal width  
- Only two classes used for clean visualization  

### **2. Decision Boundary Visualization**
A custom function plots:

- The decision boundary  
- The margin lines (gutters)  
- The support vectors  
- The data points colored by class  

This helps illustrate how SVM finds the optimal separating hyperplane.

---

## 📊 Final Visualization

The final plot shows:

- A clear linear separation between Setosa and Versicolor  
- Support vectors highlighted  
- Margin lines drawn parallel to the decision boundary  
- Petal length vs. petal width scatter plot  

*(Insert your saved PNG here once you upload it)*

---

## 🧠 What I Learned
- How SVMs maximize the margin between classes  
- How to compute and visualize decision boundaries  
- How support vectors influence the classifier  
- How to prepare and filter real‑world datasets  
- How to create clean, interpretable ML visualizations  

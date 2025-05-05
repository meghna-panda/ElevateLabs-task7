# ElevateLabs-task7
# Task 7: Support Vector Machines (SVM) – Breast Cancer Classification
This repository contains the solution to **Task 7** of the AI & ML Internship. The task focuses on implementing **Support Vector Machines (SVM)** to classify breast cancer tumors as **malignant** or **benign** using a real-world dataset.

## What is SVM?
**Support Vector Machine (SVM)** is a powerful supervised machine learning algorithm used for **classification** and **regression** problems. 
It works by finding the **optimal hyperplane** that best separates the data points of different classes. For non-linearly separable data, it uses a **kernel trick** (like RBF) to transform data into a higher dimension where it becomes separable.

### Key Concepts:
- **Linear SVM**: Used when data is linearly separable.
- **RBF (Radial Basis Function)**: Kernel for non-linear separation.
- **Margin**: Distance between the separating hyperplane and the closest data points (support vectors).

## What We Did in This Project

### Objective:
Classify tumors as **malignant (cancerous)** or **benign (non-cancerous)** using SVM.

### Steps Performed:
1. **Loaded the Breast Cancer dataset**
2. **Cleaned and preprocessed** the data
3. **Converted labels** to numerical format
4. **Standardized** the features using `StandardScaler`
5. **Split** the dataset into training and test sets
6. Trained:
   - **Linear SVM**
   - **RBF SVM**
7. **Evaluated** performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
8. **Tuned hyperparameters** using `GridSearchCV`
9. **Performed 10-fold cross-validation**
10. **Visualized the dataset** using PCA in 2D

## Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib & Seaborn
- scikit-learn (SVC, GridSearchCV, PCA, etc.)

## Result Summary (Points)
1. Linear SVM achieved ~96% accuracy on the test data.
2. RBF SVM achieved ~98% accuracy, showing better performance for non-linear relationships.
3. Hyperparameter tuning using GridSearchCV identified the optimal values of C and gamma.
4. 10-fold cross-validation showed an average accuracy of around 97%, ensuring the model's reliability.
5. Precision, Recall, and F1-score were high for both classes, indicating good classification performance.
6. PCA Visualization helped in visualizing the dataset in 2D for better understanding of class separation.

# Random_Forest
## 📌 Overview
This repository contains two small projects demonstrating the use of *Random Forest* for classification tasks:
1. *Predicting Network Ad Purchase* – Classifying whether a user will purchase a product from an online ad, using a *confusion matrix* for evaluation.
2. *Predicting Flower Species (Iris Dataset)* – Classifying flower species based on petal and sepal measurements from the famous Iris dataset.

## 📖 About Random Forest
Random Forest is an *ensemble learning algorithm* that combines multiple decision trees to improve accuracy and reduce overfitting.  
Key concepts include:
- *Bootstrap Sampling*: Training each tree on a random subset of the data  
- *Feature Randomness*: Selecting a random subset of features for splitting at each node  
- *Voting Mechanism*: Predictions are based on majority voting from all trees  

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Predicting Network Ad Purchase
- *Goal*: Predict if a user will purchase a product after viewing an online ad.
- *Process*:
  - Load dataset
  - Train *Random Forest Classifier*
  - Evaluate performance using a *confusion matrix*

### 2️⃣ Predicting Flower Species (Iris Dataset)
- *Goal: Classify iris flowers into species (*Setosa, Versicolor, Virginica).
- *Process*:
  - Load the Iris dataset
  - Train *Random Forest Classifier*
  - Predict species based on sepal/petal measurements
  - Evaluate accuracy

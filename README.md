# Task-5-Decision-Trees-and-Random-Forests
# 🌳 Task 5: Decision Trees and Random Forests

This project demonstrates how to apply **Decision Tree** and **Random Forest** classifiers to a binary classification dataset. The dataset used is related to **heart disease prediction**.

---

## Dataset

- **File Name**: `heart.csv`
- **Target Variable**: `target` (0 = No Disease, 1 = Disease)
- **Features**: Clinical attributes such as age, cholesterol, chest pain type, etc.

## Tasks Covered

## 1. Train a Decision Tree Classifier and Visualize the Tree
- Trained a decision tree using `sklearn.tree.DecisionTreeClassifier`
- Used `plot_tree()` to visualize the tree with `matplotlib`
- Helps in understanding the decision-making process of the model

## 2. Analyze Overfitting and Control Tree Depth
- Compared training and test accuracy by varying `max_depth`
- Observed how deeper trees tend to **overfit**
- Demonstrated simple depth control with `max_depth=3`

## 3. Train a Random Forest and Compare Accuracy
- Trained a random forest using `RandomForestClassifier`
- Compared accuracy with the decision tree
- Random Forest showed better generalization and accuracy

## 4. Interpret Feature Importances
- Plotted feature importances to identify most influential factors
- Helped understand which clinical features contribute most to predictions

## 5. Evaluate Using Cross-Validation
- Performed 5-fold cross-validation
- Measured model stability and average performance
## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `sklearn

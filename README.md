# 🧠 Task 5: Decision Trees and Random Forests – Heart Disease Prediction

## 📌 Objective
Explore and implement **tree-based classification models** using a heart disease dataset to:

- Train and visualize a **Decision Tree**
- Analyze overfitting and control tree depth
- Train a **Random Forest** and compare it to the decision tree
- Interpret **feature importance**
- Evaluate models using **cross-validation**

## 🛠 Tools & Libraries
- Python
- Scikit-learn
- Matplotlib
- Graphviz

## 📁 Dataset
Used: `heart.csv` (Heart Disease UCI dataset)

- **Target column**: `target`
- **Features**: Age, sex, chest pain type, cholesterol, etc.

## 🧪 Tasks Performed

1. **Data Exploration**:
   - Loaded the dataset and reviewed basic statistics.

2. **Decision Tree Classifier**:
   - Trained a decision tree.
   - Visualized the tree using `plot_tree`.
   - Controlled overfitting with `max_depth`.
   - Evaluated using accuracy and classification report.

3. **Random Forest Classifier**:
   - Trained a random forest with 100 trees.
   - Compared performance to decision tree.
   - Visualized feature importances.

4. **Cross-Validation**:
   - Used 5-fold cross-validation to assess generalization performance.

## 📊 Results

| Model           | Accuracy (Test) | Cross-Validation Score |
|----------------|------------------|--------------------------|
| Decision Tree  | ~0.79            | ~0.79                    |
| Random Forest  | ~0.86            | ~0.83                    |

> *Note: Values may vary slightly due to randomness in training splits.*

## 📌 Conclusion
- Random Forest outperformed the standalone Decision Tree due to ensemble learning.
- Feature importance insights show which attributes most influence predictions.
- Cross-validation helps assess true performance and reduce overfitting risk.

## 🧩 Concepts Covered

- Decision Trees: splitting based on information gain.
- Random Forests: bagging and ensemble voting.
- Overfitting: controlled via `max_depth`.
- Model Evaluation: accuracy, classification report, cross-validation.
- Feature Importance: interpretation of key predictive features.

---

## ✅ Submission

- All code is in `task5_colab.ipynb`
- Dataset: `heart.csv`
- This README summarizes the project.


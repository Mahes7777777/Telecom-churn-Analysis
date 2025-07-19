# Telecom Customer Churn Prediction
## 📌 Objective

To analyze telecom churn data and build a predictive model that can identify customers likely to leave the service. The models were optimized using hyperparameter tuning techniques and compared using performance metrics.

---

## 📁 Project Structure

telecom-churn-prediction/
│
├── Telecome_churn_data.ipynb
├── decision_tree_model _development_hyperparameter_tuning.ipynb
├── random_forest_hypertuning_parameter_cv.ipynb
├── compare_two_dtree_rforest.ipynb
└── README.md

### 📂 Dataset Used

The dataset used in this project is:
- `data/telecom_churn_data.csv`

Make sure this file is present in the `data/` folder for the notebooks to run correctly.


---


## ✅ Steps Performed

### 1. 📊 Data Understanding and Preprocessing
- Loaded the telecom churn dataset.
- Checked for missing values.
- Verified data types and encoding (all were numerical).
- Performed correlation analysis.
- Visualized correlation heatmap.
- Checked multicollinearity using VIF.

Notebook: `Telecome_churn_data.ipynb`

---

### 2. 🌲 Decision Tree Classifier
- Trained Decision Tree classifier.
- Used `GridSearchCV` for hyperparameter tuning.
- Evaluated using metrics:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

Notebook: `decision_tree_model _development_hyperparameter_tuning.ipynb`

---

### 3. 🌳 Random Forest Classifier
- Trained Random Forest model.
- Applied `RandomizedSearchCV` for hyperparameter tuning.
- Evaluated using same performance metrics.

Notebook: `random_forest_hypertuning_parameter_cv.ipynb`

---

### 4. 📈 Model Comparison
- Compared the performance of both models (DT vs RF).
- Created a final DataFrame showing evaluation results side-by-side.
- Helped identify the better model for churn prediction.

Notebook: `compare_two_dtree_rforest.ipynb`

---

## 📌 Final Output

A comparison DataFrame was created that showed the accuracy, precision, recall, and F1-score for both models. Based on results, the better performing model can be deployed or further optimized.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📁 How to Run
'https://github.com/Mahes7777777/Telecom-churn-Analysis.git'

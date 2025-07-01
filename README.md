#  Drug Prediction using Decision Tree & Random Forest

This project focuses on predicting the correct **drug** to prescribe to patients based on medical features using two machine learning models:
- **Decision Tree Classifier**
- **Random Forest Classifier**

We perform data cleaning, normalization, training, evaluation, and visualization to compare both models.

##  Tasks Completed

### 1. **Data Cleaning & Preparation**
- Loaded the dataset.
- Checked and handled **missing values**.
- **Removed outliers** using boxplot analysis.
- **Encoded categorical variables** using `LabelEncoder`.

### 2. **Feature Scaling**
- Applied **z-score normalization** using `StandardScaler` to bring all features to the same scale.

### 3. **Model Training**
- Split data using `train_test_split` (80% training, 20% testing).
- Trained two classifiers:
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`

### 4. **Model Evaluation**
- Compared both models using:
  -  **Accuracy**
  -  **Confusion Matrix**
  -  **Classification Report** (Precision, Recall, F1-Score)

### 5. **Visualization**
- Plotted the **Decision Tree** using:
  - `plot_tree` (matplotlib)
- Random Forest does not produce a single tree, so visualization was done only for the Decision Tree model.

---

##  Model Comparison
we get same result from both the models





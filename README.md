# Heart Disease Classification 🫀

This project focuses on building a machine learning model to predict the presence of heart disease in patients using clinical data. 
## 📊 Project Summary

Using a real-world dataset, we explored the data, visualized patterns, preprocessed features, and trained multiple machine learning models. After evaluating all models, **Logistic Regression** achieved the best accuracy.

## 🚀 Workflow

1. **Data Loading**  
   - Load heart disease dataset using Pandas.
2. **Exploratory Data Analysis (EDA)**  
   - Visualize feature distributions and relationships using Seaborn.
   - Correlation heatmaps and pairplots.
   - Check for missing values and data imbalances.
3. **Data Preprocessing**  
   - Feature scaling using `StandardScaler`.
   - Train-test split for model validation.
4. **Model Training**  
   - Logistic Regression ✅ *(Best performing)*
   - Decision Tree Classifier
   - Random Forest Classifier
5. **HyperParameter Tuning**
   - RanomizedSearchCV()
   - GridSearchCV()
6. **Model Evaluation**  
   - ROC curve and AUC score
   - Confusion matrix
   - Classification report
   - Precision
   - Recall
   - Fl-score


## 📈 Results

- The **Logistic Regression model** outperformed Decision Tree and Random Forest classifiers 

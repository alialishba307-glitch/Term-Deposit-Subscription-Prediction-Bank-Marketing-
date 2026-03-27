# Term-Deposit-Subscription-Prediction-Bank-Marketing-

## Task Objective

The objective of this project is to predict whether a bank customer will subscribe to a term deposit based on data collected from a direct marketing campaign. The goal is to analyze customer demographics, financial attributes, and campaign-related features to build a classification model that supports targeted marketing strategies and improves campaign efficiency.

## Approach

The project follows a structured end-to-end machine learning workflow:

## Data Understanding & Exploration
Loaded and examined the Bank Marketing dataset.
Analyzed dataset structure, feature types, and summary statistics.
Performed exploratory data analysis (EDA) to understand customer behavior and campaign patterns.

## Data Preprocessing
Checked for missing values and inconsistencies.
Encoded categorical variables using One-Hot Encoding.
Prepared feature matrix and target variable.
Split the dataset into training and testing sets.

## Model Development
Trained classification models including Logistic Regression and Random Forest.
Generated predictions on the test dataset.

## Model Evaluation
Evaluated performance using Confusion Matrix.
Calculated F1-Score to balance precision and recall.
Plotted ROC Curve to assess model discrimination ability.

## Model Interpretability (XAI)
Applied SHAP or LIME to explain individual predictions.
Analyzed at least five predictions to understand feature contributions.
Identified key drivers influencing customer subscription decisions.

## Results & Insights
Customer interaction features such as contact duration and previous campaign outcomes significantly influenced subscription likelihood.
Demographic and financial attributes contributed to model predictions but with varying importance.
Random Forest provided better performance by capturing complex relationships, while Logistic Regression offered interpretability.
Explainability techniques (SHAP/LIME) highlighted the impact of specific features on individual predictions, improving transparency.

## Conclusion

This project demonstrates a complete classification workflow for predicting term deposit subscription. By combining data preprocessing, model training, evaluation, and interpretability techniques, the system provides both accurate predictions and meaningful insights. The inclusion of explainable AI enhances trust and usability in real-world decision-making scenarios.

## Future Improvements
Perform hyperparameter tuning and cross-validation to improve model performance.
Address class imbalance using resampling techniques.
Explore advanced models such as Gradient Boosting or XGBoost.
Enhance interpretability using global SHAP summary plots.
Deploy the model as an interactive dashboard for marketing teams.

## Tools & Technologies
Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

SHAP / LIME

Jupyter Notebook

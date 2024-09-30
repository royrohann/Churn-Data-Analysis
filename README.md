# Churn Data Analysis
This project focuses on building a machine learning model to predict customer churn based on historical customer data. The goal is to identify customers who are likely to leave the service and provide insights for retention strategies.

## Project Overview

Customer churn, which refers to the rate at which customers stop using a service, is a critical business problem, particularly in industries like telecom, banking, and subscription-based services. Predicting churn accurately helps businesses proactively address customer dissatisfaction and improve retention.

### Key Steps:
1. **Data Preprocessing and EDA**:
   - Handled missing values and explored the distribution of Binary and Continuous variables, along with Correlations.
   - Applied encoding techniques to convert categorical variables into numerical values.

2. **Feature Selection**:
   - Utilized **Recursive Feature Elimination (RFE)** to select the top 20 most important features for predicting churn.
   - This process helped reduce the dimensionality of the dataset and improve model performance.

3. **Modeling**:
   - The model used for this project was **Logistic Regression**, chosen for its simplicity and effectiveness in binary classification problems like churn prediction.
   - Applied **k-Fold Cross-Validation** to evaluate the model's performance across 10 different folds, ensuring robust validation of the model.

4. **Evaluation**:
   - The model was evaluated using metrics such as **Accuracy**, **Precision**, **Recall**, and **F1-Score** to assess its performance.
   - The confusion matrix was generated to observe the model's true positives, false positives, true negatives, and false negatives.

5. **Insights**:
   - The final model provides actionable insights to target customers at high risk of churning, allowing businesses to deploy targeted marketing and retention strategies.

## Project Structure

- `churn_prediction.ipynb`: The Jupyter notebook containing the complete analysis, from data preprocessing to model evaluation.
- `README.md`: Overview of the project (this file).

## Installation and Usage

### Prerequisites:
To run this project, you'll need the following libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `jupyter`
 

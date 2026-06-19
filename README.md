# Customer-Spending-Prediction-Using-Multiple-Linear-Regression

A Machine Learning project that predicts annual customer spending for an e-commerce business using Multiple Linear Regression. The project analyzes customer engagement metrics, performs feature selection, trains a predictive model, and evaluates performance using R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

---

## Project Overview

This project aims to predict a customer's yearly spending based on behavioral and engagement metrics. Multiple Linear Regression is used to model the relationship between several independent variables and the target variable, helping businesses understand factors that influence customer spending.

The project covers:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis
- Correlation Analysis
- Feature Selection
- Train-Test Split
- Multiple Linear Regression
- Model Evaluation
- Spending Prediction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Features Used

### Independent Variables

- Average Session Length
- Time on App
- Length of Membership

### Target Variable

- Yearly Amount Spent

---

## Workflow

### 1. Data Loading
- Imported the customer spending dataset using Pandas.
- Examined dataset dimensions and structure.

### 2. Data Cleaning
- Checked for missing values.
- Removed unnecessary columns if present.
- Verified data consistency and quality.

### 3. Exploratory Data Analysis
- Analyzed customer behavior patterns.
- Studied distributions and relationships among features.

### 4. Correlation Analysis
- Generated a correlation matrix.
- Identified features strongly related to yearly spending.

### 5. Feature Selection
- Selected the most relevant customer engagement metrics.
- Removed irrelevant features to improve model performance.

### 6. Train-Test Split
- Split the dataset into training and testing sets.
- Used the training set for model learning and the testing set for evaluation.

### 7. Multiple Linear Regression
- Applied Multiple Linear Regression using Scikit-Learn.
- Trained the model using selected features.

### 8. Model Evaluation

The model was evaluated using multiple performance metrics.

| Metric | Value |
|----------|----------|
| Training R² Score | `<TRAIN_R2_SCORE>` |
| Testing R² Score | `<TEST_R2_SCORE>` |
| Mean Absolute Error (MAE) | `<MAE_VALUE>` |
| Root Mean Squared Error (RMSE) | `<RMSE_VALUE>` |

### Evaluation Interpretation

#### R² Score
- Measures how well the model explains variations in customer spending.
- Values closer to 1 indicate better predictive performance.

#### Mean Absolute Error (MAE)
- Represents the average prediction error.
- Lower values indicate more accurate predictions.

#### Root Mean Squared Error (RMSE)
- Measures the average magnitude of prediction errors.
- Penalizes larger errors more heavily than MAE.
- Lower values indicate better model performance.

### Model Fit Analysis

- A small difference between training and testing R² scores suggests good generalization.
- The model effectively captures spending patterns without significant overfitting.
- Low MAE and RMSE values indicate accurate customer spending predictions.

### 9. Spending Prediction
- Predicted yearly spending for customers based on engagement metrics.
- Compared actual spending values with predicted values.

---

## Results

The Multiple Linear Regression model successfully identified important factors influencing customer spending and achieved strong predictive performance.

### Key Findings

- Customer engagement metrics significantly impact yearly spending.
- Length of Membership showed a strong influence on spending behavior.
- The model achieved high R² scores, indicating strong explanatory power.
- Low MAE and RMSE values demonstrate reliable prediction accuracy.
- Training and testing scores were closely aligned, indicating good model generalization.

---

## Conclusion

This project demonstrates the effectiveness of **Multiple Linear Regression** for predicting annual customer spending using customer engagement metrics.

The model achieved strong performance by accurately capturing relationships between customer behavior and spending patterns. The evaluation metrics indicate that the model generalizes well to unseen data and can be used as a reliable tool for customer spending prediction and business decision-making.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Correlation Analysis
- Feature Selection
- Multiple Linear Regression
- Model Evaluation
- Predictive Analytics
- Scikit-Learn
- Business Data Analysis

---

## Future Improvements

- Include additional customer behavior features.
- Compare performance with advanced regression algorithms.
- Perform hyperparameter tuning.
- Deploy the model using Flask or Streamlit.
- Build a customer spending prediction dashboard.
---

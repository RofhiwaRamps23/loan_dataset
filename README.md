
# Loan Default Prediction and Risk Assessment

## Project Overview
This project aims to predict loan defaults using machine learning models, enabling financial institutions to assess risk and make informed lending decisions. The analysis focuses on identifying key factors influencing loan repayment behavior and evaluating the performance of predictive models.

## Data Description
- **Source:** Kaggle Lending Club Dataset ([Link](https://www.kaggle.com/datasets/itssuru/loan-data))
- **Size:** 9,578 loan records
- **Features:**
  - Numerical: FICO score, interest rate, debt-to-income ratio (DTI), annual income, etc.
  - Categorical: Loan purpose
- **Default Rate:** 16% of loans were not fully paid

## Methodology
1. **Data Preprocessing:**
   - Handled missing values and class imbalance.
   - Encoded categorical variables.
2. **Modeling:**
   - Logistic Regression and Random Forest models were implemented.
   - Evaluated using metrics like accuracy, precision, recall, and ROC AUC.
3. **Feature Importance:**
   - Identified key predictors such as DTI and interest rate.

## Results
- Logistic Regression outperformed Random Forest with an ROC AUC score of 0.645.
- Debt-to-income ratio (DTI) and interest rate were the most influential predictors.

## Limitations
- Class imbalance impacted model performance.
- Limited features may not fully capture loan repayment behavior.

## Future Work
- Address class imbalance using techniques like SMOTE.
- Explore advanced models like XGBoost or LightGBM.
- Collect additional features to enhance predictive power.

## References
1. **Data Source:** Kaggle Lending Club Dataset ([Link](https://www.kaggle.com/datasets/wordsforthewise/lending-club))
2. **Tools and Libraries:**
   - Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
3. **Documentation:**
   - Scikit-learn Documentation ([Link](https://scikit-learn.org/stable/documentation.html))
   - Python Documentation ([Link](https://docs.python.org/3/))
4. **Research Papers:**
   - "Random Forest Classification" by Breiman, L. (2001)
   - "Logistic Regression: From Introductory to Advanced Concepts and Applications" by Scott Menard

## How to Use
1. Clone the repository.
2. Install required libraries.
3. Run the Jupyter Notebook to reproduce the analysis.


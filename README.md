# Magazine-Subscription-Analysis

## Project Overview
This project analyzes customer subscription behavior for a magazine company to understand factors influencing subscription renewals. Predictive models were built to classify customers as subscribers or non-subscribers, and their performance was evaluated on various metrics.

Key Deliverables:
- Exploratory Data Analysis (EDA) with visualizations
- Predictive models: Logistic Regression and Quadratic Discriminant Analysis (QDA)
- Model comparison and recommendations based on performance metrics

---

## Dataset
- **Description**: A dataset containing customer demographic and behavioral features influencing subscription decisions.
- **Preprocessing**:
  - Missing values handled through imputation
  - One-hot encoding for categorical variables
  - Non-predictive columns like `ID` and `Dt_Customer` were excluded

---

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Distribution analysis (e.g., income, amount spent)
   - Relationship visualizations (e.g., scatter plots, box plots)
   - Correlation analysis to detect multicollinearity

2. **Model Development**:
   - Logistic Regression (Baseline model)
   - Quadratic Discriminant Analysis (QDA)

3. **Evaluation Metrics**:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC curve

4. **Model Comparison**:
   - Logistic Regression demonstrated better recall and precision than QDA.

---

## Technologies Used
- **Python**: Data preprocessing, modeling, and visualization
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualizations
  - `scikit-learn` for machine learning

---

## Results
### Logistic Regression:
- **Accuracy**: 82%
- **Precision**: 45%
- **Recall**: 79%
- **ROC Curve**: Demonstrates strong performance in identifying subscribers

### Quadratic Discriminant Analysis (QDA):
- **Accuracy**: 82%
- **Precision**: 43%
- **Recall**: 55%
- **ROC Curve**: Slightly lower performance compared to Logistic Regression

### Conclusion:
- Logistic Regression is the preferred model for this analysis due to its better recall and precision for identifying subscribers.

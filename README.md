
# Marketing Mix Modeling (MMM) Project

## 1. Project Overview
This project analyzes the relationship between marketing activities
and sales using Marketing Mix Modeling (MMM).

The project compares two datasets:
- Monday dataset
- Saturday dataset

## 2. Objective
- Understand marketing channel relationships with sales.
- Analyze carryover effects using Adstock.
- Study saturation effects.
- Build sales prediction models.
- Compare model performance.

## 3. Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## 4. Project Workflow
1. Data collection and loading
2. Data inspection and cleaning
3. Exploratory Data Analysis (EDA)
4. Correlation analysis
5. Multicollinearity and VIF analysis
6. Adstock transformation
7. Saturation analysis
8. Regression modeling
9. Residual analysis
10. Model evaluation
11. Final test validation

## 5. Final Test Results

| Metric | Monday | Saturday |
|---|---:|---:|
| MAE | 18157.39 | 18867.98 |
| RMSE | 25758.12 | 26370.52 |
| R2 | 0.3851 | 0.3746 |

## 6. Conclusion
The Monday model performed slightly better than the
Saturday model based on MAE, RMSE and R2.

The results provide an initial understanding of
marketing variables, carryover effects and sales prediction.

## 7. Limitations
- The model's predictive performance is limited.
- Correlation does not prove causation.
- Reliable channel ROI requires suitable spend and
  contribution data.
- Further validation and model improvement are needed.

## 8. Important Output Files
- Final_Test_Model_Performance.csv
- Final_Test_Predictions.csv
- Final_MMM_Performance_Graph.png

## 9. Project Status
Initial MMM analysis and model validation completed.

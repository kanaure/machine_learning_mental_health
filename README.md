# machine_learning_mental_health
Personal Project for class "Machine Learning and Data Mining".

This project explores the relationship between digital device usage, everyday lifestyle factors, and mental health outcomes. The goal is to understand whether lifestyle factors and device usage can explain differences in mental health scores.

Key Findings:
- Several regression models (Linear Regression, Ridge, Lasso, and XGBoost) were used to predict a continuous mental health score. However, all models performed poorly, with negative R² values, meaning they predicted mental health outcomes worse than using the average score.
- Correlation analysis revealed weak relationships between attributes and mental health scores, suggesting that the features available in the dataset do not strongly explain the target variable.
- The problem was reformulated as a classification task by grouping mental health scores into Low, Medium, and High categories.
- A Random Forest classifier was trained, but it mainly predicted the most frequent class, indicating class imbalance and limited separability in the data.

The poor performance is likely due to the dataset itself, which seems to lack strong and consistent patterns linking digital behavior and habits to mental health. The results suggest that better data or additional features might be necessary to improve predictive accuracy

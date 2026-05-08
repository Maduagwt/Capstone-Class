## Predicting Pro Bowl NFL Quarterbacks Using Performance Metrics
# Introduction
# Background

# Quarterback performance is one of the most important and debated topics in the NFL. Every season, the league selects quarterbacks to the Pro Bowl based on overall performance, fan voting, media attention, and team success. However, these selections are not always based strictly on statistics, which creates debate over whether the best-performing quarterbacks are truly being recognized.

# This project uses data analytics and machine learning techniques to analyze NFL quarterback statistics from 2001 to 2023 and predict whether a quarterback will be selected to the Pro Bowl. By using performance metrics such as passing yards, touchdowns, interceptions, completion percentage, passer rating, and advanced efficiency statistics like ANY/A, the project aims to determine how strongly quarterback performance influences Pro Bowl selections.

# Explore
# How quarterback statistics influence Pro Bowl selection
# Which performance metrics are the strongest predictors of Pro Bowl selection
# The relationship between advanced efficiency metrics and recognition
# Trends in quarterback performance over time
# The effectiveness of machine learning models in predicting Pro Bowl outcomes
# Executive Summary

# This project focuses on predicting Pro Bowl quarterback selections using statistical performance metrics from NFL quarterbacks between 2001 and 2023. The analysis combines data preprocessing, exploratory data analysis (EDA), and predictive analytics to identify patterns associated with successful Pro Bowl selections.

# The following methodologies were used throughout the project:

# Data cleaning and preprocessing using Python and pandas
# Exploratory Data Analysis (EDA) using visualizations and statistical summaries
# Feature selection using quarterback performance statistics
# Logistic Regression modeling for binary classification
# Model evaluation using accuracy score, confusion matrix, classification report, and coefficient analysis

# The model achieved an accuracy score of approximately 84%, showing that quarterback performance statistics have strong predictive power when determining Pro Bowl selections. The results also showed that touchdowns, quarterback rating, and ANY/A were among the strongest positive predictors, while interceptions negatively affected the probability of selection.

# Results
# Exploratory Data Analysis
# Quarterbacks with higher touchdown totals and passer ratings were more likely to make the Pro Bowl
# Advanced efficiency metrics such as ANY/A showed strong relationships with Pro Bowl selections
# Interceptions negatively impacted Pro Bowl selection probability
# Quarterbacks with stronger overall efficiency metrics consistently performed better in the dataset
## Predictive Analytics

# The logistic regression model performed well overall and achieved an accuracy score of approximately 84% on the testing dataset.

# Additional evaluation metrics included:

# Precision scores ranging from 0.80 to 0.86
# Recall scores ranging from 0.80 to 0.85
# F1-score near 0.83 overall

# The confusion matrix showed that the model correctly classified a large number of quarterbacks who were selected and not selected for the Pro Bowl.

# The coefficient analysis revealed that:

# Touchdowns had a strong positive influence on Pro Bowl selection
# Quarterback rating positively affected selection probability
# ANY/A was one of the strongest advanced metrics in predicting success
# Interceptions negatively impacted Pro Bowl selection chances
# Methodology
# Data Collection
# NFL quarterback performance dataset sourced from Kaggle
# Dataset includes quarterback statistics from 2001–2023
# Dataset contains over 2,300 quarterback records
# Data Preprocessing
# Removed missing values
# Filtered quarterbacks with fewer than 50 passing attempts
# Selected relevant variables for predictive modeling
# Defined target variable as Pro Bowl selected vs. not selected
# Split dataset into training and testing sets using train_test_split
# Exploratory Data Analysis (EDA)
# Created visualizations to analyze quarterback performance trends
# Examined relationships between touchdowns, interceptions, passer rating, and Pro Bowl selection
# Analyzed statistical distributions and correlations between variables
# Predictive Analytics
# Used Logistic Regression for binary classification
# Trained the model using quarterback performance metrics
# Evaluated model performance using:
# Accuracy Score
# Confusion Matrix
# Classification Report
# Coefficient Analysis
# Technologies Used
# Python
# Jupyter Notebook
# pandas
# NumPy
# matplotlib
# seaborn
# scikit-learn
# Conclusion

# The project demonstrated that quarterback performance statistics can effectively predict Pro Bowl selections. The logistic regression model achieved strong results, showing that metrics such as touchdowns, quarterback rating, and ANY/A are major contributors to Pro Bowl recognition. However, the analysis also highlighted limitations because Pro Bowl selections are influenced by factors beyond performance, including fan voting, popularity, and team success.

# Overall, this project shows how machine learning and sports analytics can be used to evaluate player performance and support more data-driven decision-making in professional sports. Future improvements could include adding team-level variables or testing more advanced machine learning models such as Random Forest or Gradient Boosting to further improve prediction accuracy.# Capstone-Class

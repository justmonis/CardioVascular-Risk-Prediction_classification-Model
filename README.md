# CardioVascular-Risk-Prediction_classification-Model


![Local GIF](ali-hajiluyi-MhFJNz_D8t4-unsplash.jpg)

<h3 align="Left">
<br>
Problem Statement:
<br>
Rossmann operates more than 3,000 drug stores across 7 European countries. Currently, Rossmann's store managers face the challenge of accurately predicting daily sales up to six weeks in advance. Sales at each store are influenced by various factors such as promotions, competition, holidays, seasonal trends, and location specifics. Due to the diverse circumstances of individual managers, the accuracy of these sales predictions varies significantly. You're given historical sales data for 1,115 Rossmann stores, with some stores undergoing temporary closure for refurbishment. Your task is to forecast the 'Sales' column for the test set.<br>
<br>
<h3 Project Summary: </h3>
The Rossman Sales Prediction project involved comprehensive data analysis, feature engineering, and model selection to achieve precise sales forecasts. Here's an overview of the project's key steps and findings:<br>
<br>
1. Data Collection and Cleaning:<br>
* Gathered historical sales data for Rossmann stores, including competitor, holiday, customer, and daily sales details.
- Ensured data integrity by cleaning and preparing the dataset, handling missing values, and addressing outliers.<br>
<br>
2. Exploratory Data Analysis (EDA):<br>
- Conducted thorough EDA to extract insights through univariate, bivariate, and multivariate analysis.
- Utilized visualizations to identify patterns and trends, providing valuable insights for decision-making.<br>
<br>
3. Feature Engineering and Preprocessing: <br>
- Engineered new features like PromoDuration and Competition Distance to capture crucial information.
- Managed multicollinearity using VIF analysis and addressed outliers through the IQR technique.
- Applied One-Hot Encoding to categorical variables and employed transformation techniques for data normalization.
<br>
  <br>
4. Model Selection and Training: <br>
- Split the preprocessed data into training and testing sets to assess model performance.
- Employed various machine learning algorithms, including linear regression, decision trees, and random forest, for sales prediction. <br>
  <br>
- Evaluated model performance using metrics such as R-squared score, mean square error, and root mean square error.
- Utilized regularization techniques like Lasso, Ridge, and Elastic Net to enhance model performance.
<br>
  <br>
5. Conclusion:<br>
- After experimentation, the XGBoost model emerged as the top performer, achieving an R2 score of approximately 98% on the training data and maintaining 97% on the test dataset.
- The model exhibited lower MSE and RMSE values compared to other models, indicating superior predictive accuracy.
- Consistent performance across multiple evaluation metrics demonstrates robust generalization.
- Residuals analysis confirmed the model's effectiveness in capturing underlying data patterns.
  <br>
  <br>
This project demonstrates the effective application of data analysis, feature engineering, and machine learning techniques to address real-world forecasting challenges in the retail industry, providing actionable insights for decision-making.  

</h3>

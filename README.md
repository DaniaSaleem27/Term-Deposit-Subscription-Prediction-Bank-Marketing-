# Term-Deposit-Subscription-Prediction-Bank-Marketing-

Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign.

# Approach:
Loaded and explored the dataset using pandas and seaborn.

Cleaned the data and handled missing values.

Encoded categorical variables using OneHotEncoder and scaled numerical features using StandardScaler inside a ColumnTransformer pipeline.

Split the dataset into training and testing sets.

Trained two classification models:

Logistic Regression as a baseline model.

Random Forest Classifier as an advanced ensemble model.

Evaluated model performance with:

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

ROC Curve and AUC score

Interpreted the Random Forest model by extracting and visualizing the top 10 important features influencing customer decisions.

# Results and Findings:

Both models performed well, with Random Forest showing higher accuracy and AUC than Logistic Regression.

The most influential factors in predicting subscription were call duration, previous campaign outcome, contact type, balance, and age.

Customers who had longer call durations and previous successful contacts were much more likely to subscribe to a term deposit

The final model can help banks target high-potential clients more efficiently and reduce marketing costs.

# Conclusion:

The Random Forest model provides strong predictive performance and clear feature interpretability, making it a reliable tool for marketing decision support.

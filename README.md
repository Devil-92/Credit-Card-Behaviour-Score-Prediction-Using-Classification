# Project_1
I developed a binary classification model to predict whether a customer will default on their
credit card payment in the next month. The project focused on credit risk assessment, where
minimizing false negatives is critical.
I began with exploratory and behavioural analysis, examining trends such as payment delays,
repayment consistency, credit utilization, and delinquency streaks. These insights guided the
creation of financially meaningful features like utilization ratios and delinquency indicators.
To address class imbalance, I applied techniques such as SMOTE, class weighting, and down
sampling. I trained and compared multiple models, including Logistic Regression, Decision
Trees, XGBoost, and LightGBM, evaluating them using metrics aligned with credit risk
priorities — primarily the F2 score, along with AUC-ROC and F1-score.
I tuned the classification threshold to reflect the bank’s risk appetite and generated production-
style predictions on an unlabelled dataset. The final model achieved a validation F2 score of
0.8721, balancing business needs and predictive performance.

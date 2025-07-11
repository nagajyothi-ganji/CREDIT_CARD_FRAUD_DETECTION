# CREDIT_CARD_FRAUD_DETECTION

ABSTRACT

Credit card fraud detection has become a critical concern in the financial sector due to the rise 
in digital transactions. Traditional fraud detection methods are rule-based and struggle to adapt 
to evolving fraud techniques. This project proposes a machine learning-based approach using 
XGBoost, a high-performance gradient boosting algorithm, to detect fraudulent transactions 
efficiently. 
The dataset used in this study is the Kaggle Credit Card Fraud Detection Dataset, which con
tains 284,807 transactions, with only 0.172% fraudulent cases. Due to severe class imbalance, 
Synthetic Minority Over-sampling Technique (SMOTE) was applied to generate synthetic 
fraud cases. Additionally, StandardScaler was used for feature scaling. 
The model evaluation, based on accuracy, precision, recall, F1-score, and AUC-ROC, showed 
that XGBoost significantly outperformed traditional models, achieving 99.81% accuracy and 
a 96.79% AUC-ROC score. 
This system offers a robust fraud detection mechanism that can be integrated into real-time 
banking systems for improved security. 
Keywords: Credit Card Fraud Detection, XGBoost, SMOTE, Imbalanced Data, Financial Se
curity.

Aim Of The Project

The primary aim of this project is to develop an anomaly detection system for identifying 
fraudulent credit card transactions using XGBoost. The system applies data preprocessing tech
niques, feature selection, and model optimization to enhance fraud detection performance.

XGBOOST IN FRAUD DETECTION

Extreme Gradient Boosting (XGBoost) is an ensemble learning algorithm that improves fraud 
detection by: 
✔ Handling imbalanced datasets using scale_pos_weight. 
✔ Being computationally efficient compared to Random Forest and SVM. 
✔ Using boosting techniques to improve fraud classification.

DATASET INFORMATION 

Kaggle Credit Card Fraud Dataset - MLG-ULB Machine Learning Group (2013). 
https://www.kaggle.com/mlg-ulb/creditcardfraud



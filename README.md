**Bank Term Deposit Prediction (Marketing Campaign Analysis) 
**
This project predicts whether a customer will subscribe to a term deposit based on a Portuguese bank’s marketing campaign data. Built using machine learning and explainable AI (XAI), this end-to-end solution demonstrates data preprocessing, model training, evaluation, and interpretation. 
Objective 

Predict customer subscription (yes/no) using demographic, financial, and campaign-related features from the UCI Bank Marketing Dataset. 
Key Components 

    Data Preprocessing: One-hot encoding of categorical variables  
    Exploratory Data Analysis (EDA): Visualizations for age, education, job, and campaign outcomes  
    Model: Random Forest Classifier with train/test split  
    Evaluation Metrics: Confusion Matrix, F1-Score, ROC-AUC  
    Explainability: SHAP values to interpret predictions for individual customers
     

Insights 

    Customers with previous success in campaigns are far more likely to convert.  
    Job type (e.g., entrepreneur, retired) significantly impacts subscription likelihood.  
    Call duration is highly predictive — but should be excluded in production due to data leakage.  
    Model achieves 88% ROC-AUC, showing strong predictive power.
     

Technologies Used 

Python: pandas, numpy, matplotlib, seaborn, scikit-learn, shap 
Files 

    bank_deposit_prediction.ipynb: Jupyter Notebook with full analysis  
    bankb-full.csv: Dataset (renamed from bank-full.csv)
     

Use Case 

Helps banks optimize marketing campaigns by identifying high-propensity customers and improving targeting strategies.

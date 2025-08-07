# *Customer Churn Prediction*

### *Overview:*  
This project focuses on building a machine learning model to predict customer churn—i.e., whether a customer is likely to stop using a company’s service. Timely prediction enables businesses to implement tailored retention strategies, reduce revenue loss, and improve customer satisfaction.

### *Problem Statement:*  
Customer churn is a critical challenge in service-based industries such as telecom, SaaS, and banking. Identifying at-risk customers before they churn can provide a competitive edge. This project aims to develop a predictive model using historical customer data.

### *Data Source:*  
The dataset contains customer-level information such as:  
- Demographics (Age, Gender, Region)  
- Account info (Subscription type, Billing method, Tenure)  
- Usage statistics (Call minutes, Data usage, Support interactions)  
- Target variable: Churn (1 if churned, 0 otherwise)

### *Project Workflow:*  
##### 1.  *Data Cleaning & Exploration*  
   - Handled missing values and outliers  
   - Visualized churn distribution and patterns in customer behavior

##### 2. *Feature Engineering*  
   - Created derived features (e.g., average monthly spend)  
   - One-hot encoded categorical variables

##### 3. *Model Building*  
   - Trained models including Logistic Regression, Random Forest, XGBoost, and Neural Networks  
   - Used SMOTE to address class imbalance  
   - Performed hyperparameter tuning using GridSearchCV

##### 4. *Evaluation Metrics:*  
   - Accuracy, Precision, Recall, F1 Score, ROC-AUC  
   - Confusion Matrix for interpretability

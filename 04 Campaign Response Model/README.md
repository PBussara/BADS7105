# Campaign Response model
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15L0BpnpN6m_elG51d4WArzy0YDpMmrYz?usp=sharing)
## Objectives of this work 
 
 
      - find the best model.
      - Optimize the model


## Dataset
    Retail Data consist of 2 files:
      - Retail_Data_Response:  CUSTOMER_ID, TRANS_DATE, TRANS_AMOUNT
      - Retail_Data_Transactions: CUSTOMER_ID, Response
      
## Data prepareing
   
   Feature Engineering by RFM model and CLV
   
     - 6 features that include Response, Recency, Frequency,Monetary, AOU and Ticket size,were generated.
     - Created two dataste, First dataset has only RFM features.  Second dataset add AOU and Ticket size. 
     - Splited data to train and test data
     - By Response Feature we found that have imbalance. Thus we fix imbalanced only train data with SMOTE.
   
 
 ## Model Selection
    - We compared between logistic regression and XGBoost on dataset that was fix imbalance 
      by oversampling undersampling and SMOTE.
   
   ![alt tag](https://github.com/PBussara/BADS7105/blob/main/04%20Campaign%20Response%20Model/results_campaign_respone_model.jpg)
   
   Finally we selected XGboost model that trained on oversampling dataset for tuning parameter.
   We try to fine tuning parameter but AUC score isn't increase.
     


# Campaign Response model
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1T6ikOAZxS1cLaf-UWQS0WSD50k1Ltq2q?authuser=3#scrollTo=UoJ_MIBhbeFf)
## Objectives of this work 
 
 
      - find the best model.
      - Optimize the model by AUC 


## Dataset
    Retail Data consist of 2 files:
      - Retail_Data_Response:  CUSTOMER_ID, TRANS_DATE, TRANS_AMOUNT
      - Retail_Data_Transactions: CUSTOMER_ID, Response
      
## Data prepareing
   
   Feature Engineering by RFM model and CLV
   
     - 6 features that include Response, Recency, Frequency,Monetary, AOU and Ticket size,were generated.
     - Splited data to train and test data
     - By Response Feature we found that have imbalance. Thus we fix imbalanced only train data with SMOTE.
   
 
 ## Evaluate model

# Customer Segmentation

 ## Dataset 
 Supermarket data 
 
 ## Feature Engineering
    - we generated 3 features from RFM model to clustered customers. 
    - New features are Recency,Frequecy, Monetary (or totalSpend) .
    - we try to generate another features such as Ticket size, lifestyle of customer for the best model.
   
 
## Model Selection

### Cluster customers
    
  We use pycaret to compare clustering model by Silhouette, Calinski-Harabasz score.
![alt tag](https://github.com/PBussara/BADS7105/blob/main/01%20CLV%20Dashboard/Dashboard1.jpg)
  
  K-means is model that we used to cluster customes.
  
  we set up number of group or k by distortion score elbow. k is 4 
  
![alt tag](https://github.com/PBussara/BADS7105/blob/main/01%20CLV%20Dashboard/Dashboard1.jpg)
  Finally we clustered customers to 4 group and taken each group to analyze what are features that cluster them to each group by Decision Tree Classifier.  
![alt tag](https://github.com/PBussara/BADS7105/blob/main/01%20CLV%20Dashboard/Dashboard1.jpg)
  
### Decision tree
 We compared classication models by pycaret again. We choosed Decision Tree Classifier to found feature.
![alt tag](https://github.com/PBussara/BADS7105/blob/main/01%20CLV%20Dashboard/Dashboard1.jpg)
 
 
 ## Customers analysis for clustering
 
      Cluster0  (Know you): Low total spending, Lowest rencency and not often visited. 
      Recommend :
          - Run analytic model to compare  cost vs revenue for offering promotions.
          - Churn prediction (Lead scoring)
 
      Cluster1 (please coming): total spending ,rencency and total visit is middle.
      Recommend :
          - Daily promotion speacial
          - Discounted speacial products, BOGO
          
      Cluster2 (My royal): Highest total spending, Highest Rencency, Lowest avg between visit 
      recommend :
          - New products
          - promotions for new customers suggestion such as if your suggest your friends to be our members, you will receive discount.
      Cluster3  (Muggle):  High total spending, High Rencency, customers don't often visited.
      recommend :
          - upsell 
          - voucher for buying more than average spending per month.




 
 
    

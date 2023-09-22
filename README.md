# ClassificationProjects-SupervisedML
Classification analysis is being done using various supervised ML algorithms like : Logistic Regression, SVC, GaussianNB , Decision-Tree Classifier, 
Random-Forest Classifier with Hyperparameter Tuning

The analysis of Customer Churn Prediction is divided into three stages:

Stage I : In this analysis and Model training is done with : 
         
          (a) Pipeline : 
             - Missing value Imputation
             - Ohe.
             - Standard Scaling

          (b) Imbalance Data 
          (c) Feature Engineering

Stage II(A) : In this analysis and Model training is done with :

              (a) Pipeline : 
                 - Missing value Imputation
                 - Ohe.
                 - Standard Scaling

              (b) Imbalance Data - Up-Sampling
              (c) Feature Engineering

          
Stage II(B) : In this analysis and Model training is done with : 

              (a) Pipeline : 
                 - Missing value Imputation
                 - Ohe.
                 - Standard Scaling

              (b) Imbalance Data - Down-Sampling
              (c) Feature Engineering    

Stage II(C) : In this analysis and Model training is done with : 

              (a) Pipeline : 
                 - Missing value Imputation
                 - Ohe.
                 - Standard Scaling

              (b) Imbalance Data - Combine-Sampling
              (c) Feature Engineering 
              
Stage III FinalModel : In this analysis and Model training is done with : 

                      (a) Pipeline : 
                       - Missing value Imputation
                       - Ohe.
                       - Standard Scaling

                      (b) Imbalance Data - Combine-Sampling
                      (c) Feature Engineering   
                   
                      (d) HyperParameter Tuning using Grid Search CV of the best model (Logistic Regression) is done at the end.

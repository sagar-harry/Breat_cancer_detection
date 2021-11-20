# Breat_cancer_detection
General steps for predicting breast cancer using KNN, Naive Bayes, Logistic Regression and SVM

Steps involved in the current project:
1. Data Exploration
2. Feature Engineering
    - Univariate analysis
        - Dealing with missing values
        - Checking imbalance in datasets
        - Distribution of data
        - Standardization after train-test split
3. Feature Selection
    - Bivariate analysis
        - Pearson's Coorelation and dropping multi-collinear features
4. Model Creation and hyper parameter tuning
    - KNN
        - Dealing with imabalanced classes
        - KNN model training
        - Accuracy metrics - confusion matrix, accuracy score, classification report (precsion, recall,....)
    - Naive Bayes
        - Gaussian Naive bayes training and prediction
        - Accuracy metrics - confusion matrix, accuracy score, classification report (precsion, recall,....)
        - Standardizing and then MinMax Normalization to deal with outliers and to pass positive values as input to GNB model
        - Complement Naive Bayes training and prediction
        - Accuracy metrics 
    - Logistic Regression
         - Logistic regression training and prediction
         - Accuracy metrics
    - SVM
         - SVC training and prediction
         - Accuracy metrics
 5. Final Results
  FINAL TRAINING AND TEST ACCURACY OF EACH MODEL 
<pre>
                          Training accuracy    Testing accuracy <br />

KNN                             0.97                 0.91 <br />
Naive Bayes                     0.90                 0.87 <br />
Logistic Regression             0.97                 0.95 <br />
SVM                             0.97                 0.94 
   
        

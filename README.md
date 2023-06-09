**ICAIML Project - Company Bankrupcy Prediction**

**Data Description:**


**Handling Imbalance Data(Company_Bankruptcy_prediction_Handling_Data_Imbalance.ipynb):**

This notebook contains differnet approaches to handle data imbalance including
1. Resampling
2. Balanced Bagging Classifier
3. SMOTE on Train data
4. SMOTE on full data


**Company_Bankruptcy_Prediction_1_SMOTE_FULL_data.ipynb:**
**Company_Bankruptcy_Prediction_1_SMOTE_train_data.ipynb:**
The Notebook contains the following models:
1. LR with imbalanced dataset
2. LR with SMOTE + FR
3. PR with imbalanced dataset
4. PR with SMOTE +FR
5. DT with imbalanced dataset
6. DT with SMOTE +FR
7. weighted NN with imbalanced dataset
8. NN with SMOTE +FR
9. PCA+NN with imbalanced dataset
10.PCA+NN+FR with SMOTE

**Company_Bankruptcy_Prediction_2a.ipynb:**
**Company_Bankruptcy_Prediction_2b.ipynb:**

2a -> SMOTE performed on full dataset
2b -> SMOTE performed on train data only

Above Notebooks contains the following models:
1. Most relevant feature selection capturing 97% variance in data using PCA
2. Logistic Regression with SMOTE
3. Logistic Regression with SMOTE + PCA reduced feature
4. Decision tree with hyperparameters tuned + SMOTE
5. Decision tree with hyperparameters tuned + SMOTE + PCA reduced feature
6. Random Forest with hyperparameters tuned+ SMOTE
7. Feature importance bar with Random forest
8. Hard Voting Classifier with Logistic regression, Decision Tree and Random Forest
9. Soft Voting Classifier with Logistic regression, Decision Tree and Random Forest


**Company_Bankruptcy_prediction_Adaboosting_with_SMOTE.ipynb**

Above Notebooks contains the following models (SMOTE for the whole data)
1. Ada Boosting + RandomForestClassifier 
2. Ada Boosting + DecisionTreeClassifier 


**Company_Bankruptcy_prediction_Adaboosting_no_SMOTE.ipynb**

Above Notebooks contains the following models (SMOTE only on the training data)
1. Ada Boosting + RandomForestClassifier 
2. Ada Boosting + DecisionTreeClassifier 

**company_bankrupcy_SMOTE_TRANING**

Extracts the data and iterates through the K-Best features (in ranges of 5 till 95)
Identifies the best k features for a model 
      Traning Data has been oversampled using SMOTE
Models
      Adaboost
      Xgboost
      SVM
      Linear regression

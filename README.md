# credit-card-fraud-detection

## Problem Statement:
   A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Data Exploration and Preprocessing:

### Data Loading and Initial Exploration: 
•	The dataset is loaded using pandas, and initial exploration involves checking the first few rows, summary statistics, and data types of the columns. 
### Summary Statistics: 
•	Summary statistics provide insights into the distribution and scale of the data. 
### Checking for Missing Values: 
•	The dataset is checked for missing values, and it was found that there are no missing values in any of the columns. This ensures that the dataset is complete and ready for analysis without the need for imputation. 
### Distribution of Classes: 
•	The distribution of the classes (fraudulent vs. non-fraudulent transactions) is examined to understand the class imbalance, which is crucial for model training and evaluation. 
### Handling Data Imbalance: 
Given the heavily imbalanced nature of the data, several approaches are employed to address this imbalance:
•	Check and Mitigate Skewness: Explaining the techniques used to handle skewness in the data. 
•	Handling Data Imbalance: Describing the methods used to balance the dataset (e.g., SMOTE, ADASYN). Handling data imbalance as we see only 0.17% records are the fraud transactions 

## Model Building
### Algorithms Used: 
•	The model will be trained using a variety of algorithms, including Logistic Regression, Decision Tree, Random Forest, and XGBoost. Each algorithm has unique strengths.
•	 by comparing their performance, we can determine the most effective one for detecting fraudulent transactions.
### Hyperparameter Tuning: 
•	The process of hyperparameter tuning will involve using Grid Search Cross Validation to identify the optimal values for the model's hyperparameters. 
•	This technique systematically searches through a predefined set of hyperparameters and evaluates their performance using cross-validation, ensuring that the model achieves the best possible performance on unseen data.


## Results:
•	The evaluation results for each model will be presented, highlighting the key metrics of Precision, Recall, and ROC-AUC. These metrics will provide a comprehensive view of the model's performance, emphasizing its effectiveness in identifying fraudulent transactions while maintaining a balance between false positives and false negatives. 
•	The results will help determine which model and hyperparameter settings achieve the best performance in detecting fraud within this imbalanced dataset.


  

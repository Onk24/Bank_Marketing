# Bank_Marketing

This case study aims to increase the efficiency of the marketing campaign by predicting whether the client will subscribe to a term deposit. Furthermore, we have done an inferential analysis to find out the potential factors for a successful campaign. <br>


The study is divided into the following 3 parts:
- Exploratory Data Analysis 
- Feature Selection & Inferential Analysis
- Predictive Modeling

**Findings:**
- Inferential Analysis: Following is the list of some important factors determining whether a client would subscribe to a term-deposit 


| Factors | Description
| :-: | :-: |
| Euribor Rate | Euribor 3 month rate - daily indicator |
| Age | Age of the client |
| Campaign Days | No. of contacts performed for this client |
| Contact Type | Cellular or Telephone |
| No. Employees | Number of Employees in the Bank |
| Housing Loan | Yes or No |
| Marital Status | Married or Other |
| Education Level | University degree or Other |


- Predictive Modeling:
Predicting clients subscribing to term-deposit would be very important for the bank’s marketing team to focus efforts on the right candidates. Since the banks need to identify potential clients who would subscribe to a term deposit we focus on the class "yes" for term deposit i.e. people who have subscribed. <br>
Following is the summary of various models: 

| Model | Avg-Precision |F1-Score|
| :-: | :-: |:-: |
|Null - No Features| 0.11|0.20|
| Decision Tree | 0.41 | 0.49|
| Logistic Regression | 0.45 |0.47|
| Random Forest | 0.43 |0.47|
| AdaBoost | 0.47 |0.50|
| K-Nearest Neighbors| 0.29|0.38|
| XGBoost | 0.48 |0.51|




    
**Next Steps:**
- Different metric: Asymmetric misclassification rate can be used with more weightage to false negatives compared to false positives and finding the model with the least asymmetric misclassification rate. False negatives are costlier for the bank as it cannot afford to miss out on a potential client who might subscribe for a term deposit
- More Models: Neural Networks and SVM can be tried on the data for comparison purposes 

# Detect Fraudulent Credit Card transactions using different Machine Learning models and compare performances

In this notebook, I explore various Machine Learning models to detect fraudulent use of Credit cards. I compare each model performance and results. The best performance is achieved using SMOTE technique.

Please note that this approach can be transferred to other detection analysis in alternatrive domains. The feature extraction process remains similar and can be replicated on many other detection issues.

# Problem Statement  
In this project we want to identify fraudulent transactions with Credit Cards. Our objective is to build a Fraud detection system using Machine learning techniques. In the past, such systems were rule-based. Machine learning offers powerful new ways.

The project uses a dataset of 300,000 fully anonymized transactions. Each transation is labelled either fraudulent or not fraudulent. Note that prevalence of fraudulent transactions is very low in the dataset. Less than 0.1% of the card transactions are fraudulent. This means that a system predicting each transaction to be normal can reach an accuracy of over 99.9% despite not detecting any fraudulent transaction. This will necessitate adjustment techniques.  

# Techniques used in the project  
The project compares the results of different techniques :

Machine learning techniques:  
Random Forest  
Decision Trees

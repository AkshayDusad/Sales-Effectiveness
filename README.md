# Product Sales Effectiveness
## FicZon Inc.

# Project Summary
### Requirement
   FicZon Inc is an IT solution provider with products ranging from on-premises products to SAS based solutions. FicZon major leads generation channel is digital and through their website.
   
   FicZon business is majorly dependent on the sales force effectiveness. As the market is maturing and more new competitors entering the market, FicZon is experiencing the dip in sales. Effective sales is dependent on lead quality and as of now, this is based on manual categorization and highly depended on sales staff. Though there is a quality process, which continuously updates the lead categorization, it’s value is in for post analysis, rather than conversation.
    
   FicZon wants to explore Machine Learning to pre-categorize the lead quality and as result, expecting significant increase in sales effectiveness.

PROJECT GOAL:
1. Data exploration insights – Sales effectiveness.
2. ML model to predict the Lead Category.

### Analysis
- The data is supervised and categorical. The predictor variables are nominal. The target variable 'Status' is nominal as well. 
- Most of the columns had a lot of different labels, so we compressed and merged the labels such that only the main ones were included and then used Label Encoding. The predictor variable was categorized into two types 'Good Lead' and 'Bad Lead'.
- SMOTE is used ajdusting the sampling data. For training the data and predicting the target, algorithms used are Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Naive Bayes, K-Nearest Neighbor, XGBoost Classifier and Artificial Neural Network.

### Summary
The project is done with the purpose of finding out the Lead Quality, whether the lead should be followed or not. The company motive is to invest in the right prospects. So therefore we divided the Lead as 'Good' or 'Bad'. This resulted  in increase of accuracy drastically.
    The following steps were carried out:
1. Import the data, find out the predictor and target and drop columns which has no use in analysis.
2. Compress and merge the labels such that only the main ones are included and use Label Encoding.
3. Split it into test and train and use SMOTE.
4. Train the data using algorithms like Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Naive Bayes, K-Nearest Neighbor, XGBoost Classifier and Artificial Neural Network and check the accuracy to find out which algorithm is the best.
5. Export the model with highest accuracy.

### Results
- XGBoost Classifier gave an accuracy of 70%.

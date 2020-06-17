# Credit-Card-Fraud-Detection
Detecting credit card fraud using machine learning and dealing with imbalanced data

<h2> Introduction </h2>
According to Nilson Report, credit card fraud is projected to reach $35.67 billion by 2023 and this billion figure doesn't included expenses related to investigation costs, operations, call centres, chargeback management of fraudulent transactions and external recovery expenses borne by issuers and merchants. This alarming figure show that businesses are suffering monumental losses due to credit card fraud. The share of total business revenue lost to credit card fraud increased 279% between 2013 and 2016. 


In a nutshell, the explosion in credit card fraud is massive and it continues to be a major threat to all businesses - a threat that has potentially crippling financial implications. Although businesses have been investing enormously in credit card fraud protection tools and technology, there's no surefire way to extirpate it completely. But there are things one can do to minimize it and this is the objective of this piece.

<h2> Dataset </h2>
The dataset used is taken from Kaggle. It has credit card transactions made over a two-day period in September 2013 by European cardholders. It contains 284,807 transactions out of which 492 are frauds. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. Each transaction has 30 features, all of which are numerical. Due to confidentiality reasons, the features V1, V2, ..., V28 are the result of a PCA transformation. The features 'Amount' and 'Class' have neither been transformed or scaled. Feature 'Amount' is the transaction amount and 'Class' is the response variable that takes value:
1 if Fraud
0 if Non Fraud

<h2> Imbalanced Data </h2>
In our case, the data is imbalanced and this bias in the dataset can influence the machine learning algorithms leading to ignore the minority class entirely and so it's of utmost importance to first deal with the imbalanced data. We discuss Undersampling, Oversampling and Combined sampling techniques to deal with the imbalanced dataset.

<h2> Models Used </h2>
* Logistic Regression and,
* Random Forest Classifier

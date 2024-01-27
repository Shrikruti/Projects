**Prediction of Credit Card fraud using Machine Learning**
I was exploring different Machine Learning models aimed at detecting fraudulent credit card usage and compared the performance and results of each model. Remarkably, the most effective performance is attained through the implementation of the SMOTE technique.
Problem Statement
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

**Methodology:**
1.	Collect the time series data from the CSV file linked here.
2.	Exploratory Data Analysis (EDA) - Show the Data quality check, treat the missing values, outliers etc if any.
3.	Get the correct datatype for date.
4.	Balancing the data.
5.	Feature Engineering and feature selection.
6.	Train/Test Split - Apply a sampling distribution to find the best split.
7.	Choose the metrics for the model evaluation
8.	Model Selection, Training, Predicting and Assessment
The dataset uses Logistic Regression, Decision Tree, and Random Forest Algorithms. All the three algorithms are performed for imbalanced data, under sampled data and oversampled data. 

**Conclusion:**
From the above examination of an imbalanced dataset, I got to know that for under sampling technique logistic regression with 93.76% is good fit on the predicted data while for oversampling technique Random Forest with 99.99% classifier is the good fit. Comparing both the technique, employing oversampling technique using SMOTE, particularly with the Random Forest classifier, yielded a robust model fit with accuracy score of 99.99%. 
The oversampling method addresses the class imbalance by duplicating instances of the minority class, enhancing the classifier's ability to discern patterns within the underrepresented class and ultimately improving predictive performance. 
The Random Forest algorithm, known for its ensemble nature and ability to handle complex relationships, synergistically benefits from the oversampled data, resulting in a well-tailored model for credit card fraud detection.



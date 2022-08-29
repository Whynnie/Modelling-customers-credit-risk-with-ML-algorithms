# CREDIT RISK MODELLING USING MACHINE LEARNING ALGORITHMS

## INTRODUCTION
Credit risk evaluation is one of the critical and biggest challenges faced in financial institutions. However, analysis of credit scoring is an effective credit risk assessment technique, which is one of the major research fields in the financial institution. Modelling the accuracy plays a very important role in the classification of credit data to avoid financial loss via customers credits. Machine learning has a variety of applications in the banking sector and it has been widely used for data analysis. Modern techniques such as machine learning have provided a self-regulating process to analyze the data using classification techniques. The classification method is a supervised learning process in which the computer learns from the input data provided and makes use of this information to classify the new dataset. This thesis presents a comparison of various machine learning techniques used to evaluate the credit risk. A credit transaction that needs to be accepted or rejected is trained and implemented on the dataset using different machine learning algorithms. The purpose of this study is to identify whether there are improved performances in the classification of consumers’ default when different machine learning algorithms are implemented. The aim is to minimize customers’ risk.

The techniques are implemented on the German credit dataset taken from UCI repository which has 1000 instances and 21 attributes, depending on which the transactions are either accepted or rejected. This thesis compares algorithms such as Support Vector Network, K Nearest Neighbors (KNN), Logistic Regression, Naive Bayes, Random Forest, and Classification and Regression Trees (CART) algorithm and based upon metrics such as Accuracy, Error, Precision, Recall, F1-score and Specificity, the efficiency of the best algorithm was selected. Due to the imbalanced nature of the credit data, the F1-score, which is a weighted average of the Precision and Recall, was eventually used as the metric to assess the best algorithm for loaning credit. 

## FINDINGS
The findings from this study were;
i.	Machine learning algorithms had a better performance compared to the logistic regression and among the machine learning models, Random Forest algorithm showed the best efficiency at modelling customers’ credit risk. This was followed by the Decision Trees algorithm while the logistic regression model performed the worst.

ii.	The measure that was used to capture the efficiency of the models was the F1-score. However, logistic regression did perform well when it came to the Accuracy measure, with an accuracy of 69%. The accuracy measure is however, not a good measure of performance as it does not take into account the cost of misclassification which was captured in the false-positives and false-negatives.

iii.	The presence of data imbalance made overfitting an issue and Random Forest, being an algorithm that is robust against overfitting effects, could have been the reason why it performed best among others.

iv.	To optimize for a better threshold between Precision and Recall, the study conducted a hyperparameter optimization and model tuning and the Random Forest model still outperformed with the F1-score improving to 51% from an initial score of 47%.

v.	The Random Forest classification algorithm used for granting loans under the 0.241 threshold (cut-off), had a loan approval rate of 51.3% and rejection rate of 48.7%.


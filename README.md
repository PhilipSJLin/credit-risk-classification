# Credit Risk Analysis Report
## credit-risk-classification
Homework 20: Using supervised machine learning and a logistic regression model.

## **Overview of the Analysis**
This analysis aims to use various machine learning models to train and evaluate the performance of Logistic Regression Models in identifying the creditworthiness of borrowers and whether they were a high-risk loan(1) or a healthy loan(0). This decision was based on financial factors such as loan size, interest rate, borrower income, income-to-debt ratio, number of accounts, and total debt.<br/>

The models were trained using different methods and were compared to determine which was the best model. We used logistic regression(LogisticRegression) to fit the data and be used for analysis(logistic regression is used to calculate or predict the probability of a binary or yes/no event from occuring which in this case is high-risk or healthy-risk). <br/>
The initial model presented slightly skewed results and thus oversampling was used to improve the overall recall score. <br/>

## **The Results**
The results were based on the Accuary, Precision, and Recall scores. <br/>
***Accuracy tells you how many times the model was correct overall.*** <br/>
***Precision tells you how good the model is at predicting the binary choice.*** <br/>
***Recall tells you how many times the model was able to detect a specific category.*** <br/>

* Machine Learning Model-1(Original Model):<br/>
    *Accuracy: 94%
    *Precision: 87%
    *Recall: 89%
    *The model is very good at predicting the healthy loans. However, the model's precision only predicted 87% of all actual high-risk loans and 89% of all high-risk loans which suggest that margin of error can be improved

* Machine Learning Model-2(Oversampled Model):<br>
    *Accuracy: 99%
    *Precision: 87%
    *Recall: 100%
    *The oversampled logistic regression model has a higher accuracy (99%) in predicting the labels and a higher recall score (100%) in correctly predicting the high-risk loans out of the dataset. The precision score stayed at the same score as the original model.

## **Summary**
Based on the results, Model 2 performed better at predicting high-risk loans and displayed a higher accuracy when compared to Model 1. Based on the nature of our problem, I recommend using an oversampled logistic regression model because it helps us stabilizes our results in predicting both the high-risk (1) and the healthy-risk (0) with highly accurate results.<br/>

## **Data**
For my assignment, I have used data extracted from the following files available in the Resources folder. <br/>
   * lending_data.csv<br/>

In this assignment, I receieved assistance through looking at previous activities, stackoverflow, and received some support through my partner who works in the data analyst field<br/>



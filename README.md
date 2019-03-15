# class8

Van Quang Nguyen

To run the code: python3 class08.py

Basic 1 and 2: Figures

Basic 3:(K-Nearest Neighbors, Logistic Regression, Bayes Inference)

K-Nearest Neighbors classification

Mean accuracy 0.92 

Classification Report

              precision    recall  f1-score   support

           0       0.83      0.97      0.90        67
           1       0.98      0.89      0.94       121

   micro avg       0.92      0.92      0.92       188
   macro avg       0.91      0.93      0.92       188
weighted avg       0.93      0.92      0.92       188

Logistic Regression

Mean accuracy 0.97 

Classification Report

              precision    recall  f1-score   support

           0       0.94      0.97      0.96        67
           1       0.98      0.97      0.97       121

   micro avg       0.97      0.97      0.97       188
   macro avg       0.96      0.97      0.97       188
weighted avg       0.97      0.97      0.97       188

Bayes Inference

Mean accuracy 0.94 

Classification Report

              precision    recall  f1-score   support

           0       0.92      0.91      0.92        67
           1       0.95      0.96      0.95       121

   micro avg       0.94      0.94      0.94       188
   macro avg       0.94      0.93      0.94       188
weighted avg       0.94      0.94      0.94       188


REACH: Pseudocodes:

Program GaussainNB
	import dataset function.
	import GaussianNB as GNB.
	import train_test_split.
	Split data into training data and testing data.
	Create an classifier object.
	Fit the model with training datafit.
	Predict the label on testing data.
	Compute the score with prediction and test labels.
	Print score.
	Compute classification report with testing data.
	Print Classification report.


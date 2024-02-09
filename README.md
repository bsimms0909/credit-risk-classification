# Credit-Risk-Classification

## Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Credit Risk Analysis Report
The purpose of this credit risk analysis is to develop a machine learning model that can accurately predict the risk associated with loans. This analysis helps financial institutions in assessing creditworthiness, thereby minimizing default risks and improve lending tactics.

## Model Performance Metrics:
Confusion Matrix results:
True Positives: 590
True Negatives: 18686
False Positives : 106
False Negatives : 2

## Accuracy Score:
Original Logistic Regression Model: 99.25%
Logistic Regression Model with Resampled Data: 99.44%

## Precision and Recall Scores:
Original Logistic Regression Model:
Precision for label 0 (healthy loan): 100%
Precision for label 1 (high-risk loan): 85%
Recall for label 0: 100%
Recall for label 1: 91%

## Logistic Regression Model with Resampled Data:
Precision for label 0: 100%
Precision for label 1: 85%
Recall for label 0: 99%
Recall for label 1: 100%
Summary of Results:

## Original Logistic Regression Model:
Accuracy: 99.25%
Precision for predicting healthy loans (label 0) is perfect, while precision for high-risk loans (label 1) is 85%. Recall for both labels is relatively high.
The model is doing well identifying healthy loans but slightly less so for high-risk loans. Despite its high accuracy, the model may need some improvements to improve precision and recall for high-risk loans.

## Logistic Regression Model with Resampled Data:
Accuracy: 99.44%
Precision and recall for both labels have improved significantly after resampling.
The model exhibits exceptional performance in predicting both healthy and high-risk loans. With a precision of 85% for high-risk loans and a recall of 100%, this model provides reliable predictions, making it suitable for practical use in credit risk assessment.

# Recommendation:
After studying the data, I recommend using the Logistic Regression Model with Resampled Data for checking credit risks. This model is really good at figuring out who can pay back loans and who might have trouble. It works well for both safe and risky loans. By fixing the problem of uneven data, it becomes even better at predicting who might have trouble repaying loans. The logistic regression has a score of 99.44%, indicating that the model is effective in making correct predictions. I think this will be reliable in predicting healthy or high-risk loans. 

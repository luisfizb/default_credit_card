# default_credit_card
repo for the prediction of probability of default of credit card clients

Develops and evaluates a predictive model for estimating the probability of default of credit card holders using logistic regression, prioritizing interpretability of the covariates.
We tested four different models, comparing metrics such as Recall, F1-Score, Accuracy, and R2. The model with the highest Recall was selected to predict the greatest number of defaults cases. After that, the odds ratios were calculated from the coefficients to interpret the probability.
The data used was financial and demographic information about credit card holders from Taiwan. The demographic variables are age, education, civil status, and the financial variables are payment status, payment amount, and bill amount statements over a period of 6 months.
The key variables identified by the model were the payment status one month prior to default, gender, total payments in full, and the number of months with zero bill statements.

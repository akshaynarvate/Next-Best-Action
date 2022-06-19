# Next-Best-Action for Standard Bank :-

### - Proactively finding whether the customer is going to churn or not.

### - Random Forest gave best accuracy with greater stability

### Analysis :

### * The Target variable is highly imbalannced
### * Age feature is positively skewed
### * When considered age feature, mostly of the churn customers fall under the age range of 40-60
### * customer who are married or single tend to churn
### * Transaction S1 matters in identifying the churnesss of the customers
### * Executive class are lesser in number yet have high rate of churn
### * Avg years spend with the bank is 14

### Test Accuracy
	XGBoost  |    Random Forest  |	Logistic Regression |   SVM 
	82.00%   |          84.00%    |        82.00%       |   84.00% 

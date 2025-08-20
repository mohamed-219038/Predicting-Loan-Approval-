# Dataset description:
This data set would provide you enough taste of working on data sets from insurance companies, what challenges are faced, what strategies are used, which variables influence the outcome etc. This is a classification problem. The data has 615 rows and 13 columns.
#Objective
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


# Methodology :
<H3> 1- Logistic regression  without hyperparmters tuning: <H3\>
the test score was: 68.18%

<H3> Logistic regression with hyperparmters tuning (regulization):<H3/>
test Score: 70.78%

  
H 2- descioin tree without hyperparmters tuning:  ____> # OVERFITTING
Train Result:
================================================
Train Score: 100.00%

_______________________________________________

Test Result:
================================================
Accuracy Score: 57.79%
_______________________________________________

<H3> 2- descioin tree with hyperparmters tuning: <H3\>

Fitting 3 folds for each of 4332 candidates, totalling 12996 fits
Best paramters: {'criterion': 'gini', 'max_depth': 1, 'min_samples_leaf': 15, 'min_samples_split': 2, 'splitter': 'best'})
Train Result:
================================================
Accuracy Score: 68.07%



Test Result:
================================================
Accuracy Score: 70.78%



# Note that the <h1> GRID SEARCH is used in bothways for hyperparams tunning<h1\>





# so the decision tree with hyperparam tunning is the best algorithm used.





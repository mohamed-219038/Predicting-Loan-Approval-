# Dataset description:
This data set would provide you enough taste of working on data sets from insurance companies, what challenges are faced, what strategies are used, which variables influence the outcome etc. This is a classification problem. The data has 615 rows and 13 columns.
#Objective
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


# Methodology :

# 1- Logistic regression  without hyperparmters tuning: 
the test score was: 83.5%


# 2-Logistic regression with hyperparmters tuning (regulization):
test Score: 83.5%

  
3- descioin tree without hyperparmters tuning:  ____>OVERFITTING
Train Result:
================================================
Train Score: 100.00%

_______________________________________________

Test Result:
================================================
Accuracy Score: 77.09%
_______________________________________________


# 4- descioin tree with hyperparmters tuning: 

Fitting 3 folds for each of 4332 candidates, totalling 12996 fits
Best paramters: {'criterion': 'gini', 'max_depth': 3, 'min_samples_leaf': 1, 'min_samples_split': 4, 'splitter': 'random'})
Train Result:
================================================
Accuracy Score: 81.22%



Test Result:
================================================
Accuracy Score: 84.71%



# 5- random forest  without hyperparmters tuning: ___>(OVERFITTING)


Train Result:
================================================
Accuracy Score: 100%



Test Result:
================================================
Accuracy Score: 83.53%





# 6- descioin tree with hyperparmters tuning: 

Fitting 3 folds for each of 100 candidates, totalling 300 fits
Best paramters: {'n_estimators': 400, 'min_samples_split': 5, 'min_samples_leaf': 4, 'max_depth': 30, 'bootstrap': True})
Train Result:
================================================
Accuracy Score: 84.01%



Test Result:
================================================
Accuracy Score: 83.53%




# Note that the <h1> GRID SEARCH is used in ALL ways for hyperparams tunning





# so the RANDOM FOREST is the best algorithm used with the best score.









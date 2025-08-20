# Dataset description:
This data set would provide you enough taste of working on data sets from insurance companies, what challenges are faced, what strategies are used, which variables influence the outcome etc. This is a classification problem. The data has 615 rows and 13 columns.
#Objective
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


# Methodology :
<H3> 1- Logistic regression  without hyperparmters tuning: <H3\>
the test score was: 68.18%
  _______________________________________________
CLASSIFICATION REPORT:
              0           1  accuracy   macro avg  weighted avg
precision   0.0    0.690789  0.681818    0.345395      0.479964
recall      0.0    0.981308  0.681818    0.490654      0.681818
f1-score    0.0    0.810811  0.681818    0.405405      0.563356
<H3> Logistic regression with hyperparmters tuning (regulization):<H3/>
test Score: 70.78%
_______________________________________________
CLASSIFICATION REPORT:
                   0           1  accuracy   macro avg  weighted avg
precision   0.625000    0.712329  0.707792    0.668664      0.685676
recall      0.106383    0.971963  0.707792    0.539173      0.707792
f1-score    0.181818    0.822134  0.707792    0.501976      0.626713
  
<H3> 2- descioin tree without hyperparmters tuning: <h3\> ____> # OVERFITTING
Train Result:
================================================
Accuracy Score: 100.00%
_______________________________________________
CLASSIFICATION REPORT:
               0      1  accuracy  macro avg  weighted avg
precision    1.0    1.0       1.0        1.0           1.0
recall       1.0    1.0       1.0        1.0           1.0
f1-score     1.0    1.0       1.0        1.0           1.0
support    117.0  240.0       1.0      357.0         357.0
_______________________________________________

Test Result:
================================================
Accuracy Score: 57.79%
_______________________________________________
CLASSIFICATION REPORT:
                   0           1  accuracy   macro avg  weighted avg
precision   0.285714    0.687500  0.577922    0.486607      0.564877
recall      0.255319    0.719626  0.577922    0.487473      0.577922
f1-score    0.269663    0.703196  0.577922    0.486430      0.570884

<H3> 2- descioin tree with hyperparmters tuning: <H3\>

Fitting 3 folds for each of 4332 candidates, totalling 12996 fits
Best paramters: {'criterion': 'gini', 'max_depth': 1, 'min_samples_leaf': 15, 'min_samples_split': 2, 'splitter': 'best'})
Train Result:
================================================
Accuracy Score: 68.07%
_______________________________________________
CLASSIFICATION REPORT:
                    0           1  accuracy   macro avg  weighted avg
precision    0.578947    0.686391  0.680672    0.632669      0.651178
recall       0.094017    0.966667  0.680672    0.530342      0.680672
f1-score     0.161765    0.802768  0.680672    0.482266      0.592691
support    117.000000  240.000000  0.680672  357.000000    357.000000
_______________________________________________


Test Result:
================================================
Accuracy Score: 70.78%
_______________________________________________
CLASSIFICATION REPORT:
                   0           1  accuracy   macro avg  weighted avg
precision   0.625000    0.712329  0.707792    0.668664      0.685676
recall      0.106383    0.971963  0.707792    0.539173      0.707792


# Note that the <h1> GRID SEARCH is used in bothways for hyperparams tunning<h1\>





# so the decision tree with hyperparam tunning is the best algorithm used.



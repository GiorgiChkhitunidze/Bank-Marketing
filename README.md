# Bank-Marketing
  Predict if the client will subscribe a term deposit

In these notebook I tried to predict bank term deposit subscription. I also wanted to test RAPIDS GPU accelerated algorithms. Briefly speaking, that's what I did:
- First, some preprocessing using scikit-learn library
- Second, cross validation using scikit-learn StratifiedKFold and XGBClassifier and RAPIDS GPU accelerated models (RandomForestClassifier, LogisticRegression, KNeighborsClassifier)
- Third, fine tune the best model
- Fourth, prediction on a test set
- Fifth, interpret results

# References:
Moro,S., Rita,P., and Cortez,P.. (2012). Bank Marketing. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.

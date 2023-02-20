# supervised-machine-learning-challenge
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

In this challenge, I used data to create machine learning models to classify the risk level of given loans. Specifically, the Logistic Regression and Random Forest Classifier models were compared.

An initial prediction that the Logistic Regression would be the most accurate turned out to be wrong. The Logistic Regression and Random Forest models had a test score of 0.9021 and 0.8624, respectively. Thus, based solely on test score, the LR model performed better. However the accuracy for LR and RF models was 0.9021 and 0.9160, suggesting that the Random Forest model had a slight edge against Logistic Regression. Given that the confusion matrix is "a summary of prediction results on a classification problem, and that it provides insight not only into the errors being made by your classifier but more importantly the types of errors that are being made" (Brownlee, 2020), I think the best metric is model accuracy. In conclusion, the Random Forest model performed better for this data set, which does not match my initial prediction. 

Reference used: Jason Brownlee. 2020. What is a Confusion Matrix in Machine Learning. https://machinelearningmastery.com/confusion-matrix-machine-learning/
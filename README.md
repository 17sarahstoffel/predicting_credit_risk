# predicting_credit_risk
This is my solution to homework 19 for data bootcamp


# Prediction

I think that the Logistic Regression Model will do better than the Random Forest Classifier Model. The Random Forest Model works better with more categorical data and since this data set is made up of numeric data, I think the Logistic Regression will do better.


# Results

From my model score results, both the Logistic Regression and the Random Forest scores are very very close, but the Logistic Regression performed 4 ten thousandths of a point better (0.0004). This falls in line with my prediction, but it is much closer than I expected. I would like to explore what would happen if I scaled the data.

After scaling the data, the Logistic Regression score improved but the Random Forest stayed the same. Now the Logistic Regression score is 2 thousandths of a point better (0.002). This still falls in line with my hypothesis and the scores are still really close. I do think that the Logistic Regression performed better since the data was more numerical. There is one column, derogatory_marks that is categorical and I think helps the Random Forest model. Either way, since both models’ scores are so close, I think either model will be a really good predictor of if a loan will be approved or not.




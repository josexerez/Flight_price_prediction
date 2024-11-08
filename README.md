This project focuses on predicting flight prices, starting with some data preparation to make sure everything’s ready for modeling.
I used One-Hot Encoding for the categorical columns and Ordinal Encoding for the "stops" column to handle the data properly. 
After trying out a few different models, Random Forest Regression turned out to give the best results, with an error (RMSE) of around 13%. 
Initially, there was a lot of overfitting, so I implemented RandomizedSearchCV to find the best model.
The features that most affect the price are class, which helped the model make more accurate predictions by focusing on what matters most for pricing.

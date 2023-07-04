# Marketing Campaigns Bank

The objectives are to find what variables are important for obtaining a subscriber and to create a model that can correctly predict a potential client’s preference towards the term deposit (product). The models are created by using Naive Bayes, Decision Tree and Random Forest method.

# End Result 

The project can be viewed in my Rpubs at this link: https://rpubs.com/Fib_Gro/Marketing_Campaign

# Dataset information 

The dataset is collected from the UCI website. The data is related to the marketing campaigns of a Portuguese bank. The campaign is through phone calls. We use the “bank-full.csv” dataset, which contains 45,211 rows and 17 variables. Our target variable is y (status of the client’s subscription). 

# Attachment 

- csv file 
- Rmd file 
- Picture for introduction 
- The Random Forest RDS file is not attached due to the limitation of the Github file size (Feel free to contact me for requesting the file)

# Insight / Conclusion : 

1. The summary table shows that the model with Random Forest using K-fold cross-validation and Decision Tree produce high values of accuracy. It implies that this model is appropriate to be used to correctly predict the customer’s preference toward the term deposit (product).
2. All models have a relatively low precision value. It implies that the models bad at minimizing false positives. Since the model with Random Forest has the highest value of precision, this model might be used to reduce labour costs by avoiding calling uninterested customers. However, some improvement is acquired to increase the value.
3. If the objective of the bank is to increase the number of customers and does not want to lose any opportunities, the model with Naive Bayes is the appropriate model to be used. It is confirmed by the highest value of sensitivity.
4. To be concluded, the model with Random Forest with K-fold cross-validation is the best model for our project objective, confirmed by the highest values of accuracy and AUC.


The goal of this notebook is to understand and predict customer churn for a bank. Specifically, we will initially perform **Exploratory Data Analysis** (**EDA**) to identify and visualise the factors contributing to customer churn. This analysis will later help us build **Machine Learning** models to predict whether a customer will churn or not. 

This problem is a typical **classification** task. The task does not specify which performance metric to use for optimising our machine learning models. I decided to use **recall** since correctly classifying elements of the positive class (customers who will churn) is more critical for the bank.

*Models Used: Logistic Regression, Support Vector Machines, Random Forests, Gradient Boosting, XGBoost, and Light Gradient Boosting Machine.*

 - EDA can help us identify which features contribute to customer churn. Additionally, feature importance analysis can quantify the importance of each feature in predicting the likelihood of churn. Our results reveal that the most significant feature is age (older customers are more likely to churn), followed by the number of products (having more products increases a customer’s likelihood to churn). The bank could use our findings to adapt and improve its services in a way that increases satisfaction for those customers more likely to churn.

 - Here we can build several machine learning models with recall approximately equal to 78%, meaning that they can successfully detect almost 80% of those customers more luckily to churn. Perhaps, adding more features or/and records could help us improve predictive performance. Therefore, the bank could benefit from investing in gathering more data.

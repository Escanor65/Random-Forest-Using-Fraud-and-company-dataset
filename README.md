# Random-Forest-Using-Fraud-and-company-dataset
It looks like you have written code in Python for building and evaluating Random Forest classifiers on two different datasets. The first dataset is for predicting the risk level of a person based on their financial and demographic information, while the second dataset is for predicting the sales category of a product based on its marketing and sales data.

In the first dataset, you converted the "Taxable.Income" column into a categorical variable and created dummy variables for the categorical features. Then, you split the data into training and testing sets and applied a Random Forest classifier using 10-fold cross-validation. The code outputs the accuracy of the model in predicting the risk level of a person.

In the second dataset, you performed some exploratory data analysis (EDA) by creating a new categorical variable "SalesCategory" based on the "Sales" column and created dummy variables for the categorical features. Then, you split the data into training and testing sets and applied two Random Forest classifiers using 10-fold cross-validation, one with criterion 'entropy' and another with criterion 'gini'. The code outputs the accuracy of both models in predicting the sales category of a product.

Overall, your code seems well-structured and follows the standard practice of data preprocessing, model building, and model evaluation using cross-validation. However, it's important to note that there's always room for improvement in terms of feature engineering, hyperparameter tuning, and model selection.





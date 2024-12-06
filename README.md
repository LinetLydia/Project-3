# Customer Churn Prediction Project

### Overview

The project focuses on predidcting customer churn for a telecom company using machine learning techniques. The primary goal is to develop a model capable of predicting whether a customer will churn(Leave the company) based on various features, including their usage patterns and service subscriptions. By identifying high-risk customers, the company can proactively design retention strategies to improve customer satisfaction and reduce churn rates.


### Business and Data Understanding

The stakeholders in this project include the telecome company's customer service, marketing and management teams. The dataset used for this analysis comes from the SyriaTel Customer Churn dataset, that contains customer information such as account length, usage statistics and whether the customer has churned. The company wants to use this data to predict customer churn and design retention strategies.

The data includes both numerical features (such as total minutes used during the day, night and international calls) and categorical features (such as whether the customer has a voice mail plan or an international plan). This allows for a mix of techniques to build the predictive model.

### Data Preparation

The dataset underwent multiple data preparation steps, including handling missing values, encoding categorical variables and scaling numerical features. This ensures that the data is clean and ready for modeling. The columns considered in this project include customer usage statistics, plan details and the churn status of each customer.

### Modeling

Three machine learning models were used for this project: Logistic Regression, Random Forest Classifier and XGBoost. These models were chosen for their ability to handle classification tasks and provide accurate interpratable results.

1. Logistic Regression served as a baseline model, providing simplicity and interpretability.
2. Random Frest Classifier demonstrated superior performance in predicting customer churn, offering a balance betwween precision and recall.
3. XGBoost provided high accuracy and fast execution, further boosting the overall performance

Hyperparameter tuning was performed on each model to enhance their performance. Among the three, Random Forest Classifier showed the best results, followed closely by XGBoost.

### Evaluation

The performance of the models was evaluated using several metrics:

1. Accuracy: The overall correctness of the model.
2. Precision and Recall: To asses the balance between correctly predicting churned customers and minimizing false positives.
3. Confusion Matrix: To show the distribution of true positives, false positives, true negatives and false negatives.
4. ROC - AUC Score: To measure the model's ability to distinguish between the classes (churned vs non-churned).
5. Cross - Validation: To evaluate the robustness and generalizability of the models.

XGBoost was the best performer because of its quick execution and great precision. Additionally, the Random Forest Classifier performed well, with a ROC-AUC score of 0.91 and an accuracy of 92.9%. Lower accuracy was offered by logistic regression, which was mostly employed for comparison.

### Conclusion 

The best model for forecasting customer attrition was XGBoost, which demonstrated strong performance and excellent accuracy. The telecom business can utilize the findings from this model to proactively identify customers who are at risk of leaving and adopt focused retention measures, such better customer assistance and personalized offers. This study demonstrates how important feature engineering, model selection, and data preparation are to creating a successful churn prediction system.

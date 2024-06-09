# Predicting Customer Churn: A Comprehensive Analysis

## Introduction
In today's highly competitive business landscape, retaining customers has become a crucial strategy for organizations to maintain a sustainable and profitable operation. Customer churn, the phenomenon where customers discontinue their relationship with a company, can have significant financial implications. This project aims to delve into the analysis and prediction of customer churn using a comprehensive dataset.

## Dataset
The dataset used in this project includes the following features:
- `age`: The age of the customer.
- `tenure`: The duration (in years) the customer has been with the company.
- `nationality`: The nationality of the customer.
- `balance`: The current account balance of the customer.
- `salary`: The annual salary of the customer.
- `score`: A customer credit score.
- `card`: The type of card the customer has.
- `gender`: The gender of the customer.
- `active`: Whether the customer is currently active or not.
- `products`: The number of products the customer has with the company.
- `Age bins`: A new feature created through feature engineering, which categorizes the customers into different age groups.

## Data Exploration and Visualization
To gain a deeper understanding of the dataset, we conducted extensive data exploration and visualization. This process involved analyzing the distributions, correlations, and patterns within the data. Some of the key insights obtained from the visualizations include:

1. **Age Distribution**: The age distribution of the customers reveals that the majority of the customer base is in the middle-aged range, with a significant number of younger and older customers as well.

2. **Tenure and Churn Rate**: The analysis of customer tenure shows a direct correlation between tenure and churn rate, with longer-tenured customers being less likely to churn.

3. **Balance and Churn**: The relationship between customer balance and churn rate suggests that customers with higher account balances are less likely to churn, indicating the importance of financial stability in retaining customers.

4. **Gender and Churn**: The data reveals that there is a slight difference in churn rate between male and female customers, which could be an important factor to consider in the customer retention strategy.

5. **Active Customers and Churn**: The analysis of active customers versus inactive customers shows a significant difference in churn rate, highlighting the importance of maintaining an active customer base.

Through these visualizations and insights, we were able to answer key business questions and gain a comprehensive understanding of the factors influencing customer churn.

## Data Preprocessing and Resampling
Before training the machine learning models, we conducted thorough data preprocessing. This included handling missing values, encoding categorical variables, and scaling the numerical features. Additionally, as some of the features in the dataset were imbalanced, we used the Synthetic Minority Over-sampling Technique (SMOTE) to resample the data and ensure a more balanced representation of the target variable (churn).

## Machine Learning Models
To predict customer churn, we trained several machine learning models, including:
- Logistic Regression
- K Nearest Neighbors
- Random Forest
- GradientBoostingClassifier

Each model was evaluated using various performance metrics, such as accuracy, precision, recall, and F1-score, to ensure the most effective model for predicting customer churn.

## Results and Insights
The machine learning models provided valuable insights into the key factors influencing customer churn. Additionally, the model performance metrics indicated that the Random Forest model achieved the highest accuracy and F1-score in predicting customer churn.

## Conclusion and Future Recommendations
This project demonstrates the power of data-driven decision making in the context of customer churn analysis. By leveraging the insights gained from the data exploration, feature engineering, and machine learning models, organizations can develop targeted strategies to improve customer retention and reduce churn rates.


## Get Involved
If you're interested in collaborating on this project or have any questions, feel free to reach out to me. I'm always excited to engage with the community and explore new ways to tackle the challenge of customer churn.

Happy coding and may the odds be ever in your favor!

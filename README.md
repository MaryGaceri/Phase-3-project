# Telecom Churn Prediction for SyriaTel: Identifying Patterns for Customer Retention

## Overview

This project focuses on helping SyriaTel predict and reduce customer churn, where customers stop using their services. Churn prediction is crucial for businesses to prevent revenue loss.

### Target Audience

This project's target audience includes SyriaTel executives, data analysts, and customer service teams seeking strategic insights. Marketing teams and financial analysts will benefit from tailored retention strategies and financial implications. Regulatory authorities and industry analysts gain market competitiveness insights. Internal teams, including UX and product development, can enhance customer experience based on project findings.

# Business Understanding

# Introduction
This project centers on SyriaTel, a prominent telecommunications company, seeking to predict and reduce customer churn. Customer churn, defined as customers discontinuing services, poses a significant challenge to businesses. Our focus is to leverage data analysis and machine learning techniques to unveil patterns indicative of potential customer exits. By identifying these patterns, SyriaTel can proactively implement measures to retain customers and mitigate revenue loss. The project involves thorough data analysis, the development of predictive models, and the formulation of actionable recommendations to enhance customer retention strategies. The overarching goal is to augment SyriaTel's understanding of customer behaviors, ultimately contributing to more effective retention initiatives.


## Main Objective

The main objective of this project is to apply classification modeling techniques to analyze customer churn data for Syria Tel, aiming to identify and quantify the influential factors contributing to customer churn.

## Subjectives Objective
1.Explore the Data for Classification Explore the dataset to understand the relationships between different variables and the target variable (customer churn)

2.Develop accurate machine learning models for predicting customer churn based on historical data.

3.Identify and analyze patterns and trends in customer behavior that contribute to churn.

4.Evaluate model performance and fine-tune hyperparameters for optimal predictive accuracy.

5.Provide actionable insights and recommendations based on churn predictions to aid SyriaTel in implementing effective customer retention strategies.

## Data Understanding

In the data understanding phase, a thorough examination of the Telecom Churn dataset was conducted, focusing on customer-related features and the target variable, churn. Key activities included identifying data types, addressing missing values, and generating descriptive statistics for numeric variables. Exploratory Data Analysis (EDA) provided valuable visual insights, especially in understanding data distributions and relationships. Categorical variables were examined for potential one-hot encoding, and target variable exploration shed light on the distribution of churn instances. Correlation analysis contributed to identifying potential multicollinearity. Integration of domain knowledge enhanced the understanding of variable significance. The comprehensive assessment of data quality laid a solid foundation for subsequent data preprocessing and model development stages.


## Results and Interpretation

## Baseline Model:
Logistic Regression:

Accuracy: Around 87% Precision for Churn: 68% Recall for Churn: 18% Findings: The Logistic Regression model performs reasonably well in predicting non-churn instances but struggles to identify churn cases, as indicated by its low recall score. It's somewhat accurate but needs improvement in capturing churn instances effectively


## More complex model
In the Random Forest model, Accuracy: Approximately 89% Precision for Churn: 84% Recall for Churn: 32% Findings: The Random Forest model shows improvement compared to Logistic Regression. It achieves better balance in precision and recall for churn. However, it still faces challenges in identifying churn cases effectively.

## XGBoost Classifier:

Accuracy: Roughly 91% Precision for Churn: 85% Recall for Churn: 47% Findings: The XGBoost model demonstrates the highest accuracy among the three models and significantly improves identifying churn instances. While the balance between precision and recall is better, there's still room for enhancing the recall score for churn.

Overall : Best Model: XGBoost Classifie Reasoning: XGBoost stands out by being the most accurate and striking a good balance between finding all actual churn cases and minimizing incorrect predictions. It excels at identifying customers who are likely to churn compared to Logistic Regression and Random Forest models.

Improvement Areas:All models face challenges in accurately pinpointing instances of churn, suggesting the necessity for improvements. This could involve delving deeper into the data, enhancing features, or exploring alternative modeling techniques to better grasp and predict patterns associated with customer churn.


## Conclusion
All models exhibit predictive abilities, with XGBoost showing particular promise in predicting customer churn due to its elevated accuracy and improved ability to identify churn cases. Nevertheless, there is room for improvement in refining the models to enhance churn prediction, with a focus on increasing recall while maintaining precision.

## Summary:
The XGBoost model performed the best with an accuracy of around 91%, while Random Forest and Logistic Regression also showed good accuracy, around 89% and 87% respectively.

All models prove useful in predicting customer churn, offering valuable insights for identifying at-risk customers and understanding the factors that impact churn, like 'customer service calls,' 'international plan,' and 'total day minutes.'

Notably, customers with an international plan have a significant churn rate, suggesting the importance of tailored retention strategies to keep them engaged.

## Recommendations based on churn predictions to aid SyriaTel in implementing effective customer retention strategies.¶

1.Improve Customer Service Experience
2.Communicate oactively
3.Understand Churn Indicators

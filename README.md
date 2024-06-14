![Header Image](https://github.com/andmercado/Capstone-Project-Group-6/assets/159932014/7409f5bc-d706-4524-a64a-4eab1d0351f0)

## LoyalLock: Predictive Modeling for Customer Segmentation and Churn Reduction

Significant revenue losses due to customer churn are a critical issue in the credit card industry. This proposal offers a solution that enables companies to use data analysis to predict potential customer churn in advance. The predictive approach encourages companies to incentivize customers who are likely to churn, thereby reducing the probability of their departure and securing revenue. 

## Business Understanding and Data Understanding

### Business Understanding

In the competitive realm of credit card companies, each firm offers a wide range of incentives to attract and retain customers. These incentives include reward systems that allow customers to redeem rewards for travel, card statements, or gift cards, and offering low interest rates on balances. Customer retention is crucial for sustaining revenue growth and fostering long-term profitability.

The key stakeholders include the credit card companies who seek to decrease customer churn, the customer service and marketing teams who may need to adjust their operations and strategies based on our insights, and the customers who will benefit from improved services and retention incentives.

This proposal aims to recognize the importance of retaining clientele by implementing and developing a predictive analytics tool to forecast customer churn by enabling proactive measures to mitigate churning rates effectively. Our primary goal is to identify potential churning among credit card company's customers and harness the retention. We would investigate the identifying factors within the data set that we feel contribute to the customer churn. We would then perform evaluations with models to increase customer retention. By carefully analyzing these predictions and creating an analysis, credit card companies can then tailor their retention rates by implementing strategies to incentivize their current customers that are at risk of churning.

To enable our predictive analytic models, we would require specific customer data. Using this data, we will be able to strategically plan and allocate resources to overcome potential challenges. The predictive modeling insights will guide changes to increase customer retention. This process may involve modifying current marketing strategies or enhancing customer service operations. However, with the correct approach and by leveraging the insights obtained from our predictive analytics, we are confident that any arising challenges can be effectively addressed, leading to improved customer retention and business growth.

### Data Understanding

The dataset from Kaggle is designed to help predict when customers might stop using their credit cards. This dataset includes information on how customers spend, who they are, how they interact with the company, and details about their accounts. 

**Transactional Data**: Shows how customers are spending their money.

**Demographic Data:** Information like age, gender, income, and job status.

**Account Information:** Details like how long they’ve had their account and what type of card they use.

We have data on thousands of customers, which gives us a lot of information to work with. We look at average spending, types of customers, and how often they engage with services.

**Spending and Engagement**: These tell us a lot about how happy customers are and if they might leave.

**Account Details:** These help us understand how deep and strong the relationship with the customer is.


This data is great for spotting customers who might leave and helping us figure out how to keep them. However, there are some issues with missing information, how current the data is, and if it applies to everyone everywhere. Although there are some issues with missing information, this dataset is a strong starting point for building models that predict customer churn, helping us keep customers happy and connected. We need to handle the data carefully and keep it up to date to make sure our predictions are as accurate as possible.

Data Set from Kaggle: 

https://www.kaggle.com/datasets/thedevastator/predicting-credit-card-customer-attrition-with-m

References

Dey, S. (2022, May 7). [Building Comprehensible Customer Churn Prediction Models](https://medium.com/swlh/building-comprehensible-customer-churn-prediction-models-ca61ecce529d). Medium.


## Modeling and Evaluation

Our team started with Logistic Regression to establish a baseline accuracy score for this binary classification task.

During the feature selection process, we incorporated Principal Component Analysis (PCA) for dimensionality reduction, which simplified our high-dimensional data into fewer principal components, enhancing model performance by minimizing overfitting.

We explored the K-Nearest Neighbor model, utilizing its ability to classify outcomes based on feature proximity.

The Random Forest algorithm was employed for its capability to handle many variables, reduce overfitting, and identify the most critical features contributing to customer churn.

After evaluating the above models, we decided to proceed with the Decision Tree model due to its excellent interpretability in rule-based classification.

We also used the K-Means algorithm, an unsupervised learning method, to segment customers into different groups based on their behaviors or characteristics, identifying patterns indicative of churn.


## Conclusion

Our team recommends using the model to mitigate customer churn by implementing a sophisticated predictive modeling approach that leverages customer data to identify individuals at risk and tailor retention strategies accordingly. By collecting and analyzing data, our model can pinpoint the key factors contributing to churn. Continuous monitoring and refinement of the model ensures it adapts to evolving customer behaviors, ultimately leading to improved retention rates, customer loyalty, and sustained business growth.


## Repository Navigation
Final Notebook Link: https://github.com/andmercado/Capstone-Project-Group-6/blob/main/final_notebook.ipynb

Final Presentation Link: https://github.com/andmercado/Capstone-Project-Group-6/blob/main/CAPSTONE%20PPT.pptx

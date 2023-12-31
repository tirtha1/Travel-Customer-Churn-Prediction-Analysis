# Travel-Customer-Churn-Prediction-Analysis
The Travel Customer Churn Prediction model is a powerful tool built using Logistic Regression and Random Forest Classifier algorithms to forecast and identify potential customer churn within the travel industry.

The Travel Customer Churn Prediction model is a powerful tool built using Logistic Regression and Random Forest Classifier algorithms to forecast and identify potential customer churn within the travel industry. The model utilizes historical customer data, including various demographic, transactional, and behavioral features, to accurately predict whether a customer is likely to churn or not.



Logistic Regression is a well-known statistical algorithm that is widely used for binary classification problems. This model analyzes the relationship between the dependent variable (churn) and the independent variables (customer attributes) to estimate the probability of churn. It considers factors such as age, travel preferences, flying history, and other relevant metrics to make predictions.



The Random Forest Classifier is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy. It constructs a multitude of decision trees and averages their predictions to make a final prediction. By using this approach, the model can capture complex relationships and interactions between different features, leading to more robust and accurate predictions.



The Travel Customer Churn Prediction model aims to help travel companies proactively identify customers who are likely to churn in the near future. By identifying these high-risk customers, travel companies can implement targeted retention strategies, such as personalized offers, proactive customer service, or loyalty programs, to prevent churn and improve customer satisfaction. Ultimately, this predictive model assists businesses in optimizing their customer retention efforts, enhancing customer loyalty, and maximizing revenue.


Here are some images of our model:

![image](https://github.com/tirtha1/Travel-Customer-Churn-Prediction-Analysis/assets/37182361/bf0562f6-b97a-45a8-b2a2-3c403b421d33)

![image](https://github.com/tirtha1/Travel-Customer-Churn-Prediction-Analysis/assets/37182361/ea9f8fa6-f07b-4b74-85ed-061b0b34c085)

![image](https://github.com/tirtha1/Travel-Customer-Churn-Prediction-Analysis/assets/37182361/77316fba-09c2-40e0-82a5-2f45d2fb1c2f)

![image](https://github.com/tirtha1/Travel-Customer-Churn-Prediction-Analysis/assets/37182361/37c24806-85f6-43f0-9776-6693abf50420)


# Main results summary:

The key indicators of customer churn were age, frequent flyer status, and income class. Specifically, 

 * younger customers (27-28y) tend to churn proportionally more often
 * frequent flyers churn more than non-frequent flyers   
 * high-income individuals churn more than low and middle-income classes  

Of the compared models, the balanced bagging classifier performed best in order to predict customer churn. It performed with an overall accuracy of 90%, as well as an F1 score of 81 and other performance metrics >70 for the minority class. Given that it may be most important to correctly identify those customers who churn, the priority is to predict the minority class correctly. Thus, using a classifier focusing on balancing the data set and therefore boosting performance to identify those customers who churn, so they can be the focus of measures to improve customer satisfaction.  

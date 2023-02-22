This Repository consists files of the ML Project - customer life time value on for an auto insurance company, It is an academic project for the PG Program in Data Science & Analytics @ Insofe.

Files :

i. Train.csv  - https://drive.google.com/file/d/1uDEkrD-vPunmR5ItQ74oMhZAOPjv3h1Z/view?usp=sharing

ii.Test.csv  - https://drive.google.com/file/d/1-hnRmq63rsseYlI7aJvTqbpJLnKxVoVd/view?usp=share_link

Customer Life Time  Development Plan.

1. Introduction:
   Customer lifetime value (CLV) is a critical metric that measures the total value a customer brings to a company over the course of their relationship. In the auto 
   insurance industry, CLV is a crucial measure of a company's financial health, as it can help predict future revenue and inform strategic decisions around customer 
   acquisition and retention.

   CLV takes into account a variety of factors, including a customer's spending habits, loyalty to the brand, and potential for future growth. For auto insurance     
   companies, factors like policy renewal rates, claims history, and referral rates all play a role in determining a customer's lifetime value.

   By understanding CLV, auto insurance companies can identify their most valuable customers and tailor their marketing and customer service efforts accordingly. This 
   can help companies maximize revenue while minimizing acquisition costs, ultimately leading to a more profitable business.
   
2. Problem Description : 

   To predict the Customer life time value for an auto insurance company based on different quantitative and qualitative features provided.
   Forecasting is an important approach to take an optimal decision and implement appropriate action plans. A major non-life insurance company wants to evaluate   
   customer life time value based on each customer’s demographics and policy information including claim details. The CLV is a profitability metric in terms of a value    placed by the company on each customer and can be conceived in two dimensions: the customer`s present Value and potential future Value.

3. Methodlogy:

    (I) The First stage is understanding the data. There is dataset provided in this competition. The datasets consist of 
   'CustomerID','Customer.Lifetime.Value', 'Coverage', 'Education','EmploymentStatus', 'Gender', 'Income', 'Location.Geo', 'Location.Code',
   'Marital.Status', 'Monthly.Premium.Auto', 'Months.Since.Last.Claim','Months.Since.Policy.Inception', 'Number.of.Open.Complaints','Number.of.Policies', 
   'Policy.Type', 'Policy', 'Renew.Offer.Type','Sales.Channel', 'Total.Claim.Amount', 'Vehicle.Class', 'Vehicle.Size'.
   This features represents the different properties of the customer helps to understand the customers.

   (II) The Second stage was the Expolratory Data Analysis and Data Preprcessing. In Explorartory Data Analysis we usally see how our data is with the help of       
   descriptive statistics or data visualizations in what way we have to do data preprocessing based on the analysis we have done on the EDA we will preprocess the  
   data. such as type casting,handling for null values in numerical columns and categorical columns,handling the outliers in numerical data types,standardization the      numerical columns,dummifiying the categorical columns.

   (III) Model Building: In the Final stage, using Statistical Models, Machine Learning Algorithms and Ensemble techniques were used.
   
   (IV) Results and Discussions: • For the trained Random Forest Regressor, validation root mean squared error is 0.3141061245083868.
   The evaluation metric used for this project is the Root Mean Squared Error (RMSE) - Square root of the average of squared residuals (prediction errors)
   
    RANDOM FOREST REGRESSION:
    Random forest regressor is a powerful machine learning algorithm used for predicting continuous numerical values, making it a popular choice for tasks such as  
    stock  price forecasting, demand prediction, and house price estimation.Random forest regressor is an ensemble learning method that builds a large number of    
    decision trees and then combines their outputs to make predictions. Each decision tree is trained on a random subset of the training data, and a random subset of 
    the features is considered at each split, making the algorithm less prone to overfitting.

    Tools and Technology Stack: • Jupyter notebook • Python


4. Conclusion: 
   The project has successfully demonstrated the use of Random Forest Regression in the development of customer life time value   
   Prediction model on a dataset consisting of various parameters related to the obtaining of customer life time value. The results were very realistic in nature.
   Machine Learning algorithms and methodologies are currently being used extensively in the insurance sector as a single purpose to aggregate the accuracy and to     
   identify solutions to the problems. 

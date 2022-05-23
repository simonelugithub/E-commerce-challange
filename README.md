# E-commerce-challange
Challenge in collaboration with LUISS University and NTT Data. The goal is to increase the profitability of a real e-commerce. The three main tasks:

1. Customer analysis that aims at identifying groups of users with similar purchasing behaviors in order to create a marketing strategy towards each target (Clustering) 

2. Recommendation System able to provide to each user a set of products related to their interests, in order to maximize the probability of purchase (Product Recommendation) 

3. Shipping time analysis to predict an accurate date of delivery and to reduce delays, in order to improve the quality of the shipping service (Delivery Time Prediction) 


# RFM Analysis 
RFM analysis is a marketing technique used to quantitatively rank and group customers based on the recency, frequency and monetary total of their recent transactions to identify the best customers and perform targeted marketing campaigns.

We calculated the recency (days), the frequency and the amount spent on the store. Divide the scores into Quintiles (1,2,3,4). Attribute each customer a score by a combination of the quantiles

# Recommendation System
Collaborative filtering is commonly used for recommendation system. These techniques aim to fill in the missing entries of a user-item association matrix. It is based on the idea that the best recommendations come from people who have similar tastes. We computed two different approach:

    Model based
    Item based;

Afterwards, we evaluated each model and performed the predictions

# Time Delivery Predictions
We have done three steps:

    Time Delivery Prediction (with XGBoost and Random Forest)
    Delivery Performance (with neural network)
    How to improve delivery performance? (hypotesis testing)
    
In the repository, you can find all the codes and also a report with all the tasks explained at a high level.

# Authors:

    - Enrico Romano
    - Simone Lu
    - Lorenzo Antolini
    - Luca Schisano


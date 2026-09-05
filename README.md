# Customer Subscription Prediction Using Classification Models
Author: Huda Alsaud


## Business Overview & Objective

This study uses data from a Portuguese bank that conducted direct marketing campaigns to promote a long-term term deposit to its customers. The bank contacted customers directly, mainly through telephone calls made by human agents. During these campaigns, information about customers and their interactions with the bank was recorded, including customer characteristics, previous marketing contacts, and whether a customer subscribed to the term deposit.
The main business objective is to improve the efficiency of these direct marketing campaigns by predicting which customers are more likely to subscribe to a term deposit. Using information collected from previous marketing contacts and customer characteristics, the aim is to develop classification models that can distinguish between customers who are likely to subscribe and those who are not.
Comparing different classification models allows us to determine which model provides the most useful predictions for supporting the bank’s customer targeting decisions. The expected business benefit is to focus telephone calls and other resources on a higher-quality group of potential customers, thereby reducing unnecessary contacts while maintaining or improving the number of successful subscriptions.

## Data Used in This Study
The dataset used in this study is the Bank Marketing dataset from the UCI Machine Learning Repository, which contains information collected from marketing campaigns conducted by a Portuguese bank. The data represents 17 marketing campaigns conducted between May 2008 and November 2010, involving a total of 41188 customer contacts.
During these campaigns, customers were offered an attractive long-term deposit with good interest rates. For each contact, information was recorded across several areas, including customer-related features such as age, job, marital status, education, and financial information; features related to the last contact in the current campaign, such as the contact method, timing, and duration; features describing previous and current campaign interactions; and social and economic context features reflecting broader economic conditions.
The dataset therefore provides historical information that can be used to compare different classification models for predicting customer subscription and to examine which customer and campaign characteristics are most strongly associated with successful subscriptions.

## Data Exploration and Feature Understanding
The first step was to understand how the features were distributed and how they were related to the target variable. The analysis showed that the dataset is highly imbalanced, with 88.73% of customers not subscribing to the term deposit and only 11.27% subscribing. 
<img src="Images/ph1.png" width="700"> 

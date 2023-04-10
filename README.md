# Customer Segmentation Project
## Title: Customer Segmentation
### Significance
Most marketplaces use customer segmentation to improve customer service, find new opportunities, and interact with different groups of customers effectively. This project aims to perform customer segmentation on a customer dataset to develop user profiles, categorize customers based on similarities found in the profiles, and ultimately make better decisions that can improve marketing strategies and customer service.

## Expected outcomes
The primary goal is to perform a thorough Exploratory Data Analysis (EDA) on the dataset, which consists of 2240 data points and 29 attributes, and categorize these attributes into four segments: Customer Information, Products, Place, and Promotion. By analyzing several promotions outlined in the dataset, we can understand the effect of these promotions on customers and provide recommendations to the marketing department to improve customer service and support efforts.

## Lessons learned
To understand the dataset better, we need to conduct feature engineering on some categorical features that need to be encoded into numerical forms before performing the modeling process. We can also create additional columns to extract specific information from the categorical features, such as the living situation of sub-categories in the Marital_Status column. Through these techniques, we can make better problem-solving decisions from the dataset and make progress in market research.

##Project Objectives
The project aims to perform customer segmentation on the customer's dataset of the firm by using unsupervised clustering of the data. Customer Segmentation is the practice of separating customers into groups that reflect similarities in attributes such as age, gender, interest, and spending habits. By dividing customers into several groups with different behavioral patterns in spending habits and analyzing the dataset's promotions and campaigns, we can develop user profiles and recommend ways to improve customer service and marketing strategies.

Techniques and Tools
Python is the primary tool for loading, cleaning, processing, and analyzing the dataset. For loading and processing data, we use packages such as pandas, numpy, and matplotlib. To visualize the relationship between variables, we use seaborn to create a scatter matrix and a correlation matrix heat map. To perform dimensional reduction, we use PCA (Principal Component Analysis) from the scikit-learn library, which transforms data from a high-dimensional space to a low-dimensional space while preserving the distribution of original data as much as possible. We use K-means clustering to categorize customers into groups with similar attributes.

Data Loading, Cleaning, and Processing
After loading the customer segmentation data (AMS325_marketing_campaign.csv), we remove missing values and outliers, change the date formulas to DateTime, add new attributes, and change categorical variables to numerical using label encoding. We then use seaborn to create a scatter matrix and correlation matrix heat map to visualize the relationship between variables. We focus on campaign attributes (AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, AcceptedCmp6) and analyze their relation with other features.

Dimensional Reduction
To analyze the dataset's visualizations, we use PCA to perform dimensional reduction. The first main component, PC0, preserves the distribution of the original data as much as possible while reducing the number of dimensions. We plot the reduced dataset to visualize the relationship between variables and use K-means clustering to categorize customers into groups with similar attributes.

Conclusion
Customer segmentation is an important practice that can help improve marketing strategies and customer service. By performing a thorough EDA, categorizing attributes into segments, and analyzing promotions and campaigns, we can develop user profiles and recommend ways to improve customer service and marketing strategies. Python, with packages such as pandas, numpy, matplotlib, seaborn, scikit-learn, and K-means clustering, is a powerful tool for data analysis and dimensional reduction.

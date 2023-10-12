# Customer Segmentation Project

## Project Title: Customer Segmentation

### Significance
Customer segmentation is a crucial strategy in marketing that enhances customer service, identifies new opportunities, and engages with various customer groups effectively. This project aims to explore customer segmentation, understand unique customer needs, and divide them into groups based on similarities found in their profiles.

### Expected Outcomes
The primary objective is to gain a deeper understanding of customers, cater to their individual needs, and improve marketing strategies and customer support. This involves performing an in-depth Exploratory Data Analysis (EDA) on a dataset comprising 2240 data points and 29 attributes, which will be categorized into four segments: Customer Information, Products, Place, and Promotion.

### Lessons Learned
The project identified the need to encode categorical features into numerical formats, conduct feature engineering for attributes like Marital_Status, and prepare the data for analysis. Feature engineering, such as creating a "Live_With" column, is essential to understand the dataset better and make informed decisions for market research.

### Project Objectives
The main objective is to perform customer segmentation using unsupervised clustering on the firm's customer dataset. This involves dividing customers into groups based on attributes like age, gender, interests, and spending habits. The project aims to create user profiles and divide customers into segments that reflect similarities found in their behavior and attributes.

### Techniques and Tools
The project utilizes Python for data loading, cleaning, processing, dimensional reduction, K-means clustering, and data profiling. Python libraries, including numpy, seaborn, scikit-learn, matplotlib, and pandas, are used for data analysis and visualization.

#### Data Loading, Cleaning, and Processing
The project involves data cleaning, which includes handling missing values and outliers, converting date formats to DateTime, adding new attributes, and label encoding categorical variables. Exploratory data analysis is conducted to visualize relationships between variables and focus on campaign attributes' effects on other features.

#### Dimensional Reduction
To handle the high dimensionality of the dataset (29 attributes), Principal Component Analysis (PCA) is used to reduce it to three dimensions. This helps in preserving the original data's distribution while simplifying the analysis.

#### K-Means Clustering for Segmentation
K-means clustering is applied to the data after PCA. The optimal number of clusters is determined using the Elbow method. In this project, four clusters are created, dividing customers into different groups based on income and spending habits.

### Observations
After performing K-means clustering, four distinct customer groups are identified based on income and spending. These groups are categorized as very low spending and income, very high spending and income, high spending and income, and low spending and income. Observations show differences in promotions accepted, the number of deals purchased, and campaign acceptance rates among these groups. Additionally, data profiling reveals the majority of customers are relatively young parents with small to medium-sized families.

### Conclusion
The project successfully achieves its main objective of customer segmentation, providing insights into customer spending behavior, income, and demographics. Recommendations are made for the marketing department and CEO based on the findings, such as focusing on high-income customers and those with children, and tailoring promotions to different customer segments.


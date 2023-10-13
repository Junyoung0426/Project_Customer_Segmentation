# Customer Segmentation Project


## Table of Contents
1. [Project Title: Customer Segmentation](#project-title-customer-segmentation)
2. [Significance](#significance)
3. [Expected Outcomes](#expected-outcomes)
4. [Lessons Learned](#lessons-learned)
5. [Project Objectives](#project-objectives)
6. [Techniques and Tools](#techniques-and-tools)
    1. [Data Loading, Cleaning, and Processing](#data-loading-cleaning-and-processing)
    2. [Dimensional Reduction](#dimensional-reduction)
    3. [K-Means Clustering for Segmentation](#k-means-clustering-for-segmentation)
7. [Observations](#observations)
8. [Conclusion](#conclusion)

## About this file":
- https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis
- Customer Personality Analysis is a comprehensive examination of an ideal customer profile for a company. It serves as a valuable tool for businesses to gain deeper insights into their customer base, enabling them to tailor products and services to better match the unique needs, behaviors, and concerns of distinct customer groups. This analysis empowers businesses to adapt their product offerings to cater to specific customer segments, rather than expending resources on marketing new products to all customers in their database. Instead, a company can identify the customer segment most likely to purchase a particular product and focus marketing efforts exclusively on that segment.
  
### Project Title: Customer Segmentation

### Significance
- Customer segmentation is a vital marketing strategy.
- It enhances customer service, identifies new opportunities, and engages with various customer groups effectively.
- This project explores customer segmentation, understands unique customer needs, and divides them into groups based on similarities found in their profiles.

### Expected Outcomes
- Gain a deeper understanding of customers.
- Cater to individual needs and improve marketing strategies and customer support.
- Conduct in-depth Exploratory Data Analysis (EDA) on a dataset with 2240 data points and 29 attributes.
- Categorize attributes into four segments: Customer Information, Products, Place, and Promotion.

### Lessons Learned
- Encode categorical features into numerical formats.
- Conduct feature engineering, such as creating a "Live_With" column.
- Understand the dataset better for informed decisions in market research.

### Project Objectives
- Perform customer segmentation using unsupervised clustering on the firm's customer dataset.
- Divide customers into groups based on age, gender, interests, and spending habits.
- Create user profiles and divide customers into segments reflecting their behavior and attributes.

### Techniques and Tools
- Python for data loading, cleaning, processing, dimensional reduction, K-means clustering, and data profiling.
- Python libraries: numpy, seaborn, scikit-learn, matplotlib, and pandas.

#### Data Loading, Cleaning, and Processing
- Handle missing values and outliers.
- Convert date formats to DateTime.
- Add new attributes.
- Label encode categorical variables.
- Conduct Exploratory Data Analysis (EDA) to visualize relationships between variables.

#### Dimensional Reduction
- Use Principal Component Analysis (PCA) to reduce dataset dimensionality.
- Preserve the original data's distribution while simplifying the analysis.

#### K-Means Clustering for Segmentation
- Apply K-means clustering to the data after PCA.
- Determine the optimal number of clusters using the Elbow method.
- Create four clusters, dividing customers based on income and spending habits.

### Observations
- Four customer groups identified based on income and spending.
- Groups categorized as very low spending and income, very high spending and income, high spending and income, and low spending and income.
- Differences in promotions accepted, deals purchased, and campaign acceptance rates among these groups.
- Majority of customers are relatively young parents with small to medium-sized families.

### 8. Conclusion
- Project successfully achieves customer segmentation objectives.
- Provides insights into customer spending behavior, income, and demographics.
- Recommendations made for the marketing department and CEO to tailor promotions and focus on specific customer segments.
